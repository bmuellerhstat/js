# js

## Instructions
1. In your terminal, do `git clone git@github.com:hstatsep/js.git` to clone this repository
2. In your terminal, do `cd js` to get into the `js` folder
3. In your terminal, do `rm -rf .git` to "turn off" git in this folder.

## Files/Folders
* `classwork` is a folder for organizing classwork, assignments, etc.
* `projects` is a folder for your when you want to make something large
* `sandbox` is a folder for when you want to try something small
* `templateFile.html` is a standalone template file to duplicate in order to practice small concepts
  * to duplicate, use either:
    * `cp templateFile.html sandbox/newFileName.html`
    * `cp templateFile.html classwork/newFileName.html`
* `templateFolder` is a template folder to duplicate in order to make large projects
  * to duplicate, use `cp -r templateFolder projects/newProjectName`

## Console
* In order to see errors and results of `console.log()`, you can do one of the following:
  * keyboard shortcut:
    * Mac: <kbd>Command</kbd> + <kbd>Option</kbd> + J
    * Windows/Chromebook: <kbd>Control</kbd> + <kbd>Shift</kbd> + J
  * right-click > inspect > switch to **console** tab
  * three-dots in the top-right corner > More tools > Developer Tools > **console** tab
* More information [here](https://developers.google.com/web/tools/chrome-devtools/console/javascript#:~:text=Press%20Command%20%2B%20Option%20%2B%20J%20(,here%20on%20this%20very%20page.)

## Git alias commands
* Copy/paste the following into the terminal.
```
echo "alias gp=\"git add ." >> ~/.bash_profile
echo "git commit -m 'update repo'" >> ~/.bash_profile
echo "git push\"" >> ~/.bash_profile

```
* If you still see the last command in your terminal, press <kbd>ENTER</kbd>
* Close the terminal and open a new one
* In the future, you can simply type `gp` to automatically add/commit/push all updated files in a repo