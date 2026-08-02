Battlefield 1942 Remote Admin (BFRA)
Version 1.0.0
Copyright (c) 2026 Xberg

=================
Description
=================

Battlefield 1942 Remote Admin (BFRA) is a modern Windows
remote administration tool for Battlefield 1942 servers
running Battlefield Server Manager (BFSM).

BFRA is a complete rewrite of the original Battlefield
Remote Manager (BFRM) with a modern interface, improved
stability and many quality-of-life improvements while
remaining compatible with BFSM 2.0 and 2.01.

=================
Requirements
=================

- Windows 10 or Windows 11
- Battlefield Server Manager (BFSM) 2.0 or 2.01
- A valid BFSM user account


=================
Installation
=================

1: Unzip BFRA.
2: Copy BFRemoteManager.ini to the same folder. (If you have it)
3: Double click BFRemoteAdmin.exe to run it.
4: You can remove BFRemoteManager.ini if you did copy it.

=================
Features
=================

- Connect to one or more BFSM servers.
- Modern resizable interface.
- System, Dark and Light themes.
- Dashboard mode with multiple pages.
- Live server status.
- Server, Game, Friendly Fire, Misc and Admin settings.
- Map rotation editor with drag & drop.
- Player administration.
- Ban management, with duration and update option.
- BFSM user management.
- Scheduled server actions.
- Connected BFSM client list.
- Built-in server log viewer.
- Buddy system with custom names.
- Automatic reconnect handling.
- Optional player menu download from the server.

=================
BFSM Access Rights
=================

BFRA follows the access rights configured in BFSM.

Pages and actions are automatically hidden or disabled
when the connected BFSM account does not have permission
to use them.

BFRA also introduces one additional derived permission:

D - Clear Bans

This is not a BFSM permission.

The "Clear all bans" button is only available when the
connected account has the following BFSM permissions:

    Status
    Maps
    Players
    Banlist
    Users
    Clients
    View server log

This extra check helps prevent accidental removal of the
entire ban list by users with limited administrative
permissions.

=================
Buddy System
=================

Buddy names are stored locally and are never uploaded to
the server.

Buddy lists are isolated per BFSM server using the BFSM
IP address and port.

Example:

102.168.1.10:14667|0123456789abcdef0123456789abcdef|BFSoldier

The same player may therefore have different buddy names
on different servers.

If the user has big role he will then instead see
admins in player list.

You can turn off the buddies in Options, but you cant
turn of showing admins other than setting the admin
color to same color as normal players have.

=================
Configuration
=================

BFRA stores its configuration in:

BFRemoteAdmin.ini

Additional files:

BFRemoteAdminBuddies.con
PlayerMenu.con
BFRemoteAdmin.log

=================
Notes
=================

BFRA is an unofficial third-party administration tool.

Battlefield is a trademark of Electronic Arts Inc.

This software is not affiliated with, endorsed by,
sponsored by, or approved by Electronic Arts Inc.,
DICE or Black Bag Operations.

=================
Project
=================

Author:
    Xberg

Project:
    Battlefield 1942 Remote Admin (BFRA)

=================
Version History
=================

1.0.0
- Initial public release.
