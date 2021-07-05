# egstylus

This is a set of ~~two~~ four styles for the EG CMS that change its appearance in terms of colour palette, layout and font.

1. Dark mode sensitive with layout and font changes
2. Dark mode with layout and font changes
3. Light mode with layout and font changes
4. Dark mode only (no layout or font changes)

Everything is written in CSS and can be tweaked to your liking with a bit of experimenting (eg you can write in the name of a font of your choice, change the font size and so on). 

The styles are applied using Stylus, an extension supported by most modern browsers.

**Dark mode only**

![Dark mode only screenshot](https://i.imgur.com/i9GJyrq.gif)

**Fancy dark mode**

![Fancy dark mode screenshot](https://i.imgur.com/tLjux4U.gif)

## Tutorial

* Install Stylus for [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), [Firefox](https://addons.mozilla.org/en-GB/firefox/addon/styl-us/) or [Opera](https://addons.opera.com/extensions/details/stylus/). 
* Open and save [this .json file to your desktop](https://raw.githubusercontent.com/silentdragoon/egstylus/main/egcms-styles.json)
* Open Stylus by clicking on the S icon in the top right of your toolbar or extensions list

![Stylus icon](https://i.imgur.com/KxO5GRu.gif)

* Click **Manage** and a screen will appear
* Under the **Backup** section on the left select Import

![Stylus manage screen](https://i.imgur.com/ss4hioj.gif)

* Select the .json file you downloaded earlier
* It should say "Finished importing styles" and "4 added"
* Tick your preferred style to enable it, or untick it to disable it. As well as doing this on the **Manage** screen, you can also do this on the EG CMS itself by clicking the Stylus icon (in the upper right of the screen or in the extensions list for Chrome users).
* To have the default Gibson font work, you'll need to install it on your PC using Adobe Creative Cloud. Open the Creative Cloud app, click the *f* icon in the upper right corner of the screen. Then click on "Browse More Fonts", which opens your web browser. Sign in with your Reedpop account if needed. Search for Gibson in the search box at the top of the screen. Click on the search result, then click on the toggle switch in the upper right to "activate 32 Gibson fonts". This will download the font to your computer, and after a minute or two you should be able to close and open your browser (or restart your PC) to see the font in use in the EG CMS with the Layout + Font + Dark mode version of the theme. See the instructions below if you fancy a different font.

![Stylus disable and enable](https://i.imgur.com/mAe9oPz.png)

# Making changes to the styles

Click the S Stylus icon while you're in the CMS editor, then click the little pencil near the theme you have enabled. This will show you a long list of CSS. From here, you can make changes by changing the CSS directly. For example, if you wanted to change the font, just type in a new font name where it says:

    font-family: "Gibson", "Work Sans";
  
So if we wanted our editor font to be Georgia, we'd just change it to read:

    font-family: "Georgia", "Gibson", "Work Sans";

Similarly, if you want to change the font size or line height, just type in your own values. You can't go too far wrong here, and if you delete the lines completely, it'll revert to the site's default theming for that item. If you feel you've screwed up, just delete the styles (Stylus > Manage > select the 'X' next to the theme name) and import the .json file you downloaded again.

If anything doesn't work, or you'd like to make changes to the style but you're not quite sure how, hit me up - happy to help.
