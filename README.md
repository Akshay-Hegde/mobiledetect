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

## Other methods

isMobile()	
isTablet()	
Custom detection methods
isiPhone()	
isBlackBerry()	
isHTC()	
isNexus()	
isDell()	
isMotorola()	
isSamsung()	
isLG()	
isSony()	
isAsus()	
isPalm()	
isVertu()	
isPantech()	
isFly()	
isSimValley()	
isGenericPhone()	
isiPad()	
isNexusTablet()	
isSamsungTablet()	
isKindle()	
isSurfaceTablet()	
isAsusTablet()	
isBlackBerryTablet()	
isHTCtablet()	
isMotorolaTablet()	
isNookTablet()	
isAcerTablet()	
isToshibaTablet()	
isLGTablet()	
isPrestigioTablet()	
isYarvikTablet()	
isMedionTablet()	
isArnovaTablet()	
isArchosTablet()	
isAinolTablet()	
isSonyTablet()	
isCubeTablet()	
isCobyTablet()	
isSMiTTablet()	
isRockChipTablet()	
isTelstraTablet()	
isFlyTablet()	
isbqTablet()	
isHuaweiTablet()	
isNecTablet()	
isPantechTablet()	
isBronchoTablet()	
isVersusTablet()	
isZyncTablet()	
isPositivoTablet()	
isNabiTablet()	
isKoboTablet()	
isDanewTablet()	
isTexetTablet()	
isPlaystationTablet()	
isGalapadTablet()	
isGenericTablet()	
isAndroidOS()	
isBlackBerryOS()	
isPalmOS()	
isSymbianOS()	
isWindowsMobileOS()	
isWindowsPhoneOS()	
isiOS()	
isMeeGoOS()	
isMaemoOS()	
isJavaOS()	
iswebOS()	
isbadaOS()	
isBREWOS()	
isChrome()	
isDolfin()	
isOpera()	
isSkyfire()	
isIE()	
isFirefox()	
isBolt()	
isTeaShark()	
isBlazer()	
isSafari()	
isTizen()	
isUCBrowser()	
isDiigoBrowser()	
isPuffin()	
isMercury()	
isGenericBrowser()	
isiphone()	
isIphone()	
istablet()	
isIOS()