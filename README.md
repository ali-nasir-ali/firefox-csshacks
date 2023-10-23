# firefox-csshacks

https://github.com/MrOtherGuy/firefox-csshacks


https://mrotherguy.github.io/firefox-csshacks/?file=navbar_tabs_oneliner.css

The above links have CSS hacks for Firefox that will make it more useful and better looking.

the below youtube video that can be followed for a quick recap on how to use it or what it will look like once done
https://www.youtube.com/watch?v=h9NK75NVyqc
https://www.youtube.com/watch?v=BmchttxZ85w


Other Firefox CSS GitHub sources

https://github.com/Aris-t2/CustomCSSforFx/blob/master/current/userChrome.css
https://github.com/stonecrusher/simpleMenuWizard/blob/master/simpleMenuWizard/blank-context.css

great Reddit post explaining how to edit right-click context menu

https://www.reddit.com/r/firefox/comments/7dvtw0/guide_how_to_edit_your_context_menu/?rdt=48923

---------------------------------------------------------------

## Instructions

To **set up CSS for firefox** you need to

1. Find your **profile folder** (profile names are different for everyone):  
   Address bar > Enter `about:support` > Click `Open Folder` (second one, not the "Update Folder").

2. Move `userChrome.css` into `[...]\profile folder\chrome\` directory.  
   If `chrome` folder doesn't exist, create it.  
   If `userChrome.css` already exists, do *not* overwrite and proceed [here](https://github.com/stonecrusher/simpleMenuWizard#using-simplemenuwizard-together-with-other-custom-modifications).

3. Open `userChrome.css` with a text-editor for a general overview and some options.

4. Load `about:config` into the address bar. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and make sure the value is `true`.

5. Restart Firefox to make changes work.


