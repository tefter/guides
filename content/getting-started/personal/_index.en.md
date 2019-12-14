---
title: "Personal"
date: 2019-12-12T11:02:05+06:00
type: "post"
---

{{< rawhtml >}}
  <img class="inpage-hero" src="/images/getting_started_personal.svg"/>
  <br/>
{{< /rawhtml >}}

You're setting up Tefter for personal use. For a team, read [here][team-setup].

To take better advantage of all the features of Tefter, follow the steps below.

## Import Bookmarks

You can import bookmarks from a variety of sources.

We support:
* [Pocket][pocket] ([select](https://tefter.io/pocket/import))
* [Pinboard][pinboard] ([select](https://tefter.io/pocket/import))
* [Google Bookmarks][google-bookmarks]
* All major browsers.

We do our best to preserve folders and labels and map them to Tefter lists and tags.

If you with to import from a service not yet supported, let us know by
sending an [email](mailto:support@tefter.io).

## Install a Browser Extension

With the extension you can quickly add bookmarks of the page you're
visiting, search and resolve [aliases][aliases].

First click one of the following buttons to install it.

{{< rawhtml >}}
  <a class="btn btn-primary" href="https://chrome.google.com/webstore/detail/tefter/eldofalegbgagpenjjcapjaogpioldoh">Chrome</a>
{{< /rawhtml >}}

{{< rawhtml >}}
<a class="btn btn-primary" href="https://addons.mozilla.org/en-US/firefox/addon/tefter/">Firefox</a>
{{< /rawhtml >}}

For older browsers there's also a
{{< rawhtml >}}
<a href="javascript:q=location.href;if(document.getSelection)%7Bd=document.getSelection();%7Delse%7Bd='';%7D;p=document.title;void(open('https://www.tefter.io/bookmarks/new?showtags=yes&source_app=bookmarklet&uri='+encodeURIComponent(q)+'&notes='+encodeURIComponent(d)+'&title='+encodeURIComponent(p),'tefter','toolbar=no,scrollbars=yes,width=750,height=700'));">bookmarklet</a>
{{< /rawhtml >}}
, which you can drag to the browser's bookmarks bar.

### Using the Extension

To add a bookmark, click the Tefter icon.

![extension add bookmark](/images/getting_started/extension_add_bookmark.gif)

## Install the Mobile App

Visit Tefter on your favourite browser on your phone, then select "Add
Tefter to Home Screen".

{{< rawhtml >}}
  <img class="inpage-hero" src="/images/getting_started/install_mobile_app.jpg"/>
{{< /rawhtml >}}

[team-setup]: {{< relref "../organizations/_index.en.md" >}}
[pocket]: https://app.getpocket.com/
[pinboard]: https://pinboard.in/
[google-bookmarks]: https://www.google.com/bookmarks/
[aliases]: {{< relref "../../features/aliases/_index.en.md" >}}
[bookmarklet]: javascript:q=location.href;if(document.getSelection)%7Bd=document.getSelection();%7Delse%7Bd='';%7D;p=document.title;void(open('https://www.tefter.io/bookmarks/new?showtags=yes&source_app=bookmarklet&uri='+encodeURIComponent(q)+'&notes='+encodeURIComponent(d)+'&title='+encodeURIComponent(p),'tefter','toolbar=no,scrollbars=yes,width=750,height=700'));
