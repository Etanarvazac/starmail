# star Mail
Originally developed by [sword7 on GitLab](https://gitlab.com/sword7/starmail) and [released on Spigot](https://www.spigotmc.org/resources/star-mail.73406/).

Star Mail adds mailboxed, letters, and packages to the game and pays close attention to details to deliver an immersive mailing experience. Player can send three types of mail by default: letters, books, and packages. Players with the `mail.custom` permission will be able to send any item as mail.

### Letters
Letters are available in Minecraft 1.14 and up and are similar to books, but are cheaper to craft. This plugin does use a custom model resource pack which you can download from sword7 [here](https://gitlab.com/swordo/starmail/-/wikis/misc/Resource-Pack)

### Packages
**Sending:** Packages are used to send multiple items. Right-clicking an empty package to open the menu where you can place the items you want to send. Once packed, click the seal button and the the items in the package will be tracked using the tracking number on the item. 

**Receiving:** Right-click on the package and click any of the strings to open the package. Once opened, all items can be collected by clicking on the fishing pole or closing the menu. Once empty, the package vanishes in a poof of smoke.

**Decoration:** Empty packages can be used as decoration by right-clicking while sneaking. Sealed packages can not be placed.

### Tracking & Expiration System
Information about any package are tracked and stored while the server is offline. As a preventitive measure on storage spack, tracked packages will expire after 30 days by default. This value can be changed in the `config.yml` and `-1` can be set to disable expiration.

### Mailboxes
Players can register a mailbox by simply placing a mailbox block. By default, players can only register one mailbox. However, this can be changed in the `config.yml` or by granting the permission `mail.boxes.<amount>` to a user or group. Clicking on another player's mailbox will open a menu allowing the player to send a valid mail item to the recipient. When new mail arrives, players are notified when it's received and shorty after joining. These notifications can be disabled in the mailbox menu in-game.

### Globalbox
Interacting with the globalbox will open the mail collection menu and is a globally used mailbox.

### Postbox
Interacting with the postbox allows players to send mail to other players.

### Email
Star Mail includes email which can be used to send mail from anywhere long as the player has permissions to `/sendto <player>` and the recipient has access to `/mailbox`. Using `/mailbox` will open a virtual mailbox to access this type of mail.

### Supported integrations
[Dynmap](https://www.spigotmc.org/resources/dynmap%C2%AE.274/)
