Steps for Sublime Text 2

1. Clone this repo.
https://github.com/rnel/subl-settings.git

2. Rename the current settings folder from 'User' to 'User-orig'. The settings folder is located here:
~/Library/Application Support/Sublime Text 2/Packages

2. Symlink the settings folder.
ln -s ~/Development/Tools/subl-settings ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User

3. Install Package Control (copy the python code from the link below and run on Sublime Text console).
https://sublime.wbond.net/installation#st2

4. Update the color scheme for GitGutter icon coloring.
  a. Copy the GitGutter color entries from this link:
    https://github.com/jisaacks/GitGutter

  b. Add the color entries color scheme plist (before </array>). Here's the path of the color scheme file:
    ~/Library/Application Support/Sublime Text 2/Packages/Color Scheme - Default/Sunburst.tmTheme
