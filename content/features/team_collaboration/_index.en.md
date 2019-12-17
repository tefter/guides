---
title: "Team Collaboration"
date: 2019-12-12T11:02:05+06:00
icon: "ti-package"
description: "Features enabling team collaboration"
type: "pages"
weight: 3
---

{{< rawhtml >}}
  <img class="inpage-hero" src="/images/team_collaboration.svg"/>
{{< /rawhtml >}}

Tefter enables team collaboration through its Slack application.
Click the button below to install it on your workspace.

{{< rawhtml >}}
<a class="btn btn-primary" href="https://tefter.io/integrations/slack_direct_install_callback">Install</a>
{{< /rawhtml >}}

After installing, read [here][org-setup] to set up your organization.

### Available Commands

After installing the Slack app, you may either use `/tefter <command>` or its shorter
equivalent `/t <command>`.

Begin with `/t help` to list some of the ways you can interact with it.

#### Login

Any Slack workspace member who wishes to create or modify content on
Tefter for the organization, has to log in first. By logging in a Slack
member account is connected to a Tefter one.

Use `/t login` to connect your accounts.

#### Adding bookmarks

You can use the call the root tefter command or a Slack message action to add a bookmark.

```
/t <url>
```

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

You can use the `/t search <query>` command or mention the
`@tefter` bot to search.

An example using the mention might be:

`Yo @tefter search functional programming`

:bulb: There's a short version of the search command. It's just `s`.  
Example: `/t s agile`

{{< rawhtml >}}
<details>
  <summary>
  Demo of the search command
  </summary>

  <img src="https://i.imgur.com/4wqaTL4.gif" alt="slack integration search command">
</details>

{{< /rawhtml >}}

You may also browse the bookmarks of an organization you're member of
from the web or the apps by using a filter.

{{< rawhtml >}}
  <img src="/images/org_filter.png" alt="org filter">
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

{{< /rawhtml >}}

:warning: Keep in mind that `@tefter` has to be invited to that channel first.

#### Creating an alias

```
/t alias <alias> <url_pattern>
```

Example:

```
/t alias api-docs https://tefter.io/docs/api
```

or with a dynamic alias

```
/t alias deb-tracker https://tracker.debian.org/pkg/{{*}}
```

Read more about aliases in the section below.

#### Resolving an alias

```
/t <alias_pattern>
```

Example:

```
/t deb-tracker/nginx
```

or by mentioning `@tefter`

```
@tefter deb-tracker/nginx
```

#### Listing all aliases

```
/t aliases
```

or by mentioning `@tefter`

```
@tefter aliases
```

#### Listing the most popular bookmarks

```
/t news
```

Our ranking algorithm factors in recency, likes and views.

![tefter-news-command](https://i.imgur.com/XmrFUhs.png)

[org-setup]: {{< relref "../../getting-started/organizations/_index.en.md" >}}
