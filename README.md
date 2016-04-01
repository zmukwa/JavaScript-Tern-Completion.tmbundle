# JavaScript Tern Completion.tmbundle

Smart Javascript auto-complete for Textmate 2 using [TernJS](http://ternjs.net).

### Usage
1. Download and install [JavaScript.Tern.Completion.tmbundle-0.2.zip](https://github.com/fab1an/JavaScript-Tern-Completion.tmbundle/releases/download/release%2F0.2/JavaScript.Tern.Completion.tmbundle-0.2.zip)
2. Create `.tern-project` file in your project-directory (more [info](http://ternjs.net/doc/manual.html))

   ```javascript
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

### Dependencies
`node` must be installed and on your path.

### Known issues
* Creates a named pipe called `pipe` in the project-directory. Will be fixed.
* Generally rather brittle

### ToDo
* Use more of tern's [functionality](http://ternjs.net/doc/manual.html) to display function-parameters, symbols, jump to variables and so on.
