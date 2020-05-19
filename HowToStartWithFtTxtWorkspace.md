# How to setup my fischertechnik SLI workspace in Eclipse?

Now that [our toolbox](./WhichToolsYouNeed.md) is ready, it is time to learn how to get started with your own project via the examples.

## How to set up the FtTxtWorkspace?
`H:/workspaces` has been used  in this example as path to the `FtTxtWorkspace`. But feel free to use your own path.
- Download the `FtTxtWorkspace.zip` from the [txt_demo_ROBOPro_SLI/releases](https://github.com/fischertechnik/txt_demo_ROBOPro_SLI/releases)
- Unzip this file in the `H:/workspaces`. This will looks like something like:

  <img src="./docs/WSSetup/start(01).PNG" width= "65%" >
- Start now Eclipse <br/>
  Select the right path to your workspace, here: `H:/workspaces/FtTxtWorkspace`:<br/>
  Press `Launch`.

  <img src="./docs/WSSetup/start(02).PNG" width="65%">

- Close the `Welcome` screen

   <img src="./docs/WSSetup/start(03).PNG" width="80%" >

   You will see this screen

  <img src="./docs/WSSetup/start(04).PNG" width="80%" >

- Go in the top menu to the item `Windows` en select `Preferences`

  <img src="./docs/WSSetup/start(04A).PNG" width="80%" >

- Select `C/C++`, `Build` and then `Environment`, <br/>
  add a new Environment variable `LINAROMAP`,<br/>
  and take your map with the Linaro toochain as value (no / or \ at the end!!),<br/>
  Press `Apply` and `Apply and Close`.

  <img src="./docs/WSSetup/start(04B).PNG" width="80%" >

  You will see this screen again:

  <img src="./docs/WSSetup/start(04).PNG" width="80%" >

-  Go in the top menu to the item `FIle` en select `Import`<br/>
   Select `General` and `Existing Projects into Workspace`<br/>
   Press `Next`.

  <img src="./docs/WSSetup/start(05).PNG" width="80%" >

-  Enter the root directory of the workspace FtTxtWorkSpace,<br/>
   select the appearing 3 projects,<br/>
   press `Finish`.

  <img src="./docs/WSSetup/start(06).PNG" width="80%" >

- If everything went well, you will see this.<br/>
   In the Eclipse map Includes (this is not the same as the user map inlcudes) you will see something like this. The ${LINARO} variable has been fill in nicely.

  <img src="./docs/WSSetup/start(07).PNG" width="80%" >

   Your workspace is now ready to use, to start programming and testing.
   For example, you can start with compiling the first project `TxtSharedLibraryInterface`.
    - The [xxx document]() will describe how you can get the result to work on the TXT and you will learn about a strategy for troubleshooting and error discovering.
    - The [xxxx document]() will describe how you can create a new project and then start working on your own project.
  - With File | Import you can also add other existing projects to your workspace. Eclipse is very versatile, see it as a challenge to discover the available possibilities step by step.






# document history
- 2020-05-18/19 CvL 466.1.1 new
  Original from: on-line training SLI-programming<br/>
  © 2020-04 ing. C. van Leeuwen Btw.  Enschede Netherlands
