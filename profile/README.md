<div align="center">
 <h1>clib+</h1>
 <p>A complete system built-in mixed standard C library package using the minimial libraries that comes with just about any linux OS</p>
</div>

# About

This is a package that extend the minimum linux built-in packages to abstract low-level functions, see more below for more information on the libs created.
Please note that using this package may can increase binary size due to certain libs being used within each-other. Which wouldn't be any difference from using a higher-level language. If you aren't creating application that will proform protection check-sum operation and need better proformance.

<b>Why?</b>

To avoid re-inventing the wheels for future projects and to attract more developer(s) to move to C and have to something to start with that isn't going to kill their motivation in the process of learning when approaching memory management

# Coming Soon

- An application serving as a github-based repo package manager. Allowing you to download certain libs from this organization repo list from linux CMD-Line (ex: ctypes -i net -extra)

- A quick and temporary python script will be made for this until an official version is made...!

# Progress

<p>Symbol Definitions:<p>

<p>✅ = Completed<br />🛠️ = Being Worked On<br />⚠️ = Needs Work</p>

```
✅    Garbage Collector Lib
✅⚠️  Thread Lib 
✅⚠️  String Lib
✅⚠️  Array Lib ( Could use improvements )
✅⚠️  Map Lib ( Could use improvements )
🛠️⚠️  Request Lib
✅⚠️  Web Server Lib
🛠️    Web Socket Lib
🛠️⚠️  cGUI Lib
```

# Install

Installing the extension library is just as easy as 

```
    // Install the package manager
git clone https://github.com/clibplus/clibplus.git
cd clibplus; make

    // Install libraries using the package manager
    // pm -i str

        cLib+ Package Manager | v0.0.1 [BETA]
Usage: pm [OPTIONS]....

   Flag            Description
______________________________________________
   -l             List of cLib+ sub-pkg and sub-libs
   -i             Install a cLib+ sub-pkg or sub-library
   -r             Show a list of cLib+ Libraries to install
```

# Have Questions Or Want to Contribute?

For contributions, just fork -> edit -> PR. All PR will be reviewed before accepting or leaving a comment reporting any issues.

Join our discord server and get in contact with a dev to get started! [Server](https://discord.gg/nDB7QARjCU)
