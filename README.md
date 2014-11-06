
## vue-ui-core
This is an easy and quick way to build just the CSS 'components' of Semantic-UI.
It exists primarily to be used with [vue-ui](https://github.com/agonbina/vue-ui)

The components exposed are the following:
```
"components": [
       "reset",
       "site",
       "button",
       "divider",
       "header",
       "icon",
       "image",
       "input",
       "label",
       "list",
       "loader",
       "rail",
       "reveal",
       "segment",
       "step",
       "breadcrumb",
       "form",
       "grid",
       "menu",
       "message",
       "table",
       "card",
       "comment",
       "feed",
       "item",
       "statistic"
     ]
```

## Setup to customize Semantic-UI

1. clone Semantic-UI in this directory
```
git clone https://github.com/Semantic-Org/Semantic-UI.git -b 1.0 semantic-ui
```
2. Copy the ```semantic.json``` config file to ```semantic-ui```
3. Copy ```theme.config``` into ```semantic-ui/src```
4. ```cd``` into ```semantic-ui``` and do an ```npm install```
5. Run ```mv src/_site src/site```
6. Edit Semantic-UI how you normally would to customize it (ex. change themes, variables, overrides)
7. Run ```gulp build```