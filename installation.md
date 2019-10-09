---
description: >-
  System Administrators need to install the Webex plugin on the Mattermost
  server to make this functionality available to Mattermost end-users.
---

# Installation

## Plugin Installation

1. In Mattermost version 5.16 and above, the easiest way to install a Mattermost plugin is by clicking on the "Settings" menu button above the channel list. Select "Plugin Marketplace", search for "Webex" and click "Install"
   1. Alternatively, download one of the binary releases from the [GitHub page](https://github.com/mattermost/mattermost-plugin-webex/releases) for the webex plugin
   2. Go to Settings --&gt; Plugins --&gt; Upload Plugin. Select the file you downloaded, upload it to the server. In server 5.14+, plugins will automatically be distributed across an Enterprise cluster of Mattermost servers, prior to v5.14 you will need to deploy the plugin on each server manually.
2. Go to settings --&gt; Plugin Management and Enable the Webex Meeting Plugin



## Configuration

1. Go to Settings --&gt; Scroll down to the `Plugins` section, and click on `Webex Plugin`
2. Insert the Webex Meetings URL for your organization. It is often in the format of &lt;companyname&gt;.my.webex.com or &lt;companyname&gt;.webex.com.

