
## vue-ui-core
This is an easy way to build just the CSS 'components' of Semantic-UI.
It exists primarily to be used with [vue-ui](https://github.com/agonbina/vue-ui)

## Setup

1. clone Semantic-UI in this directory
```
git clone https://github.com/Semantic-Org/Semantic-UI.git -b 1.0 semantic-ui
```
2. Copy the ```semantic.json``` config file to ```semantic-ui```
3. Copy ```theme.config``` into ```semantic-ui/src```
4. ```cd``` into ```semantic-ui``` and do an ```npm install```
5. Run ```mv src/_site src/site```
6. Optional: Edit Semantic-UI how you normally would to customize it (ex. themes, variables, overrides)
7. Run ```gulp build```