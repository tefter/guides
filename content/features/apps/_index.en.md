---
title: "Apps"
date: 2019-12-12T11:02:05+06:00
type: "post"
---

{{< rawhtml >}}
  <img class="inpage-hero" src="/images/apps.svg"/>
{{< /rawhtml >}}

## Getting Started

The most convenient way to install an app on your current device is to
navigate to this [page](https://tefter.io/install_app) and click "install".

For video instructions, watch the following:

{{< rawhtml >}}
  <iframe width="560" height="315" src="https://www.youtube.com/embed/Nib9TPTgc-Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
{{< /rawhtml >}}

### Desktop

![desktop-app](https://i.imgur.com/TggU5w2.png)

To download, see [here](https://github.com/tefter/desktop#downloads)

### Mobile

When you have the mobile app installed, you can quickly add bookmarks by sharing links to Tefter.

![share-to-tefter](https://i.imgur.com/yHrmMqE.jpg?1)

**Installation**

To install the app on Android, navigate to [install_app](https://tefter.io/install_app).
For iOS devices, watch this [instructional video](https://www.youtube.com/watch?v=Y32Jn2XCfJo).

### Browser Extensions

**Install**

* [Chrome / Brave](https://chrome.google.com/webstore/detail/tefter/eldofalegbgagpenjjcapjaogpioldoh)
* [Firefox](https://addons.mozilla.org/en-US/firefox/addon/tefter/)
* [Bookmarklet](https://tefter.io/faq#bookmarklet)

---

With the extension you can:

* Add / Edit bookmarks
* Search your history
* Search your open tabs
* Search your bookmarks
* Navigate to [aliases][aliases]

#### New Tab

The extension changes your default new tab page to be like the following.

![extension-menu](/images/newtab.png)

Depending on the browser, you may have to press `tab` to focus the search input.
You may type to search and press `enter` to navigate to the selected link. To select a search result
use either the arrow keys, `ctrl + j / k (vim-like)` or the mouse.

To disable Tefter as your new tab, click the settings link at the bottom
of the page. Then deselect the "Enable new tab page" option and click save.

![extension-menu](/images/newtab_settings.png)

If you can't find the settings link, you either click
[here](chrome-extension://bpaaeloknanjdlmhbobaeiapbgillkge/content/options.html) for
Chrome and
[here](moz-extension://e5de1692-8064-b046-ad4d-94f03e21cc02/content/options.html) for Firefox.

#### Add bookmark

You can quickly add bookmarks clicking on the Tefter icon.

![extension-menu](/images/extension_menu.png)

#### Search

To search history, open tabs and bookmarks hit `alt + k` or `option + k` on MacOS.
The shortcut is configurable on Chrome, see: [chrome://extensions/shotcuts](chrome://extensions/shotcuts).

Alternatively you can search straight from the address bar, by typing `t` followed by the `tab` key (Chrome) 
or `t` followed by the `space` key (Firefox).

![chrome-omnibar](/images/omnibar.gif)

#### Permissions

The extension asks for the following permissions:

**Tabs**

It requires access to your open tabs, so that you can navigate to any of them and make them searchable.

**ContextMenus**

You can right-click on any link to add a bookmark.

**History**

It analyzes your history, ranks it and makes it searchable. All the data
manipulation stays on your machine. The extension never sends any of
your data to a remote server.

**Intercept Requests**

To navigate to aliases (see section below). It only intercepts
navigation to URLs starting with `go/`.

#### Aliases

Aliases are shortcuts to links you commonly use, read more about them [here][aliases].
With the extension installed, you may navigate to an alias, let's say
you got an alias `maps` pointing to `https://maps.google.com`. Then all
you need to do is type `go/maps` in the address bar and hit enter.

### Command-Line

![demo-cli](/images/cli_logo.png)

There's a command-line app for MacOS and Linux.

![demo-cli](/images/cli_demo.png)

Install via brew

```shell
brew tap tefter/homebrew-cli
brew install tefter
```

You may alternatively download the pre-built packages yourself from:
https://github.com/tefter/cli/releases


[aliases]: {{< relref "../../features/aliases/_index.en.md" >}}
