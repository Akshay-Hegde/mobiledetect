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

## Check if device is running iOS OS

{{ if { mobiledetect:isiOS } }}
This is an iOS Device
{{ else }}
This is not an iOS Device
{{ endif }}

## Check if device is iPhone

{{ if { mobiledetect:isiPhone } }}
This is an iPhone Device
{{ else }}
This is not an iPhone Device
{{ endif }}

## Check if device is iPod

{{ if { mobiledetect:isiPod } }}
This is an iPod Device
{{ else }}
This is not an iPod Device
{{ endif }}

## Check if device is a tablet
{{ if { mobiledetect:isTablet } }}
This is a Tablet Device
{{ else }}
This is not a Tablet Device
{{ endif }}