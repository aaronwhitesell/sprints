## Honor thy build 00
Create project using the Bower and Gulp.
### Bower setup
##### Global setup: once per computer
###### Check verion of node
```shell
$ node -v
```
###### If 'command not found' then download node.js from website
###### Install Bower
```shell
$ npm install -g bower
```
##### Local setup: once per project
###### cd to/the/project/root
###### Create bower.json
```json
{
    "name": "project-name"
}
```
###### Alternatively, generate bower.json
```shell
$ bower init
```
###### Search for a package (e.g. jquery)
```shell
$ bower search jquery
```
###### Install a package (e.g. jquery)
```shell
$ bower install jquery --save
```
###### Create .bowerrc, these are your Bower settings
```json
{
    "directory": "subdir/bower_components"
}
```
##### Additional commands
###### Update packages
```shell
$ bower update
```
###### Uninstall packages (e.g. jquery)
```shell
$ bower uninstall jquery --save
```