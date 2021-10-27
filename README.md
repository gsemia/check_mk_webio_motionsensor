# check_mk_webio_motionsensor
Check_MK Motion Sensor SNMP Plugin for a WebIO EA 2x2

# Dependency
Check-mk 1.6.x

# Install
To install the plugin merge the content of the check_mk folder into the /omd/sites/#sitename#/local/share/check_mk folder

# Notes 
The SNMP must be enabled on the webio devices
They must be added as host to check_mk which is monitored via snmp for the Motion Service to be added.