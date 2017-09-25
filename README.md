# Typecho-CommentToMail
A plugin for typecho to notify readers of new comments by sending emails via SMTP.

This plugin is modified from [CommentToMail](https://github.com/byends/CommentToMail).
The original author of CommentToMail is [Byends Upd.](http://www.byends.com).
The original original author is [DEFE](http://defe.me).

## Modifications
2. Removed async sending, as with modern SSL it causes way too many bugs.
3. Removed logging and caching - these causes unnecessary disk operations, which may cause lag on some systems.

## Installation
Just drop the *CommentToMail* folder into *usr/plugins/* folder under your Typecho installation, and enter your SMTP information into the control panel.
