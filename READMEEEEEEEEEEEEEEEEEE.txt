Congradulations, you have successfully downloaded FreeSCAN.
This project is being released as open source because I really don't have time to maintain it anymore and feel the community could do a better jobs.

There are however a few caveats:
*FS was developed a very long time ago, perhaps 2009, in an older development environment. Since then, it has been carted and converted to newer one, the latest being Visual Studio 2010.
*The conversion was never completed properly, so there are about a million compiler warnings about legacy code that is unsupported. It will probably not compile in newer versions of VS.
*FS was originally designed to support one scanner only, the BC246T. The memory model required to support this was not a very complicated one. I didn't know about OOP at the time of development so the entire memory model is based on a multi-dimensional array. Yes, this could be done far far better, but it's an old project.
*You will need to get your own API key to use RadioReference import functions.
*Don't ask me for tech support
*Don't bitch about how things are done, be they inefficient, wrong, whatever. 
*If people are willing to fix existing issues I will be happy to integrate the changes into the main branch. These include fixing the broken Google maps, fixing upload/download features on the new style scanner, and fixing the ailing logging system.
*You need the NAudio plugin for this to work properly.
