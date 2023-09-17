## Welcome to my twinBASIC projects repository!

I've been stubbornly sticking to VB6 for decades now. It's how I got my start in programming, and I believe it offers a combination of simplicity/RAD and low level capability in a way still unmatched by anything else, until twinBASIC burst onto the scene. [twinBASIC](https://www.twinbasic.com) is a language+IDE currently being developed that aims to be 100% backwards compatible with the VB6/VBA7 language, and unlike so many disappointments in the past, is nearly there and progressing every day! It offers x64 compilation and a laundry list of new features, [see a list of the ones added so far here](https://github.com/twinbasic/documentation/wiki/twinBASIC-Features); it's got a community and issue tracking [here on GitHub](https://github.com/twinbasic/twinbasic). I'm a huge fan of the project, and have brought a number of my VB6 projects over, upgrading them to x64 compatibility, and made several original projects with no VB6 equivalent. In addition, I've made x64-native versions of a number of open soure projects I've enjoyed over the years. 

**Check out:**

### [TBEventTrace](https://github.com/fafalone/EventTrace)

This is my ETW Kernel Logger File Activity Monitor, which uses multithreading and the incredibly complex and unfriendly ETW API to get information on disk and file operations directly from the kernel logger. 
![image](https://github.com/fafalone/fafalone/assets/7834493/c4e8bdb3-790e-4e80-942c-e1144fa7ec58)


### [ShellControls](https://github.com/fafalone/ShellControls)

These are my ucShellBrowse and ucShellTree controls, now with x64 compatibility so they can be compiled for use in x64 hosts like 64bit VBA.

![image](https://github.com/fafalone/fafalone/assets/7834493/3780f7b2-736b-4dde-8dc2-3461b365c9b7)


### [Lems64](https://github.com/fafalone/Lems64)

Lemmings was one of my favorite games as a kid. Carles PV recreated it in pure VB6 code, and I brought it into tB and made it native x64, not that you see a performance benefit to such an ancient game from that. 

![image](https://github.com/fafalone/fafalone/assets/7834493/e10a8917-99f2-4980-9205-335fc45ca12b)

### [UI Ribbon Demos](https://github.com/fafalone/UIRibbonDemos)

A modern language should take advantage of modern UI elements, right? This repository has 3 demos, a beginner proof of concept and two intermediate level demos (advanced still being worked on!)

![image](https://github.com/fafalone/fafalone/assets/7834493/7f6b3819-0fba-4a79-b834-29e693ed20bd)

### [HelloWorldDriver](https://github.com/fafalone/HelloWorldDriver)

My proof-of-concept kernel mode driver. VB6... BASIC... KERNEL MODE!? Yes, you read that right. Notorious VB6 genius The trick figured out how to make one in VB6, I've brought that to twinBASIC and 64bit-- there's no WOW64 for the kernel! tB has built in features to support making these, so it's a lot easier and the lack of runtime means it's much more capable.

![image](https://github.com/fafalone/fafalone/assets/7834493/4a62e5a8-1296-4981-808b-48def307bfb2)

### [RunAsTrustedInstaller](https://github.com/fafalone/RunAsTrustedInstaller)

Ever got tired of being told you don't have permission for something *when you're the administrator*? This lets you run not only as the actual admin SYSTEM level, but run as the TrustedInstaller process, which owns most of the most highly-restricted folders, registry keys, etc.

![image](https://github.com/fafalone/fafalone/assets/7834493/f50e5da0-6504-42b3-b756-c2cd001f26bc)

### [cTaskDialog64](https://github.com/fafalone/cTaskDialog64)

A 64bit update to my popular cTaskDialog class, which not only provides an easy-to-use class wrapping all of the TaskDialog functionality, but adds additional controls and flags.

![image](https://github.com/fafalone/fafalone/assets/7834493/14d873c4-aa36-4d84-8680-669d66e95d9c)

---

**[...and many more!](https://github.com/fafalone?tab=repositories)**

Other projects include tbShellLib, which adds thousands of Windows interfaces and APIs to make programming in tB more like programming in C/C++ with Windows.h included, Color Emojis, basicNES -- a Nintendo emulator in pure BASIC, a PropertySheet demo, a control hosting IExplorerBrowser, and an in-progress Device Manager clone.
