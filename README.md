# lf2-ai-scriptengine
Modified clone of zort's fork of the ddraw wrapper.
Nothing really changed. I only build the angelscript SDK to get the angelscript.lib, and get the missing angelscript.h from angelscript SDK.

I hope this simplifies building the ddraw wrapper and helps maintaining the development of this DLL and keeping Little Fighter 2 alive.
WRITTING AIs for LF2 is just FUN!

ddwrapper.sln is the solution file that contains all projects.  
To build this dll, you'll need Windows SDK. The targetted Windows SDK version is 10.0.16299.0, using build tools v141.
  
If you just need the DLLs (binaries) to develop your AIs or even just to play with custom AIs, don't bother compiling or even looking at the sources.  
Instead, use these links:  
Debug (fit if you want to write AIs)  
https://github.com/seikosantana/lf2-ai-scriptengine/raw/master/Debug/ddraw.dll  
Release (if you only want to use AIs)  
https://github.com/seikosantana/lf2-ai-scriptengine/raw/master/Release/ddraw.dll


Sorry if I didn't do this by 'fork' or anything. I'm just not used to it. Let me know if i violate anything.
Thank you
