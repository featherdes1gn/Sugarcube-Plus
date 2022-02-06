# SugarCube+ 2.0
Yes. I'm already writing it. SugarCube+ was written lazily. I barely wrote any documentation, and I didn't add as much content as I originally wanted. So, I have begun to start writing 2.0 Obviously it will retain the same design elements, but with a little more polish. No release date yet. Probably within the next few days.

# SugarCube+
I designed SC+ in about a day to give [SugarCube](https://www.motoslave.net/sugarcube/2/) a more modern UI. I got sick of playing around with CSS everytime I wanted to open Twine, so I decided to write my own CSS framework.

SC+ contains some custom classes to help speedup the design process a little bit. They're not powerful classes, but they get the job done. Boxes, colored buttons, smoother animations/transitions, and a more modern feel are basically what SC+ has to offer. I am underselling it, but.. it is what it is.

You can, of course, pick and choose what you want. The CSS sheet has been commented on, in most places, in order to help you understand what each class is actually doing, and why I edited it the way I did.

# Classes
So, yeah. SC+ contains a few workflow classes that I think will make initial deployment a bit easier. Like I already mentioned above, colored buttons, for example, are something that SC+ comes default with, and they're fairly intuitive to use.

```
<span class="btn-red"><<button "Button text">><</button>></span>
```

will provide you with a red button. `btn-red`, `btn-blue`, `btn-green`, `btn-yellow`, `btn-orange`, `btn-purple`, `btn-bronze`, `btn-silver`, and `btn-bgold` are the new button color classes. Oh, yeah, those colors can be applied to anything, by the way.

```
<span class="textRed">Some red text goes here.</span>
```
will change the text to red. 

I've added some other box classes, to make divs/spans look nicer. Plenty of options to go around for those as well. Extending SC+ is fairly easy, even if you're unfamiliar with CSS. The stylesheet is marked pretty well, and all one would have to do is read the /* comments */, copy, paste, and adjust to taste.

# What else?
I also reformed the `{{{ }}}` codeblock. When I'm writing a code block, I want it to actually appear as a code block.

There's quite a few new animations. I particularly enjoy the new UI bar toggle button animation. Pretty much everything I could find is rounded now.

There's also a few toggleable options, for those who want to (for example) disable the UI bar, but retain full viewport width. I prefer the UI bar to the side, so you should keep in mind that SC+ *was* designed with the UI bar. Like I said, there are options to toggle it on and off, but I haven't tested it much with the UI bar off.

Oh, speaking of viewport, I also increased the viewport in general. Maybe there was a good reason why it was scrunched up, but I like it better with a wider view. 

# How do
Eventually I'll write up some documentation, but for now you can just play around on the [demo site](https://vxssi.github.io/Sugarcube-Plus/) to get a feel of how everything looks and operates. There are two options, `sugarcubeplus.css` and `sugarcubeplus-min.css`. They're both the same, they're just formatted differently. If you're not familiar with CSS, you should use the `sugarcubeplus.css` file, since it's actually, you know, readable.

P.S, thanks to TwineLabs for making this [dialog macro](https://twinelab.net/custom-macros-for-sugarcube-2/demo/). I didn't wind up using it here (yet), but I accidentially left the JS snippet in the demo site. Don't want to be a dirty pirate.
