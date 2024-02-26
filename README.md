# WaspPremiumCracked
Setup (Windows) Full installation setup of Simba, SRL, WaspLib and Scripts



Setting up

To use Simba you pretty much only need to run it. However, since Simba needs to create some files and folders to work, I recommend you make a folder for it. For simplicity sake you can name it "Simba" and then put your Simba.exe in that folder. simba directory

Next, you are ready to run the crack and download the premium scripts. Open Crack.CMD to patch simba.

Now you are ready to run it! Depending on where you placed your Simba.exe, the first time you run it you might get a warning from Windows Defender SmartScreen like this: warning 1 Click "More info". warning 2 And then "Run anyway".

Wait for Simba to open up...

Once it opens for the first time, you can optionally associate simba scripts with simba: associate scripts

It doesn't really matter what you choose... I choose Yes.

Now you can also optionally disable the command line prompt. I personally find it annoying when I don't need it. img04

You can minimize or close Simba for now.

If you check your Simba folder now you will see it has a bunch of new stuff there: img05

In there you will find 2 important folders: Includes and Scripts.

The Includes folders is where you will put the Includes (well duh...).

An include is a sort of framework, a collection of common functions and procedures so scripts don't have to contain everything. Examples of includes are SRL and my WaspLib. You might not need to use this folder though since Simba has a tool to setup things automatically for us.

The Scripts folder is where you will put the scripts you download or create.

Now we are going to install SRL-T and WaspLib. You have 3 ways of installing includes, manual, automatically through Simba or using git.

To manually install a Include, simply download it's zip file from github, and unzip it in:

C:\Simba\Includes\

Unzip it, change it's name to whatever is required, for example if your unzipped folder is named "SRL-T-master", rename it to "SRL-T" and place it in Includes.

Using git is similar to the manual install, but with git. If you are using it I'm going to assume you don't need instructions.

For the automatic install which I recommend for most people, open up Simba and click on the package 📦️ icon.

img06

In the window that opens up, click the plus icon in the top left corner.

img07

Paste the link of the include you want to install...

img08

Click Ok and then click Install

If you get prompted with a overwriting warning click Yes.

Once that is done, you can install WaspLib the same way.


Press the plus icon, paste the link above, click Ok and click Install.

You can close the package manager now.

Now we are going to test if everything was setup correctly.

Type this code into Simba:

{$I SRL-T/osr.simba}
{$I WaspLib/osr.simba}

Open your Old School RuneScape Client and let it load up to the Login Screen.

If you are on Windows, I strongly recommend you use the Official OSRS Client (not the new steam one).

RuneLite is not supported!

Once that's done, click and drag the green crosshair on Simba to your RuneScape Client.


You will see the windows you drag the crosshair through being highlighted, once the RuneScape client is highlighted release the mouse. Keep in mind you should only select the client and nothing of the border.

In this case this first example is wrong:


This one is right:


Doing this tells Simba that will be it's target, because in reality you can use Simba for other things that are not RuneScape.

Once you set your client as your target, click the green arrow. That's the Play button for all scripts.


The script will run and if everything is working properly, the output on your debugger should be something similar to this:


The key words to know everything is properly installed are:

Successfully compiled

and

Successfully executed

If your output looks different or displays an error, feel free to check the the common errors page or join the discord server and ask around there!

That is it. You have successfully Setup Simba, SRL and WaspLib.

Now you can either make your own scripts, or put other people scripts in your Scripts folder.

I also recommend you to use fixed mode in osrs though it's not necessarily required.

Have fun Botting!
