# Android-security
A curated list of resources to study Android security for a beginner
![](https://img.shields.io/badge/android%20-security-blue.svg)

1. [Week 1](#week1)
2. [Week 2](#week2)
3. [Week 3](#week3)
4. [Week 4](#week4)
5. [Week 5](#week5)
6. [Week 6](#week6)
7. [Extra Stuff](#extra)
8. [Tools](#tools)

---
## <a name="week1"></a>Week 1
* Decompile an APK file: [ApkTool](https://ibotpeaches.github.io/Apktool/)`Reverse engineering and disassembling tool`

* Understanding the directory structure
	[codepath](https://guides.codepath.com/android/Android-Directory-Structure)

	[howtodoinjava](https://howtodoinjava.com/android/android-tutorial-android-project-structure-files-and-resources/)

* Working of android(Internal)
    [Addictivetips](https://www.addictivetips.com/mobile/android-partitions-explained-boot-system-recovery-data-cache-misc/)

    [Android](https://source.android.com/devices/bootloader/partitions-images)

	[Book](http://newandroidbook.com/AIvI-M-RL1.pdf)

## <a name="week2"></a>Week 2
* 	Setup basic android hacking lab
		[Medium Blog](https://medium.com/@ehsahil/basic-android-security-testing-lab-part-1-a2b87e667533)

## <a name="week3"></a>Week 3
* 	View Source code
		> Unzip app.apk -o app
		> open exampe dir and do "d2j-dex2jar classes.dex"
		> Decompile the generated .classes file with [Java decompiler](http://java-decompiler.github.io/)

* 	Permissions (use apktools and open AndroidManifest.xml)
		[Android Developer](https://developer.android.com/guide/topics/permissions/overview#normal-dangerous)

## <a name="week4"></a>Week 4
* 	Understanding Android OS
		[Android Application security](https://manifestsecurity.com/android-application-security-part-2/)

* 	Android Application fundamentals
		[Android application security](https://manifestsecurity.com/android-application-security-part-3/)

*  	Introduction to adb, apktool, dex2jar and jd-gui
		[Android application security](https://manifestsecurity.com/android-application-security-part-3/)

## <a name="week5"></a>Week 5
* 	Intentionally vulnerable apps for practice
		[DIVA](https://payatu.com/damn-insecure-and-vulnerable-app/)
		[OWASP goatdroid](https://github.com/nvisium-jack-mannino/OWASP-GoatDroid-Project)
		[Android insecure bank](https://github.com/dineshshetty/Android-InsecureBankv2)

* 	Insecure data storage
		[Vuln](https://manifestsecurity.com/android-application-security-part-8/)

* Absence of binary protection
	[Vuln](https://manifestsecurity.com/android-application-security-part-9/)

## <a name="week6"></a>Week 6
* 	Insufficient protection of communication channel
		[Vuln](https://manifestsecurity.com/android-application-security-part-10/)
		[Mobilesecurity.gitbook.io](https://mobile-security.gitbook.io/mobile-security-testing-guide/general-mobile-app-testing-guide/0x04f-testing-network-communication)

* 	Developer Backdoor Hard coded credentials :D

* 	Testing Authenticatio mechanism
		[Vuln](https://manifestsecurity.com/android-application-security-part-12/)

## <a name="week7"></a>Week 7

* 	[Vuln] Weak Cryptography
		[Mobile-security.gitbook.io](https://mobile-security.gitbook.io/mobile-security-testing-guide/general-mobile-app-testing-guide/0x04g-testing-cryptography)
		[Manifestsecurity](https://manifestsecurity.com/android-application-security-part-13/)

*	Infufficient Transport Layer Protection
		[Mobile-security.gitbook.io](https://mobile-security.gitbook.io/mobile-security-testing-guide/general-mobile-app-testing-guide/0x04f-testing-network-communication)
		[Manifestsecurity](https://manifestsecurity.com/android-application-security-part-10/)

* 	Unintented Data leakage
		[Manifestsecurity](https://manifestsecurity.com/android-application-security-part-11/)


## <a name="extra"></a>Extra Reference and resources

* [Appsec Wiki](https://appsecwiki.com/#/README)
* [Manifest Security](https://manifestsecurity.com/)
* [Android security Awesome](https://github.com/ashishb/android-security-awesome)
* [OWASP mobile testing guide](https://github.com/OWASP/owasp-mstg)
* [Android sec reference](https://github.com/doridori/Android-Security-Reference)
* [Android Lab](https://github.com/sh4hin/Androl4b)
* [Android's official vulnerability disclosure](https://source.android.com/security/bulletin/)
* [Exploits from Exploit-DB](https://www.exploit-db.com/search?platform=android)

## <a name="tools"></a>Tools

* [Quark](https://github.com/linkedin/qark/)
* [Frida](https://www.frida.re/)
* [Radare2 - Reversing](https://github.com/radareorg/radare2)
* [Virus Total](https://www.virustotal.com/)
* [APKAnalyzer](https://github.com/sonyxperiadev/ApkAnalyser)
* [Apktool](https://ibotpeaches.github.io/Apktool/)
* [Android Framework for Exploitation](https://github.com/appknox/AFE)
* [Dwarf - RE](https://github.com/iGio90/Dwarf)
