#Introduction:
This plugin underlays the hexadecimal, rgb or named CSS color codes with their real color.
The foreground color is selected oppositely.

#Screenshot
![shot](http://i.imgur.com/HgGWH.png)

# Installation #

### With Package Control ###

If you have the [Package Control][package_control] package installed, you can install LiveCSS from Sublime Text. Open the Command Palette and select "Package Control: Install Package", then search for Live CSS and you're done!

### Without Package Control ###

Go to your Sublime Text 2 Packages directory and clone the repository using the command below:

    git clone https://github.com/a-sk/livecss.git LiveCSS

Don't forget to keep fresh.


#Documentation
I tried to make code as readable as I can and I will keep on improving documentation quality.
Nice html documentation is available [here][1]

#Features:
- Live on-the-fly colorization
- Or using ST commands
- Any file format support
- Local/global settings

#Settings:
Options available:
    - colorized_formats: list of file scopes or file extensions
    - autocolorization boolean, toggle colorize on file modification
 Example:
 
    {
        "colorized_formats": ["source.css", "source.css.less", "source.sass", "xml", "json"],
        "autocolorization": true
    }
    
Path to settings file - `os.path.join(sublime.packages_path(), 'User', 'LiveCSS.sublime-settings')`

#Plans:
- Colorizing only selected regions
- Write better code documentation
- Better background selection based on current theme's background
- Improve code quality

#Limitations:
Still in beta, may contains bugs.

[1]:http://livecss.readthedocs.org/en/latest/index.html
[package_control]: http://wbond.net/sublime_packages/package_control
