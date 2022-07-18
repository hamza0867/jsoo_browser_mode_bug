# jsoo_browser_mode_bug

This is a reproduction repo for the JSOO bug mention [here](https://github.com/ocsigen/js_of_ocaml/issues/1293).

To reproduce the bug you will need to install: 
1. [nodejs](https://nodejs.org/en/) to get npm.
2. [esy](https://esy.sh/en/)

Once those tools installed run the following command inside the cloned folder:
```sh
esy install
esy b
```
And then investigate the output in `_build/default/src/Main.bc.js`
