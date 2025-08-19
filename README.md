# Introduction

In this class teacher will talk about the scripts listed in the node 'scripts' of package.json.

You can run a package.json script directly in VSCode using the play button related to a script showed in "NPM SCRIPTS" panel.

![running a package.json script directly in VSCode](images/running-a-npm-script-directly-in-vscode.png)

Here you can see the "scripts" node of package.json. You can see here if you need to use the Node.JS interpreter, you have to include it ('node' before the script name, considering that 'node' can be find through the PATH):

![package.json scripts](images/example-of-package-json-script.png)

If you have to do more than 1 task in a script, you can concatenate the comands with "&&" (as in "myScript" line in the previous image) or make a script that do ths two things.

Here you can see some common script names. Note the use of double column in some script names:

![common scripts](images/common-scripts.png)

Teacher explained that there is not an universal rule of naming conventions. But he suggested:

- to group the scripts by context using prefixes like "test:" or "start:";
- to separe the context by the name of the specific action by ":", but he passed an example of React that uses the charaacter "-" as separator (seemed less clear).

Ilustrating the previous text:

![naming conventions of scripts](images/naming-conventions-of-scripts.png)

Another tip of the teacher was to use clear name and standards, making our work clear.


# Several links

[Repository related to this module](https://github.com/digitalinnovationone/formacao-nodejs/tree/main/08-npm-scripts)

[Documentation related to NPM scrips](https://docs.npmjs.com/cli/v10/using-npm/scripts)

[Facebook (React library) scripts](https://github.com/facebook/react/blob/main/package.json)
