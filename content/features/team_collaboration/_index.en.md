---
title: "Team Collaboration"
date: 2019-12-12T11:02:05+06:00
icon: "ti-package"
description: "Features enabling team collaboration"
type: "pages"
weight: 10
---

#### Login

Any Slack workspace member who wishes to create or modify content of
Tefter for the organization has to log in first. By logging in a Slack
member account is connected to a Tefter one.

Use `/tefter login` to connect your accounts.

**Adding bookmarks**

You can use the `/tefter <url>` command or a Slack
message action to add a bookmark.

{{< rawhtml >}}
<details>
  <summary>
  Demo of the command
  </summary>

  <img src="https://i.imgur.com/YBYWJyd.gif" alt="slack integration add bookmark">
</details>
{{< /rawhtml >}}

{{< rawhtml >}}
<details>
  <summary>
  Demo of the message action
  </summary>

  <img src="https://i.imgur.com/VQQ2OxX.gif" alt="slack integration add bookmark">
</details>

<br/>
{{< /rawhtml >}}

#### Searching

You can use the `/tefter search <query>` command or mention the
`@tefter` bot to search.

An example using the mention might be:

`Yo @tefter search functional programming`

💡 There's a short version of the search command. It's just `s`.  
Example: `/tefter s agile`

{{< rawhtml >}}
<details>
  <summary>
  Demo of the search command
  </summary>

  <img src="https://i.imgur.com/4wqaTL4.gif" alt="slack integration search command">
</details>

<br/>
{{< /rawhtml >}}

#### Sharing search results with others

When searching for any results that you wish to share to the members of
the channel, you can select "share".

{{< rawhtml >}}
<details>
  <summary>
  Demo of the sharing action
  </summary>

  <img src="https://i.imgur.com/raQBXG9.png" alt="slack integration share action">

  <img src="https://i.imgur.com/rVmMTVj.png" alt="slack integration share action response">
</details>

<br/>
{{< /rawhtml >}}

Keep in mind that @tefter has to be invited to that channel first.

#### Creating an alias

`/tefter alias <alias> <url_pattern>`


Example:

`/tefter alias api-docs https://tefter.io/docs/api`

or with a dynamic alias

`/tefter alias deb-tracker https://tracker.debian.org/pkg/{{*}}`

Read more about aliases in the section below.

#### Resolving an alias

`/tefter <alias_pattern>`

Example:

`/tefter deb-tracker/nginx`

or by mentioning `@tefter`

`@tefter deb-tracker/nginx`

#### Listing all aliases

`/tefter aliases`

or by mentioning `@tefter`

`@tefter aliases`

#### Listing the most popular bookmarks

`/tefter news`

Our ranking algorithm factors in recency, likes and views.

![tefter-news-command](https://i.imgur.com/XmrFUhs.png)

