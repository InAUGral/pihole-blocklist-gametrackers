# pihole-gametrackers
Pihole list of game related trackers to block (PC gaming)

**Description:**
Blocklists to block the communication to game related trackers or domains that are otherwise undesireable.
The goal of this list is to block any telemetry and tracking domains that are used by game related services ONLY. Any domains that are general or impact the use of said service or application. If that is something people desire perhaps we can make a "paranoid" version of this list.
Feel free to log an issue if you want to have a domain added and it will be tested for impact prior to adding to the list.


**Prerequisites:**

A working Pihole installation

**Installation:**

Go to the Group management on the left menu on the Pihole web page and go to Adlists.

Add the following URL to Address field.

Address: https://raw.githubusercontent.com/InAUGral/pihole-gametrackers/main/pihole-gametrackers.txt
Comment field (optional): Gametrackers

Here are Tutorials where you can learn how to add blocklists to  Pi-hole in more detail if you need:

Pi-hole: https://discourse.pi-hole.net/t/how-do-i-add-additional-block-lists-to-pi-hole/259

Author:
InAUGral

Contributors:
Ungstein
