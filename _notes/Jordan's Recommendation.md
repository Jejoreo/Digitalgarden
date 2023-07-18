---
tag: Info
project: Information Sharing
profileName: jejoreo02
postId: '14'
categories:
  - 1
---
## Intro
So, I did come up with several thing after 1 day of research and compiling (this time, my info-processing mind is a little bit quicker since I position myself as an office user trying to do my work). So here's some of the feature that (I think) would be useful in office usage best starting from what I felt the most relevant to the least (My feel/intuition could be wrong though):

## PDF Annotator
This one is done by installing `Annotator Plugin`. This plugin is able to do several things (adding ascii text, latex, highlighting keywords, etc.). The prerequisite of using this one is the `dataview` plugin (which I had explained in the previously). Here's how it looks:

![700](https://i.imgur.com/xyQakG3.png)

```ad-info
title: Tips
In order to mark the pdf/epub, make a seperate .mkdown file to fill in the dataview meta tag. This should be done since the plugin would store the editted stuff in a embedded .json file. Ex:
>%%
>```annotation-json
>{"created":"2023-07-18T13:38:12.562Z","text":"This is aweseome","updated":"2023-07-18T13:38:12.562Z","document":{"title":"mk:@MSITStore:C:\\Program%20Files\\Computers%20and%20Structures\\S","link":[{"href":"urn:x-pdf:c32b986500da37954351e35830574a80"}],"documentFingerprint":"c32b986500da37954351e35830574a80"},"uri":"urn:x-pdf:c32b986500da37954351e35830574a80","target":[{"source":"urn:x-pdf:c32b986500da37954351e35830574a80","selector":[{"type":"TextPositionSelector","start":640,"end":650},{"type":"TextQuoteSelector","exact":"Windows XP","prefix":"tems: Windows 2000, Windows NT, ","suffix":"  The SAP name has been synonymo"}]}]}
>```
>%%
>*%%PREFIX%%tems: Windows 2000, Windows NT,%%HIGHLIGHT%% ==Windows XP== %%POSTFIX%%The SAP name has been synonymo*
>%%LINK%%[[#^6u34vozjfan|show annotation]]
>%%COMMENT%%
>This is aweseome
>%%TAGS%%
>
^6u34vozjfan
```

The edited .json stuff could be found once the view is reverted back to `.mkdown`. (This is still a temporary solution since obsidian is developing its own pdf editor/viewer. But I thought It would be useful for most daily usage. Hence this recommendation is made.).

## Diagrams
I have noticed that diagram is used extensively in the line of works. So, I plug in the community forum and I found the `Diagram` plugin which itself is a sweet way of extending both `obsidian` & `excalidraw` (the plugins could be used in either way).  The diagram could be accessed directly such as this one:

![400](https://i.imgur.com/Fd4IMeK.png)

or by loading it into the `excalidraw` file, it would open up a new tab it the resulting image would be automatically loaded to the employed `excalidraw` file. 

| Diagram Canvas (SVG)                    | Excalidraw |
| --------------------------------------- | ---------- |
| ![200](https://i.imgur.com/lMAY9eH.png) |    ![](https://i.imgur.com/B3kSLNP.png)

```ad-info
title: Tips
I recommend the later since I observed that many office users in the community prefer making several custom objects which are used in the resulting excalidraw object.
```

## ❗List Point Issue 
As I browsed through the community's forum discussion. There is (*currently*) no viable alternatives to (***safely***) insert a list or some other type of nested stuffs. This is due to the design of the plugins, which would enable a formulaic type of work. The additional functionality could be seen by clicking `ctrl + shift + d`, which would pop up several commands (including a <u>function</u>). Here's how one would use the advance table functionality:

| Name           | Presense | Grade |
| -------------- |:--------:|:-----:|
| Jevon Jordan   |    1     | 80.2  |
| Tanjirou       |    1     | 90.5  |
| Gojo Satoru    |    2     | 89.2  |
| Ucok           |    2     | 80.4  |
| **Add & Mean** |    6     | 85.07 |
<!-- TBLFM: @>$3=mean(@2$3..@5$3);%.2f -->
<!-- TBLFM: @>$2=sum(@I..@-1) -->

This would remind one of excel-like stuff. That is in fact true and there's an awesome plugin called `Excel to Markdown`, that could paste the table to a markdown based table, which could then be operated in obsidian. The most viable way (the way I see it is to either make and paste the excel or just use loom (more on that later))

## Emoji 👍
I love using Emoji in my notes since it helps me refresh my brain after reading lines and lines of codes 😌. In fact, I have made it clear by assigning a special shortcut instead of the regular `ctrl + p`. As usual, this is a plugin that enables one to insert various emoji after allowing the option (much like the `imgur` ones but the only action needed is toggling the twitter something mark 😄). This is the pane of emoji which could be seen after installation:
![250](https://i.imgur.com/7bk9ZOr.png)


## Button
This is also a plugin (`button`). I used to use this one before the attachment feature kind of thing came along (which saved me a lot of time with a drawback in customization). This is still useable in some cases and I could see it being use in some office cases (I also did some stuff to automate my test and a small amount of pseudocode is needed to fully utilize this one). 

```ad-bug
There's some bug when certain action is perform, but it's safe for regular office usage. Here's an example containing link to obsidian forum:
```

```button
name Obsidian Forum
type link
action https://forum.obsidian.md/
```
^button-forum

## cMenu
This one has not been update for 2 years, but it is one of the best tools for office usage (I seldom use this one since I rarely do office works unless my mom told me to 😩). This one's also a plugin (`cMenu`, and the way it works is that it enables one to put a **floating** menu tool, which could contain several most used commands (**Bold**, *Italic*, ~~Slash~~, <u>Underline</u>, <sub>Subscript</sub>, <sup>Superscript</sup>) is present by default and several other commands such as embedded drawing, etc. could also be added.  Here's how it looks:

![400](https://i.imgur.com/x7LLvwD.png)

## Markdown Formatting Assistant
This one is another plugin (the title says it all). I use this plugins to quickly generate a html tag but this could also be used in office works/environments. Slight warning though, it has not been update for almost a year and the owner has decided not to maintain this wonderful plugin (😩). Basically, it complies the markdown command to a UI-Based Button (fonting, ~~tables~~, html tag, latex, greek letters, colors, and callouts). Here's the preview:
![250](https://i.imgur.com/lQShG8U.png)
Upon installation, there would be a markdown tool right beside the left panel and clicking would pop up the window. Once there, just click the ones required and voila. 


## Loom
So this is basically a rising/trending item which I have not fully used. I even don't know whether this would qualify as an office tool 😌. To keep it short, It's basically an excel-like extension which several data could be made and modified. Simple commands such as median, mean, average, min, max could be utilized and here's the demo:

![](https://i.imgur.com/ioQkBDK.png)
The resulting loom could then be embedded to another `.mkdown` by either exporting or linking the `.mkdown` (much like excalidraw).

![](https://i.imgur.com/tcXdsff.png)

Since it is still in active development, I am expecting more prominent features (and I am really optimistic about it since the last update was about a week ago).


## Obsidian Enhancing Export
I forgot to ask in the latest meeting whether the `pandoc` being stated was the standalone version or another obsidian plugin with a similar name. The standalone one would have cause no qualms in changing one format to another. Therefor, I would like to deduce that the `pandoc` mentioned is the obsidian's plugin. To use the better one (i.e the Obsidian Enhancing Export) one should first installed the standalone `pandoc`: [Pandoc - Installing pandoc](https://pandoc.org/installing.html) 

After installing `pandoc`, the next step is to add either the `pandoc`.exe to the computer's environmental variable or locate the .exe and paste the location on the plugin's setting. Once done, hit `ctrl + p` and choose the **enhance export**. There's many version that could be used, including the previously discussed html, such as this one:
![](https://i.imgur.com/Mp1jrCI.png)

