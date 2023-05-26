# Adding new page

Once the markdown file is generated, follow the below steps.

## 1. Adding markdown file to its proper directory

- The mardown file should be added to its proper folder in the `docs/` directory. For example:
	- A new page categorized as resource should be stored at `docs/ressources/new-page.md`.
	- A new CIDOC CRM's Introduction page should be stored at `docs/v7.1/info/new-page.md`.
	- A new CIDOC CRM's Class page should be stored at `docs/v7.1/classes/new-page.md`.

## 2. Adding path/to/file to config

- In order for the new page link to be accessible from the top header, its path to file must be added to the `header_pages` in the `docs/_config.yml` file. For example:
	- `v7.1/info/intro.md`
  - `ressources/index.md`
- Note that files of the same directory must be added in **alphabetical order**.

## 3. Adding Jekyll front matter

### CIDOC CRM pages

The following front matter template must be add to the beginning of the markdown file:

```yaml
---
layout: page
title:  {page_title_fr}
titleEn: {page_title_en_fr}
permalink: {url_path}
sidebar: {sidebar_filename}
group: {sidebar_group}
date: {last_update_date}
---
```

- `page_title_fr`: The French title of the page. *Note: DO NOT include colon `:` in the title, replace colon with dash/hyphen `-`.*
- `page_title_en_fr`: The bilingual title of the page with English first, and French follows, separated by a hyphen, i.e. `English title - French title`. *Note:*
	- *DO NOT include colon `:` in the title, replace colon with dash/hyphen `-`.*
	- *For entities pages, only include the code once, e.g. E14 Condition Assessment - Évaluation d’état matériel.*
- `url_path`: The URL path of the page. The part before the last segment (last forward slash) is the same as the part of the permalink of pages in the same directory. For example:
	- A new CIDOC CRM's Introduction page has the permalink `/v7.1/information/new-page`.
	- A new CIDOC CRM's Class page has the permalink `/v7.1/classes/new-page`.
	- *Note: The last segment could be anything of choice, but use dash/hyphen `-` in place of space, and DO NOT use accent for French link.*
- `sidebar_filename`: The filename of the sidebar (table of content) of the page, which is stored in `docs/_data/`. See [Creating table of content section below](#4-creating-table-of-content) for further details. 
	- This value is required only if the page has a table of content to be displayed in the left sidebar.
	- *Note: The ToC of all CIDOC CRM's pages are included in the same file.*
- `sidebar_group`: The value of the `group` key in the `sidebar_filename` under which all associated pages are listed. 
- `last_update_date`: The date the page content was last modified, in the format `yyyy-mm-dd`.

### Resources pages

The following front matter template must be add to the beginning of the markdown file:

```yaml
---
layout: page
title:  {page_title_fr}
permalink: {url_path}
sidebar: {sidebar_filename}
tab: {header_tab}
date: {last_update_date}
---
```

- `page_title_fr`: The French title of the page. *Note: DO NOT include colon `:` in the title, replace colon with dash/hyphen `-`.*
- `url_path`: The URL path of the page. The part before the last segment (last forward slash) is the same as the part of the permalink of pages in the same directory. For example:
	- A new page categorized as resource has the permalink `/ressources/new-page`.
	- *Note: The last segment could be anything of choice, but use dash/hyphen `-` in place of space, and DO NOT use accent for French link.*
- `sidebar_filename`: The filename of the sidebar (table of content) of the page, which is stored in `docs/_data/`. See [Creating table of content section below](#4-creating-table-of-content) for further details. 
	- This value is required only if the page has a table of content to be displayed in the left sidebar.
	- *Note: Each page has its own ToC YAML file.*
- `header_tab`: The name (lowercase) of the top header tab that the new page can be found, thus required only if the page is under a tab. Currently, the only tab value is **ressources**.
- `last_update_date`: The date the page content was last modified, in the format `yyyy-mm-dd`.

## 4. Creating table of content

Create a YAML file of the same name as `sidebar` value of the page's front matter. It is stored in either `docs/_data/`.

**Template for ToC of pages other than those belong to CIDOC CRM:**

```yaml
class: mainlist
toc:

- class: sublist
  subfolder:
	- title: {heading_1}
	  hash: {heading_1_id}
	  class: sublist
	  subfolder:
	  - title: {heading_2}
	  	hash: {heading_2_id}

- title: {title_en}
  hash: en
  class: sublist
  subfolder:
  - title: {heading_1_en}
    hash: {heading_1_id_en}
```

- Basically, for each heading, two values must be included:
	- `title`: The heading itself.
	- `hash`: the html "id" value of the heading. It is the heading in lowercase and any whitespace is replaced with hyphen `-`. For French heading with accents, the "id" must be redefined in the markdown file iself by adding `{#value-with-no-acccent}` next to the heading. The redefined `value-with-no-accent` is the value of this hash.

- If there were sub-headings, two values must be added at the same level at the heading:
	- `class`: The value is always **sublist**.
	- `subfolder`:
		- Add the required two values (`title` and `hash`) for each sub-heading.

- If there were translated English content (following the French content), add the following values:
	- `title_en`: The page title in English.
	- `hash`: The value is always **en**.
	- Headings and sub-headings are added as described above.

- Note: Each page should have its own ToC file (YAML), except for pages of CIDOC CRM, all of which ToC are included in the same file per version.

**Template for ToC of pages belong to CIDOC CRM:**

```yaml
class: mainlist
heading: {sidebar_heading}
toc:

- title: {group_name_uppercase}
  group: {group_name_lowercase}
  class: mainlist
  subfolder:
  - title: {page_title_fr}
    url: {page_url}
    class: sublist
    subfolder:
    - title: {heading_1_fr}
      hash: {heading_1_id_fr}
```

- `heading`: The heading at the top of the sidebar, usually the version of the CIDOC CRM, e.g. Version 7.1.
- `group_name_uppercase`: The name of the toggle group in uppercase. If not much changes are made to the structure of CIDOC CRM documentation, there are three groups: INFORMATION, CLASSES, and PROPRIÉTÉS.
- `group_name_lowercase`: The name of the toggle group in lowercase without accents, which is also the value of the key `group` in the page's front matter. If not much changes are made to the structure of CIDOC CRM documentation, there are three values: information, classes, and proprietes.
- For each page, four values must be included:
	- `page_title_fr`: The title of the page, in French only.
	- `page_url`: The value of the permalink found in the page's front matter as explained in the section above.
	- `class`: The value is always **sublist**.
	- `subfolder`:
		- Add the required two values (`title` and `hash`) for each highest heading, French only.
		- For sub-headings, follow the instructions for ToC of pages other than those belong to CIDOC CRM.

## 5. HTML embedded images (diagrams.net)

- Generate and copy the HTML embed code in digrams.net:
	- Select `File/Embed/HTML...`
	- Select `Open in New Window` from the dropdown of Links.
	- Click `Create`.
	- Copy the HTML code
- Paste the copied HTML code to where the image should be on the page.
	- Delete `<script type="text/javascript" src="https://viewer.diagrams.net/js/viewer-static.min.js"></script>`.
	- Replace `border:1px solid transparent` with `border:1px solid #cccccc`.


# Editing existing pages

When edit an existing markdown, be cautious when changes are made to the following components:

1. **File location**:
	- When a file is moved, make sure to edit its path/to/file in the `_config.yml` file.
	- If the file's new location also indicates the tab under which the page would be found, make sure to edit the `tab` value in the front matter accordingly.
2. **Heading**:
	- Edits must also be done in the corresponding ToC YAMl file, for example, text edit and/or rearrangement of the page's sections.








