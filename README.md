# Try Out Development Containers: Node.js
## Add a dev container configuration

Access the Visual Studio Code Command Palette (Shift+Command+P / Ctrl+Shift+P), then start typing "add dev". Click Codespaces: Add Dev Container Configuration Files.

![image](https://github.com/vipulddalal/codespace_nodejs/assets/98317422/c088bd95-2583-4e42-ac47-9fb665e23972)


Click Create a new configuration.

In this example, the template repository from which you created the codespace already contains a dev container configuration, so a message is displayed telling you that the configuration file already exists. We're going to overwrite the existing configuration file, so click Continue.

Click Show All Definitions.

![image](https://github.com/vipulddalal/codespace_nodejs/assets/98317422/22d5dbe7-0f32-4138-9d93-433c50ba311a)


Type node and click Node.js & JavaScript. Other options are available if your project uses particular tools. For example, Node and MongoDB.

![image](https://github.com/vipulddalal/codespace_nodejs/assets/98317422/796529fe-3402-4abb-b252-833677ed1710)


Choose the version of Node.js you want to use for your project. In this case, select the version marked "(default)."

![image](https://github.com/vipulddalal/codespace_nodejs/assets/98317422/9fd2021f-adc2-444b-84c6-7c63590198ff)


A list of additional features is displayed. We'll install JSHint, a code quality tool for detecting errors in JavaScript code. To install this tool, type js, select JSHint (via npm), then click OK.

![image](https://github.com/vipulddalal/codespace_nodejs/assets/98317422/3abdce14-3e4b-4d5c-a9a7-f86be3771f42)


A message is displayed telling you that the dev container configuration file already exists. Click Overwrite.

A devcontainer.json file is created and is opened in the editor.


