## [Vysor Pro Update](https://www.youtube.com/watch?v=_7Os7JTb0So)
* Search `uglify.js` from `C:\Users\amran\AppData\Local\Google\Chrome\User Data\Default` directory and backup existing one
* Search following string in `uglify.js` file
```sh
if(!r)return console.log("No Clockwork license found in cache.")
```
* Delete the string, save file and restart `vysor`

## [Stop Vysor Update](https://stackoverflow.com/questions/27657617/how-to-disable-google-chrome-extension-autoupdate/27657703#27657703)
* Update Url Change by
```sh
"update_url": "https://clients2.google.com/service/update2/crx"
```
* `https://localhost/`
