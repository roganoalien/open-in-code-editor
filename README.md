## Open in Code Editor

**You need to set the `terminal` env before using the workflow. And also needs python3 to run.**

This workflow helps you to open a `folder` inside a `code editor`, inside your prefered `terminal` or in both at the same time. You need to configure some `env variables` in order for it to work:

- `default` [string] that it's default value is `ask` which will make the prompt at the end of the flow to ask you if you want to open the selected file/folder in just the `code editor` in `both` `code editor` and your `terminal`or an empty string which will make the default to open in the code editor
- `sound` [boolean] that it's default value is true. Turn it into false to prevent the sounds triggered after finishing or canceling the flow.
- `terminal` [string] that has no default and you need to add the name of the terminal you're using. E.g. `iTerm` to make iTerm app the terminal for this workflow.

#### Keywords:

- `code` opens the folder/file inside **Visual Studio Code**
- `subl` opens the folder/file inside **Sublime Text**
- `codium` opens the folder/file inside **VSCodium**
- `storm` opens the folder/file inside **PhpStorm**
- `terminal` opens the folder/file inside **your terminal**. If app name _has spaces_ then and `\` after each word. E.g. `My\ Terminal` otherwise it would not work.

#### Specifications:

There's no filter in the search of files to make it compatible with every file posible that could be opened and read the insides like svg files, json, html, css, sass, less, stylus and every programming language and none programming language file.

#### Sugestions, requests and issues

Feel free to ask for features or post issues you're having with the workflow. I'll try to fix those as fast as I can.
