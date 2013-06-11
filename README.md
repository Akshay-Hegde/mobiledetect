mobiledetect
============

PyroCMS plugin implementation of Mobile_Detect library (http://mobiledetect.net/)

All kudos go to Victor Stanciu and Serban Ghita who wrote the library, I just adapted it to use it as a plugin in PyroCMS.

#Usage

{{ mobiledetect:isAndroidOS }} will return TRUE or FALSE



## Check if device is a mobile device
{{ if { mobiledetect:isMobile } }}
This is a Mobile Device
{{ else }}
This is not a Mobile Device
{{ endif }}

## Check if device is running Android OS

{{ if { mobiledetect:isAndroidOS } }}
This is an Android Device
{{ else }}
This is not an Android Device
{{ endif }}

## Check if device is a tablet
{{ if { mobiledetect:isTablet } }}
This is a Tablet Device
{{ else }}
This is not a Tablet Device
{{ endif }}