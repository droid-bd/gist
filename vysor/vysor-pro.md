## [Vysor Pro Update](https://www.youtube.com/watch?v=_7Os7JTb0So)
* Search `uglify.js` from `C:\Users\amran\AppData\Local\Google\Chrome\User Data\Default` directory and backup existing one
* Search following string in `uglify.js` file
```sh
if(!r)return console.log("No Clockwork license found in cache.")
```
* Delete the string, save file and restart `vysor`
