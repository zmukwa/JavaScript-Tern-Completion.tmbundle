# JavaScript Tern Completion.tmbundle

Smart Javascript auto-complete for Textmate 2 using [TernJS](http://ternjs.net).

### Usage
1. Download and install [JavaScript.Tern.Completion.tmbundle-0.1.zip](https://github.com/fab1an/JavaScript-Tern-Completion.tmbundle/releases/download/release%2F0.1/JavaScript.Tern.Completion.tmbundle-0.1.zip)
2. Create `.tern-project` file in your project-directory

   ```  
{
  "libs": [
    "browser"
  ],
  "loadEagerly": [
  ],
  "plugins": {
    "node_resolve": {},
    "es_modules": {}
  }
}
   ```
3. Press ⌥␣ (Option + Space) in a `.js` file

  ![screenshot](https://github.com/fab1an/JavaScript-Tern-Completion.tmbundle/blob/master/screenshot.png)


### Known issues
Creates a file called `pipe` in the project-directory. Will be fixed.
