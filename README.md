# mwForum Readme

## Introduction

mwForum is an open-source, Web-based discussion forum system. mwForum is based on [Perl](http://www.perl.com/) CGI scripts, uses a [MySQL](https://mariadb.org/), [PostgreSQL](http://www.postgresql.org/) or [SQLite](http://www.sqlite.org/) database and is compatible with [mod_perl](http://perl.apache.org/) 1.0 and 2.0 for optimal performance. mwForum's design goals are comfortable operation and administration, stability, security and speed, a professional and consistent look, and lean and clean code to make customization easy.

## Documentation

* README.md: this file
* doc/Install.html: installation guide (incl. system requirements)
* doc/FAQ.html: administration topics
* doc/Changes.html: list of new features, changes and bugfixes
* doc/Upgrade.html: instructions for upgrading older installations
* doc/Develop.html: development/customization notes
* LICENSE: the GNU General Public License

## License

mwForum is Copyright © 1999-2015 Markus Wichitill.

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software foundation; either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

## Features

This is an overview of the main features of mwForum, not a complete list. Many features are optional, especially those that impact performance.

* Forum
    * Supports Perl CGI, mod_perl 1.x and 2.x
    * Supports MySQL, PostgreSQL and SQLite databases
    * Highly configurable via online form
    * Valid HTML5.
    * Styling via CSS stylesheets, multiple user-selectable styles
    * Language modules, user-selectable
    * Uses Unicode/UTF-8
    * Private messages, with export
    * Chat page
    * Atom and RSS feeds
    * Event logging with log browser
    * Attachment list with image gallery mode
    * Searching, optionally with fulltext index and/or Google
    * Plugin interfaces: authen, authz, include, event, log, message display
    * Export/import between different mwForum installations
    * Supports IPv6 addresses
* Boards
    * Grouping by collapsible categories
    * Read access: everybody, registered users, selected user groups
    * Write access: everybody, registered users, selected user groups
    * Moderated boards where only approved posts are visible
    * Posting by unregistered users
    * Archiving
* Topics
    * Threaded or non-threaded
    * Polls, with single or multiple votes
    * Collapsible branches in threaded topics
    * Moving and deleting of whole topics and topic branches
    * Manual and automatic locking
    * Expiration
    * Merging
    * Tags and icons
* Posts
    * Post preview
    * Editing, with optional time limitation
    * Quoting in good old email/news style
    * Additional post field for source code etc.
    * Text snippet insertion
    * File attachments
    * Thumbnails resizing for attached images
    * Reporting of rule-violating posts
    * Post content rating with statistics
    * Tracking of which posts are new/old in current session
    * Tracking of which posts are unread/read independent of session
    * Notifications when words on watch list appear in new posts
    * Notifications when users on watch list post new posts
    * Overviews containing all new or unread posts, per topic, board or for whole forum
    * Markup [tags] with insertion buttons, predefined and custom
    * Manual and automatic linking of URLs
    * Configurable :tags:
    * Censored words
    * Flood protection
    * Video embedding
* Users
    * Cookie-based and OpenID login
    * Various captcha
    * Click-through policy agreement
    * User info pages with public profiles
    * Configurable user profile fields
    * Avatars, uploaded and gallery, automatic resizing, users can disable display
    * Signatures, short and simple or long incl. markup, users can disable display
    * Notifications for replies, messages, moderator actions etc.
    * Lists of newest, online and birthday users on main page
    * Expiration, after x days absence and/or if never logged in
    * User list for all users with public info
    * User list for admins, can display and search all fields
    * Ranks based on post count
    * User titles and badges
    * GeoIP country detection
    * User groups, public and non-public, joinable or managed
    * Birthdays
    * Ignoring
    * Banning
* Email
    * SMTP, sendmail or mail transport
    * RFC 2554 authentication
    * OpenPGP encryption
    * Bounce detection
    * Instant and digest subscriptions of boards and topics
    * Notifications for replies and private messages
    * Registration can optionally require valid address

## Credits

* Markus Wichitill
    * Author and maintainer.
* Philip Mak
    * Author of Text::Flowed, long-time hosting of mwforum.org.
* Daði Örn Jónsson, Matthias Althaus, Tobias Jaeggi
    * Testing, bug reports and feedback.
* The jQuery Team
    * Authors of the jQuery Javascript library. License: MIT.
* Dylan Verheul
    * Author of the jQuery-autocomplete Javascript library. License: MIT.
* Mark James
    * Creator of the Silk icon set, used for the Default2 style and button icons. License: CC Attribution 3.0.
    * Creator of the recommended 16x11 flag icons. License: Public domain.
* 上山根 祐輔 (Yusuke Kamiyamane)
    * Creator of the Fugue and Diagona icon sets, used to complement the Silk icons. License: CC Attribution 3.0.
* Benjamin Franz
    * Author of CGI::Minimal Perl module, on which MwfCGI.pm is based. License: Artistic/GPL.
* Milivoj Ivkovic
    * Author of Mail::Sendmail Perl module, on which MwfSendmail.pm is based. License: "Do whatever you want with it."
