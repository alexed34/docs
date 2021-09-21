# Service overview

{{ wiki-full-name }} a service for creating a corporate knowledge base, which is filled and updated by company users and employees.

On {{ wiki-name}} pages, you can store information that employees need for work: memos, useful links and contacts, instructions, project documentation, and personal notes. {{ wiki-name }} gives the company's employees additional opportunities for collaboration: they can share information, search for answers to frequently asked questions, and discuss issues in the page comments.

## Access to {{ wiki-full-name }} {#access}

Users registered in [{{ org-full-name }}](../organization/index.yaml) can work in {{ wiki-full-name }}. For an organization, its own knowledge base is created in {{ wiki-full-name }}, which is only accessible to employees. Read about how to connect {{ wiki-full-name }} in the cluster [{#T}](enable-wiki.md).

To get access to {{ wiki-name }}, [log in to the account](login.md) that you use for the organization.

If the company has a user and access management system (for example, Active Directory or Google Workspace), employees can use their corporate accounts to log in to the {{ yandex-cloud }} organization and access {{ wiki-name }} using a Single Sign-On (SSO) system. To do this, the organization administrator must set up an identity federation. Read more in the {{ org-full-name }} documentation under [Managing Identity Federations](../organization/add-federation.md).

## {{ wiki-full-name }} features {#features}

- [Create Wiki pages](quick-guide.md) with text, images, tables, and links.

- When formatting text, use [Markdown markup](static-markup.md) to highlight text fragments and add titles, lists, quotes, and other elements.

- Track user edits to pages in the [history of changes](history.md). You can compare two versions of a page or restore a version from the history.

- To structure information on the Wiki, create a page tree and link the pages with cross-references. Read more in [{#T}](structure.md).

- To quickly find information on {{ wiki-name }}, use the [search](search.md), subscribe to pages, and add them to your [favorites](notifications.md).

- Configure [access rights to pages](page-managment/access-setup.md): you can open a page to all or some employees, restrict the ability to edit, or prohibit viewing a page.

- Use {{ wiki-name }} integration with {{ tracker-full-name }} and {{ forms-full-name }}:

  * [Adding a list of issues from {{ tracker-full-name }} to a page](actions/objects.md#section_task_list).

  * [Embedding a form on a page](actions/objects.md#forms).

  * [Saving responses from {{ forms-full-name }} on a page](../forms/send-wiki.md).
