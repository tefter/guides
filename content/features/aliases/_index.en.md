---
title: "Aliases"
date: 2019-12-12T11:02:05+06:00
type: "post"
---

{{< rawhtml >}}
  <img class="inpage-hero" src="/images/alias.svg"/>
{{< /rawhtml >}}

You can create shortcuts to links you commonly use. We call such shortcuts `aliases`.

Registering an `api-docs` to `https://verylongnameapplication.com/api-docs` allows you to
type `go/api-docs` in your browser's address bar to navigate there.
Think of it as a https://www.golinks.io/ alternative.

Aliases can either be private for a user or they can be global for an organization.

![list-aliases](https://i.imgur.com/aZvW1QV.png)

### Creating an Alias

You can use the {web, mobile, desktop} UI to create a new alias, or you
can use the Slack integration.

For example, let's say you assign an alias to `https://security-tracker.debian.org/tracker/source-package/{{*}}`
to `deb-sec`.

![new-alias](https://i.imgur.com/LlN0JNB.png)

Then when you navigate to `https://tefter.io/go/deb-sec/nginx` you'll be redirected to
`https://security-tracker.debian.org/tracker/source-package/nginx`.

Aliases can be static, or dynamic. Dynamic aliases contain variable segments. Use `{{*}}` to create dynamic segments.

So, an alias `ex` pointing to `https://example.com/{{*}}/a/{{*}}/b/{{*}}` when invoked with
`go/ex/1/2/3` will redirect to `https://example.com/1/a/2/b/3`.

**Browser Extension**

You can use the browser extension to quickly navigate using aliases.
This is currently only available in Chrome.

![aliases-extension](https://i.imgur.com/oxoYBtu.gif)

### Resolving an Alias

#### Search bar

You may also navigate using aliases from the search bar.

![search-bar-demo](https://i.imgur.com/oGRZVSI.gif)

#### Command-Line Usage

We're working on command-line application you can use to interact with Tefter.
Until it's released you can use a simple shell function like the following to navigate using aliases.

```shell
# Add this to your .zshrc
te() {
  open "https://tefter.io/go/$1"
}
```

![terminal-app](https://i.imgur.com/EJw1Hx6.gif)

## Coming Soon

Functions in dynamic aliases.
