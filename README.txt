  ////////////////////////////////////////////////////
 /// UAC PROMPT BYPASS - EVADE ADMIN RESTRICTIONS ///
////////////////////////////////////////////////////

Overview:
    This program uses the very simple "CMSTP Bypass" method to run an executable
    file with elevated privileges. A user selected a Windows executable file, the
    program builds a CMSTP configuartion file, and it loads it via cmspt.exe

    At this point, another prompt will open up (cmstp confirmation dialog) at which
    point the program will throw the <ENTER> key on behalf of the user (so the user
    does not have to be bothered with it) and thusforth the program will be loaded
    into memory with admin elevation. No need to address to UAC prompt or enter in
    admin credentials.

Bug report:
    None, but if you find anything, or if this bypass method finally gets patched 
    and no longer works, please leave a pull-request.



                                                                   Use responsibly!
