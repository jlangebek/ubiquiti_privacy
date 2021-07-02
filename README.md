# ubiquiti_privacy
# List of known addresses that Ubiquiti uses for phoning home
# This hosts file is a collection of hosts that Unifi Dream Machine or related Unifi hardware (switches+access points)
# uses for "phoning home" to Ubiquiti in spite of opt-outs, etc.
# The phoning home is not necessarily a privacy problem, but the issue is that Ubiquiti does add new "features" over time
# and is not so good at documenting the need and the functionality of the "phoning home".
#
# The hosts contained in this file are based on Pi-Hole logging on the latest version of Unifi software (controller, etc)
#
# Each section documents a number of addresses spotted by using UI hardware. The "Probably used for" and "Privacy view"
# describes in my laymans terms what these addresses are most probably used for (as there is no real central documentation
# of this, to the best of my knowledge), and "Privacy view" describes why this is blocked (ie. in this file).