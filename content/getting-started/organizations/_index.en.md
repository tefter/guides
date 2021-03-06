---
title: "Setting up a Team"
date: 2019-12-12T11:02:05+06:00
type: "post"
---

{{< rawhtml >}}
  <img class="inpage-hero" src="/images/organizations_setup.svg"/>
{{< /rawhtml >}}


### Prerequisites

To create a team you have to connect Tefter to your Slack workspace.
Then the members of your workspace can use Tefter for bookmarking and aliases.

You can read about the team features [here][team-features].

### Installing the Slack Application

Click the button below

{{< rawhtml >}}
<a class="btn btn-primary" href="https://tefter.io/integrations/slack_direct_install_callback">Install</a>
{{< /rawhtml >}}

or visit the Slack directory [app page](https://slack.com/apps/AFBC4A147-tefter).

[team-features]: {{< relref "features/team_collaboration/_index.en.md" >}}

### Permissions

Keep in mind that we don't ask for a permission to read all the messages of the workspace.
Tefter only operates on commands and mentions.

When you click the button to install the app, you should see a screen
like:

{{< rawhtml >}}
  <img class="inpage-hero" src="/images/slack_permissions.webp"/>
{{< /rawhtml >}}

### Your Teams

After installing the app, your workspace will be visible in your [organizations](https://tefter.io/organizations).

{{< rawhtml >}}
  <img class="inpage-hero" src="/images/orgs_list.webp"/>
{{< /rawhtml >}}

### Add your first bookmark


From your Slack workspace, call:

```
/t https://tefter.io
```

To add your first bookmark.

Any member of the workspace may then call:

```
/t search tefter
```

to retrieve that bookmark.


### Inviting Members

While every member of the workspace can read content added to the team, not everyone can add or edit.
Any member who wishes to do that, must call the following command on Slack:

```
/t login
```

To quickly invite users to your team, first click on the icon of
the team in the sidebar, then select "invitations".

{{< rawhtml >}}
  <img src="/images/getting_started/org_invites_path.png"/>
{{< /rawhtml >}}

In the invitations page, select any users you wish to invite from the
dropdown and click "invite".

{{< rawhtml >}}
  <img src="/images/getting_started/org_invites.png"/>
{{< /rawhtml >}}


### Managing the Team

#### Transferring Ownership

The person who installs the app becomes the admin of the Tefter team.
From within your team, you can make any other member the admin as show in
the image below:

{{< rawhtml >}}
  <img src="/images/transfer_admin.png"/>
{{< /rawhtml >}}


#### Removing Members

Click on the bin icon on a member to remove them from the team.

{{< rawhtml >}}
  <img src="/images/getting_started/remove_member.png"/>
{{< /rawhtml >}}
