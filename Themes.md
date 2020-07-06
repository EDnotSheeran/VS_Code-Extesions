## Themes

### One Monokai
#### Install 
press ctl/command + shift + p to launch the command palette then run
`ext install one-monokai`
##### or
Download: [Link](https://marketplace.visualstudio.com/items?itemName=azemoh.one-monokai)
#### Screenshot
![](https://raw.githubusercontent.com/azemoh/vscode-one-monokai/master/screenshot-v0.2.0.png)

### Dracula Official
#### Install 
press ctl/command + shift + p to launch the command palette then run
`ext install dracula-theme.theme-dracula`
##### or
Download: [Link](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)
#### Screenshot
![](https://raw.githubusercontent.com/dracula/visual-studio-code/master/screenshot.png)

### Material Icon Theme
#### Install 
press ctl/command + shift + p to launch the command palette then run
`ext install PKief.material-icon-theme`
##### or
Download: [Link](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
#### Screenshot
##### File icons
![](https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/master/images/fileIcons.png)
##### File icons
![](https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/master/images/folderIcons.png)
##### Customize folder color
You can change the color of the default folder icon using the command palette:
![](https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/master/images/set-folder-color.gif)
or via user settings:
`"material-icon-theme.folders.color": "#ef5350",`
##### Folder themes
You can change the design of the folder icons using the command palette:
`https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/master/images/set-folder-theme.gif`
or via user settings:
`"material-icon-theme.folders.theme": "specific"`
##### Custom icon opacity
You can set a custom opacity for the icons:

`"material-icon-theme.opacity": 0.5`
Custom icon saturation
If colors do not make you happy you can change the icons to have less saturation making them look grayish or completely grayscale by setting saturation to 0:

`"material-icon-theme.saturation": 0.5`
Custom icon associations
You can customize the icon associations directly in the user settings.

##### File associations
With the *.[extension] pattern you can define custom file icon associations. For example you could define an icon for *.sample and every file that ends with .sample will have the defined icon. Use **.[extension] with two asterisks to apply the file association also for the filenames ending with that file extension.

If there's no leading * it will be automatically configured as filename and not as file extension.

`"material-icon-theme.files.associations": {
    "*.ts": "typescript",
    "fileName.ts": "angular"
}`
##### Folder associations
The following configuration can customize the folder icons. It is also possible to overwrite existing associations and create nice combinations. For example you could change the folder theme to "classic" and define icons only for the folder names you like.

`"material-icon-theme.folders.associations": {
    "customFolderName": "src",
    "sample": "dist"
}`
##### Language associations
With the following configuration you can customize the language icons. It is also possible to overwrite existing associations.

`"material-icon-theme.languages.associations": {
    "languageId": "iconName",
    "json": "json"
}`
Available language ids:

https://code.visualstudio.com/docs/languages/identifiers#_known-language-identifiers

You can see the available icon names in the overview above.
