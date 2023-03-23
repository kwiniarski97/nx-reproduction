# Problem with local executors and swc

If you have swc installed it's going to break. If you uninstall it and remove `node_modules` so that's it's really removed. It's gonna fallback to ts-node and it will compile just fine.

TO BREAK RUN 
```shell
nx run nx:execute
```
