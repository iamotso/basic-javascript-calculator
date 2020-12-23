# basic-calculator-vuejs

View Basic Calculator at (https://iamotso.github.io/basicCalculatorJS/)

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).

### My Vue Notes

    Create Vue app: "vue create 'app-name'
    Start: 'npm run serve'
    v-model is for two-way binding
    v-on
    v-if
    v-else-if
    v-else
    v-model is for two-way binding
    {{ "Can call any functions or use data from below here" }}
    mounted is on load
    :class="Javascript logic here"

### Deploying

    checkout to gh-pages
    git merge master
    npm run build
    git add dist && git commit -m "Initial dist subtree commit"
    git subtree push --prefix dist origin gh-pages
