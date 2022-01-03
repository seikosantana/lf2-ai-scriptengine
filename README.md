# lf2-ai-scriptengine
Modified clone of zort's fork of the ddraw wrapper.
Nothing really changed. I only build the angelscript SDK to get the angelscript.lib, and get the missing angelscript.h from angelscript SDK for the script engine to build.
Original zort's repository: https://github.com/zort/lf2-ai-scriptengine

I hope this simplifies building the ddraw wrapper and helps maintaining the development of this DLL and keeping Little Fighter 2 alive.
Writing AIs for LF2 is just _fun_!

ddwrapper.sln is the solution file that contains all projects.  
To build this dll, you'll need Windows SDK. The targetted Windows SDK version is 10.0.16299.0, using build tools v141.
  
If you just need the DLLs (binaries) to develop your AIs or even just to play with custom AIs, don't bother compiling or even looking at the sources.  
Instead, use these links:  
Debug (fit if you want to write AIs)  
https://github.com/seikosantana/lf2-ai-scriptengine/raw/master/Debug/ddraw.dll  
Release (if you only want to use AIs)  
https://github.com/seikosantana/lf2-ai-scriptengine/raw/master/Release/ddraw.dll


Sorry if I didn't do this by 'fork' or anything. I was new to Github back then. Let me know if i violate anything.
Thank you


Related:  
- [AI Script Engine 2.32 forum post](https://lf-empire.de/forum/showthread.php?tid=11004)
- [Github repository, made some minor improvements (zort's post)](https://lf-empire.de/forum/showthread.php?tid=10945)
- [[2.2]Programmable AI via scripting](https://lf-empire.de/forum/showthread.php?tid=7927)
- [AI Scripting Forum on Little Figher Empire Forums](https://lf-empire.de/forum/forumdisplay.php?fid=56)
