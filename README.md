# JavaScript Tern Completion.tmbundle

Smart Javascript auto-complete for Textmate 2 using [TernJS](http://ternjs.net).

### Usage
1. Clone into `~/Library/Application Support/Avian/Pristine Copy/Bundles`
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
