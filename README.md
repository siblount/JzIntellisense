# JzIntellisense

JzIntellisense is a JS file to assist developers with their DzScripts by utilizing powerful IDE's (such as Visual Studio/Code) autocompletion functionality; makeshift code compeletion.

JzIntellisense contents is ported directly from the [DAZ Documentation website] and inherits the [Attribution 3.0 Unported (CC BY 3.0) License]
# Me
I DO NOT WORK FOR DAZ PRODUCTIONS AND THIS SCRIPT WAS NOT SUPPORTED BY OR ENDORSED BY ANYONE AT DAZ PRODUCTIONS INC.

If I made your life wonderful, if you're feeling generious enough to donate to help me out... 😏👉: 🌟https://www.buymeacoffee.com/therealsoll🌟
## Latest Update ##
- Signals have been added as functions. A note is added to remind you that the signal is not an actual function.
- All enums have been added.
# ⚠ Heads up ⚠ 
##### The current version of JzIntellisense is in its early stages. It is still a WIP.
- The current version does not include signals as of yet.
- The current version does not include `String`, `Number`, `Boolean`, `Object`, `Date`, `Function`, and `JSON`, and others later explained.
- The current version has a few enums missing.
- JzIntellisense comes with billions of errors. This is perfectly fine. If it bothers you, you may need to disable JS vailidation errors.

# How to use 
###### ⚠  The following instructions is for Visual Studio Code  ⚠
1.  Download the `JzIntellisense.js` script and import it into your workspace.
2.  If you haven't made a `.dsa` DzScript (ASCII) script yet, go ahead and do so.
3.  After creating a `.dsa ` file, go to the bottom-right of the screen where you see the current language. At default, you will see `Text File` . Click on it and a Language Dialog will pop up.
4.  Select "Configure File Association for `.dsa" and then select JavaScript as your mode.

If you open a folder/workspace, make sure that the file is in your working directory/workspace. 

If you have created a new file (or opened a file) rather than a folder or workspace, you need to import the script using syntax like: `import * as _ from "./JzIntellisense.js"`
##### Optional
###### Disable JavaScript validation errors.
5.  Go to File -> Preferences -> Settings. In the User tab (or Workspace) select TypeScript (TypeScript is the interpreter for JavaScript & TypeScript for VS Code). Search for `JavaScript > Validate: Enable` and disable JavaScript validation.


## Missing Classes
All missing classes are EMCAScript classes which can not be added to this (or atleast I think so) 🤷‍♂️
- `Array`
- `Boolean`
- `Date`
- `Error`
- `EvalError`
- `Function`
- `JSON`
- `Math`
- `NativeError`
- `Number`
- `URIError`
- All classes not documented such as DzShape (`shape_dz`).

There may be other things missing. If you found something thats missing and it's not mentioned in this post, please post a new issue describing what is missing and where it can be found.
## Planned Updates
- Add missing documentation for properties.
- Update JSDOC for classes, constructors, and methods.
- Arrays will no longer return "any[]" (this has to be done manually afaik for 333 instances ._.)


   [Daz Documentation website]: <http://docs.daz3d.com/doku.php/public/software/dazstudio/4/referenceguide/scripting/start>
   [Attribution 3.0 Unported (CC BY 3.0) License]: <https://creativecommons.org/licenses/by/3.0/>
