---
layout: page
title: Format
---

There are integrated many [wonderful features](thearchive://search/›[[202005021405]]) to support you in building a self-hosted Zettelkasten. 

LaTex formating - view in preview mode.
$(C_8H_8)_n$
$\int(2xCosx-\frac{du}{dm}u)dx= 2x$

Mathjax
$\beta_{i=1}$

<!--myhost.example.com-->
`https://forum.zettelkasten.de`
`myhost.example.com`

[[201801000000]] Testing Ground
Testing Ground [[201801000000]]

# test [[201801000000]]
## test [[201801000000]]
### test [[201801000000]]

**[[s** Tigger =  
[[testing]]

(Ellwood 1987)
(Ellwood 1987)

Ellwood, Robert S. 1987. Zen in American Life and Letters. Vol. 6. Malibu: Undena Publications.

Bejan, Adrian. 2016. The Physics of Life: The Evolution of Everything. St. Martin’s Press. http://www.loc.gov/catdir/enhancements/fy1606/2015035874-b.html.
Mills, C. Wright. 1980. “On Intellectual Craftsmanship (1952).” Society 17 (2): 63–70. https://doi.org/10.1007/bf02700062.
Kagge, Erling. 2016. Silence in the Age of Noise. First American edition.

Kagge, Erling. 2016. Silence in the Age of Noise. First American edition.
1. Kagge, E. Silence in the age of noise. (2016).
Kagge, Erling. 2018. Walking: One Step at a Time. Penguin Publishing Group.

https://medium.com/@simp2973/montys-woods-9885bf0cc8ae

⌃⌥⇧⌘

The Safest Source of Energy Will Surprise You
    - evernote:///view/597091/s5/25a21521-a559-4bfe-82d6-34291661ca2a/25a21521-a559-4bfe-82d6-34291661ca2a/
3-2-1: Creative ideas, wealth, and making life a celebration
    - evernote:///view/597091/s5/46685fce-4122-441a-8e90-bf439f62d06b/46685fce-4122-441a-8e90-bf439f62d06b/


⇧⌘C from Zotero
Gilovich, T, K Savitsky, and V H Medvec. “The Illusion of Transparency: Biased Assessments of Others’ Ability to Read One’s Emotional States.” J Pers Soc Psychol 75, no. 2 (1998): 332–46. https://doi.org/10.1037//0022-3514.75.2.332.

Dickens, Rebecca. “The Zen of Stevens.” Masters Theses - http://thekeep.eiu.edu/theses/2262, Eastern Illinois University, 1990.

Dickens [[202010262046]], Rebecca. “The Zen of Stevens.” Masters Theses - http://thekeep.eiu.edu/theses/2262, Eastern Illinois University, 1990.



| Testing | testing | testing |  
| :-----: | :-----: | :-----: |  
|    1    |    2    |    3    |  
|   23    |    5    |    6    |  

Number, Link, Address
1, [[201801000000]], 1020 Bartho Lane
2, [[201901070553]], PO Box 9162

Services > md - Tables - Create from CSV

| Number |       Link       |     Address      |
| :----: | :--------------: | :--------------: |
|   1    | [[201801000000]] | 1020 Bartho Lane |
|   2    | [[201901070553]] |   PO Box 9162    |

'"**Testing**"'
[[testing](!g)](!bt)

[[202008301740]] Target Link

Auto opening of files - didn't work!
![](italss://media/03_3_Women_Walking.mp3)
[](udp:///Users/will/Dropbox/zettelkasten/media/walking.mp3)
![](rtp://07_supernova.mp3)

https://brettterpstra.com/projects/markdown-service-tools/index.html [^7]

Allows you to write footnotes inline using (*This is a footnote*)

---
Select then Right Click for "Services"

|    Date    | Measurement | % Body Fat | lbs. of Fat | Lean Mass |
| :--------: | :---------: | :--------: | :---------: | :-------: |
| 11/11/2016 |    36.75    |            |             |           |
| 11/18/2016 |    36.50    |            |             |           |
| 11/25/2016 |    36.00    |            |             |           |
| 12/2/2016  |    36.00    |    18.0    |     26.3    |   119.7   |
| 12/8/2016  |    35.75    |    17.6    |     25.7    |   120.5   |
| 12/16/2016 |    35.25    |    17.5    |     25.5    |   120.0   |
| 12/22/2016 |    35.50    |    16.0    |     23.0    |   121.1   |
| 12/29/2016 |    35.00    |    16.6    |     24.4    |   120.7   |
|  1/6/2017  |    34.75    |    16.2    |     23.4    |   121.0   |


| Date | Project                  | Done |  
| :--: | :----------------------- | :--: |  
| 5/24 | wood working project     |  ✔︎  |  
| 6/1  | Backpacking with Richard |  ◻︎  |    

---


[^7]: this is Inline Testing

---
Play a mp3 in VLC link
Have to set up Keyboard Maestro to help with this.
Conflict Palette
Struggling to maker work.
PDF
Photo ✔︎
Word
MP3
![](my-vlc:///Users/will/Dropbox/zettelkasten/media/01_As_Falls_Wichita,_So_Falls_Wichita_Falls.mp3)


![](my-preview:///Users/will/Dropbox/zettelkasten/media/Flower_Child.jpg)

![](my-vlc:///Users/will/Dropbox/zettelkasten/media/06_bliss.mp3)

![](my-PDF:///Users/will/Dropbox/zettelkasten/media/PRIOR_KNOWLEDGE_.pdf)

[[202008300710]] Target Link

Using AppleScript make an application with this text.
on replace_url_scheme(original)
	return do shell script "echo " & quoted form of original & " | sed 's/my-preview:/file:/'"
end replace_url_scheme

on open location this_URL
	set file_URL to replace_url_scheme(this_URL)
	do shell script "open -a preview " & quoted form of file_URL
end open location

Show Contents of application and in the info.plist add after the <dict>
<key>CFBundleURLTypes</key>
	<array>
		<dict>
			<key>CFBundleURLName</key>
			<string>Media Opener</string>
			<key>CFBundleURLSchemes</key>
			<array>
				<string>my-preview</string>
			</array>
		</dict>
	</array>

---
›[[202010010652]]‹
"Deconstructing the Placebo Effect and Finding the Meaning Response" (Moerman and Jonas 2002:471)

#thinking-skills

Investing starts with liquidity:[[202001121202]] You have to have liquidity to make investment decisions unless you are using other people's money (e.g. using leverage).


Outline Formating.
# test
## test
### test
