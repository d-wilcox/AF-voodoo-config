# AF-voodoo-config

**To get Allied Force running on newer hardware**

1.  Install Falcon Allied Force (install in default programs directory under the c:)
2.  Download and install the official patch 1.0.13
3.  In your Allied Force root folder create or edit BFops.cfg file add line set g_bForceSoftwareGUI 1
4.  Download and extract dgVoodoo ([http://dege.freeweb.hu/dgVoodoo2/dgVoodoo2/](http://dege.freeweb.hu/dgVoodoo2/dgVoodoo2/ "http://dege.freeweb.hu/dgVoodoo2/dgVoodoo2/")  )
5.  Copy all .dll files from the dgVoodoo MS folder to your Allied Force directory.
6.  Copy this config to that same directory ([https://github.com/d-wilcox/AF-voodoo-config/blob/928778ddf6d6db05e11c8af73807eb22974ee098/dgVoodoo.conf](https://github.com/d-wilcox/AF-voodoo-config/blob/928778ddf6d6db05e11c8af73807eb22974ee098/dgVoodoo.conf "https://github.com/d-wilcox/AF-voodoo-config/blob/928778ddf6d6db05e11c8af73807eb22974ee098/dgVoodoo.conf")  )
7.  Run Allied Force
8.  Go to graphic settings and set video driver and mode to use dgVoodoo
9.  Set your preferred resolution.
10.  Play! Have Fun!

**For Better Graphics**

1.  Install Aeyes Widescreen cockpits (looks like the site is no longer available)
2.  Install HiTilesAF ([https://www.hitiles.com/indexF4AF.htm](https://www.hitiles.com/indexF4AF.htm "https://www.hitiles.com/indexF4AF.htm")  )
3.  Add -g5 parameter to the FalconAF.exe. It should look something like this. "C:\Program Files (x86)\Lead Pursuit\Battlefield Operations\FalconAF.exe" -G5 (this will allow you to further increase the landscape and object detail in the game options)
4.  Download the LOD editor tool ([https://thommos.com/wiki/index5f8e.html?title=LOD_Editor](https://thommos.com/wiki/index5f8e.html?title=LOD_Editor "https://thommos.com/wiki/index5f8e.html?title=LOD_Editor") I use version 6.10)
5.  Run LOD editor as admin - Go to menu Dev utilities > database utilities > increase min lod distance (15000) click “check”. This will update LODs that are too far and also too close. This will prevent texture pop in.
