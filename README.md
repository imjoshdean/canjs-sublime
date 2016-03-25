# canjs-sublime
Welcome to the CanJS [Sublime Text](http://www.sublimetext.com/) plugin.

The plugin creates a bunch of snippets to facilitate CanJS integration into 
Sublime Text.

![](https://zippy.gfycat.com/LivelyAridCommongonolek.gif)


## Installation
Currently if you wish to "install" this package you will need to go to your 
`Packages/User` folder and manually install from github:
```
git clone https://github.com/imjoshdean/canjs-sublime.git
```

## Autocomplete in HTML/Stache files
For whatever (probably very good) reason, autocompletion doesn't work in HTML 
files unless you are within a tag. There's a quick little get around to this 
that could probably be a lot more elegant, but for now...
```
{
	"auto_complete_triggers":
	[
		{
			"characters": "qazwsxedcrfvtgbyhnujmikolpQAZWSXEDCRFVTGBYHNUJMIKOLP",
			"selector": "text, source, meta, string, punctuation, constant"
		}
	]
}
```