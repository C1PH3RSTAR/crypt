# crypt

These are siteskins for ao3, using them is simple.

Go to https://archiveofourown.org/skins/new?skin_type=Skin

Title it whatever you want

Copy the raw code in one of these files (If you didn't know, you can easily copy it all by clicking into the text box and pressing Ctrl+A, then Ctrl+C)

Paste it into the CSS text input section

Click submit

Congrats! You made a site skin you can use! Now scroll down to the bottom of the page and click use to use it.


Mild extra customization info, at the bottom of the CSS code, I added a section that looks like this:

#workskin,

.blurb,

.comment {

font-size: 130%;

min-width: 300px;

}

All this does is make the font size bigger because it strains my eyes otherwise.

font-size: 130%; is what does this. You can change, or remove this if you want.

min-width: 300px; is a tiny bit more complicated, but still easy to understand. It just means that this bit of code only applies if the display is at least 300 pixels wide.
This means that if you're using ao3 on something with a screen that's less than that, it won't make the font bigger, so it doesn't cause formatting issues that might make it
annoying to read. Since ao3 skins are applied for your account and not just that device, you may want to make sure this is set to something larger than your phone if you plan on 
using it for reading.


Fair warning, this is specifically made for people who have never used ao3's skins before, and I myself only just started figuring it out a few days ago. The original CSS code
is not mine, I only changed a few small things to fit my preferences. The original code can be found here: https://archiveofourown.org/works/32660914
I made this mainly for one of my friends, so if you already know all this and this seems like the most basic info possible, then good for you.
