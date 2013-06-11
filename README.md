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

## Check if device is iPad

{{ if { mobiledetect:isiPad } }}
This is an iPad Device
{{ else }}
This is not an iPad Device
{{ endif }}

## Check if device is a tablet
{{ if { mobiledetect:istablet } }}
This is a Tablet Device
{{ else }}
This is not a Tablet Device
{{ endif }}

## Check if device is a Samsung tablet
{{ if { mobiledetect:isSamsungTablet } }}
This is a Samsung Tablet Device
{{ else }}
This is not a Samsung Tablet Device
{{ endif }}