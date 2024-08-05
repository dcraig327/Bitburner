# Bitburner

___

### setup vscode

* install vscode extension
* add the api key
* enable the api server in the game
* enable autostart api server in the game
* download definitions & setup:
```
echo -e ".vscode/\n.gitignore" >> .gitignore

mkdir root

curl https://raw.githubusercontent.com/bitburner-official/bitburner-src/dev/src/ScriptEditor/NetscriptDefinitions.d.ts -o root/index.d.ts
```
* add vscode workspace settings:
```
"bitburner.scriptRoot": "./root/",
"bitburner.fileWatcher.enable": true,
"bitburner.showFileWatcherEnabledNotification": true,
"bitburner.showPushSuccessNotification": true
```
