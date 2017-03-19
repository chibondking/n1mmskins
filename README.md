# N1MM Skins
N1MM Logger Plus Custom Color Skins

This is a collection of custom dark N1MM skins that I created after I became so
accustomed to having a black theme in Win-Test and DXLog. While the default
N1MM skins are fine for most folks, I found the bright default blue to be just
a bit too much (In my day to day job, my desktop is as dark as possible, including
my editors) when sitting at home on the weekend contesting. So, I decided to do
something about it.

Inspired by Tim, N3QE's post on the N1MM Support reflector along with a screenshot,
I used the N1MM Low Vision mode as a start. Obviously I scaled the font sizes down
from there, but if necessary I'm sure you can resize them back up to fit the
Low Vision scheme.

![WT2P BARTG RTTY SO2R layout](https://www.dropbox.com/s/tepkveb6zu5ek6h/WT2P%20BARTG%20RTTY.png?dl=0)


##Themes
Currently I have 3 themes I came up with to use:
* Black
* Dark (blue)
* Dark 2 (darker shades of blue)

##Installation
Download the zip file of the themes here. Unzip and copy each of the files to your
N1MM Logger\SkinsAndLayouts directory (usually found under My Documents\N1MM Logger +\SkinsAndLayouts)

In N1MM Logger, go to Config, then Manage Skins, Colors and Fonts.

Click on Skins and select Load Existing Skin, then Load Skin from File.

You should see the WT2P themes displayed in a box. Choose one.

N1MM should reload and the skin should be applied. If you don't have some or all of the
fonts the theme uses, you can click on Fonts and select your own.

Click on the Preview button to see what your changes would look like in the
logger program and once you're done, click Save.

**There are some known minor issues, which I'll discuss below.**

###Manage Skins, colors and Fonts Window Extra Detail

###Fonts:
**Entry Window Callsign**: Franklin Gothic, Medium, 16pt
**Medium - screen text and tables**: Arial, Regular, 12pt
**Small - most labels, Log Window data**: Franklin Gothic, Medium, 11pt
**Smaller - buttons, small labels, Bandmap Window Callsigns**: Franklin Gothic, Medium, 9pt
**Fixed - Digital Interface, Check, Telnet and Score Windows**: Inconsolata, Regular, 10pt

###Extra Settings:
Show Form Font Sizers: Unchecked (this is a matter of personal preference)
Snap Windows to Edges: Checked (again, matter of personal preference)


##Caveats / Known Issues
I've noticed a few issues with using the dark theme so far that may (or may not)
be addressed by the N1MM developers:

* Available Mults window: The Bands across the top and Mults/Qs/Total Qs on the side
sometime change back to black foreground. Closing and reopening the window fixes it.

* Bands and Modes button in the Available Mults Window: This popup still has some
foreground text in black that does not change with the scheme.

* Info Window: The rate graph text occasionally will default back to Black foreground.
Again, close and reopen the window to fix. There's also some text that appears to be
stuck in foreground black.

* Bandmap A / B (in SO2R/SO2V mode): The focused bandmap frequency background correctly
updates to the correct foreground/background color scheme. The secondary bandmap frequency
background however will change to white. I have not been able to see where to fix that.

* Entry Windows: Along the top with the Callsign, Sent/Received fields, you can see the
white outline (with my Black theme) of each of the controls. That is likely embedded
within the software controls used and as of now, cannot be changed. You can see
this prominently in the screenshots.

* Visual Dupesheet: Color schemes are not applied

* Digital Interface Windows: Many of the various button foreground text colors on
the main DI Windows will not invert colors when using a dark theme. Easily visible
in the screenshots. Also, the text entry window foreground text is also not inverted
which if you're manually typing data will make it hard to see.

##Other Resources
[N1MM Logger Plus](https://n1mm.hamdocs.com/tiki-index.php)

###N1MM Skin Community
If you have created some custom skins you would like to share, I'd be glad to include
them (with proper attribution) in this repository. You can send me an email (wt2p at arrl)
or, if you're technically inclined, fork this repo, add your skins (or make changes to/expand on mine)
and send me a Github pull request.

###Screenshots
I have uploaded screenshots of many of the current N1MM Logger windows to the screenshots
directory in this repo as well. Take a look to see how the theme(s) look on Windows 10.

73,
CJ - WT2P
