# DokuWiki Mattermost Notifier

A DokuWiki plugin that notifies a Mattermost instance of wiki edits.

![Example notification](https://github.com/jtdroste/dokuwiki-mattermost-notifier/raw/master/example.png)

## Install

Download the latest [Release](https://github.com/jtdroste/dokuwiki-mattermost-notifier/releases) and install the plugin using the [Plugin Manager](https://www.dokuwiki.org/plugin:plugin).  Refer to [Plugins](https://www.dokuwiki.org/plugins) on how to install plugins manually.

## Configure

1. Create an Incoming Webhook on mattermost

2. Enter the webhook into the mattermost configuration section in DokuWiki's Configuration Settings

3. Don't forget https://docs.mattermost.com/administration/config-settings.html#enable-integrations-to-override-usernames

## Credits
This is based on the work done by [mallchin](https://github.com/mallchin), with minor edits to work with Mattermost.
