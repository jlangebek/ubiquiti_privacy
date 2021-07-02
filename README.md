# ubiquiti_privacy
List of known addresses that Ubiquiti uses for phoning home - I use it for my Pi-Hole setup...

This hosts file is a collection of hosts that Unifi Dream Machine or related Unifi hardware (switches+access points)
uses for "phoning home" to Ubiquiti in spite of opt-outs, etc.
The phoning home is not necessarily a privacy problem, but the issue is that Ubiquiti does add new "features" over time
and do not document the need and the functionality of the "phoning home".
This hosts file is a collection of hosts that Unifi Dream Machine or related Unifi hardware (switches+access points)
uses for "phoning home" to Ubiquiti in spite of opt-outs, etc. 
As Ubiquiti (to the best of my knowledge) has not disclosed detailed information on what is being collected, the lack of transparency means no privacy trust per default.

It started after looking into these threads (community members):
- https://community.ui.com/questions/Concerns-over-Ubiquiti-Privacy-Policy-Preventing-Enterprise-Deployment/9970c8ef-74ff-4841-89c5-174ef375acb3
- https://community.ui.com/questions/86232-DNS-queries-to-static-ubnt-com-in-24hrs-Data-Collection-Where-is-the-OPT-OUT/63972679-034f-4a83-bc85-6664253e3cd8#answer/cbb7d497-9edd-4d6c-99cb-dd2e7ee1dd7f 

The hosts contained in this file are based on Pi-Hole logging on the latest version of Unifi software (controller, etc)

Each section documents a number of addresses spotted by using UI hardware. The "Probably used for" and "Privacy view"
describes in my laymans terms what these addresses are most probably used for (as there is no real central documentation
of this, to the best of my knowledge), and "Privacy view" describes why this is blocked (ie. in this file).
