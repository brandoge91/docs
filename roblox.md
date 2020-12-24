# Setting Roblox Integrations

> We know providing us your bots .ROBLOSECURITY cookie can be a little scary, but speaking for the developer, we hash the cookies incredibly well so that way we cannot get access to them.

Alright, so now we're going to set up a Roblox account and group so you can change ranks, and shout things directly from your Discord Server!

First, you have to create a new account for the bot to shout/rank from. Let's do that now.

Step 1: Go into an incognito tab of whatever browser you use. (Right click on the icon on the bottom taskbar, and click 'open incognito window')

*You must be in an incognito window, else the cookie will refresh and it will not work*

Step 2: Navigate to [Roblox](https://www.roblox.com/signup), and create an account with the username and password you want the bot to have.

Step 3: Join the group you want the bot to rank from, and on your main account, rank the account a rank that can rank and shout.

Step 4: Right click, click inspect, and find the tabs on the inspect element tab, and in those tabs, click on 'application'.

*See [this](https://imgur.com/a/kVsTy4r) image.*

Once in application, find the tab that says .ROBLOSECURITY, double click it, copy it, and paste it in a text editor or a notepad, because we will need it later.

*See [this](https://imgur.com/a/ijQ6iEL) image.*

Alright, now that you have you cookie, now it's time to get your group ID.

First, go to your group on Roblox, and find the URL. The numbers in the URL are the group ID.

*Example: In https://www.roblox.com/groups/8555157/Stratus#!/, 8555157 is the group ID.*

Once you have that group ID, write it down under the cookie in your notepad.

Next, you're going to go back to Discord, and start setting up stuff on Stratus's end.

First, set your group ID. To do that run:

`!setgroup <group id here>`

*Remember to replace ! with your prefix!*

Next, set the cookie using:

`!setcookie <full cookie here>`

Then:

`!refreshlogin`

To ensure you're logged in.



Great! You're almost done!

Lastly, create a role in your Discord server called **Bot Master**, and the people with this role can promote/demote/shout, so be careful who you give it to!

Wow! You set up Stratus for ROBLOX Integration all by yourself! If you encounter any errors, please feel free to report them in our [support server](https://join.fused/fans).

> Next: [Setting up Sessions](/sessions)


