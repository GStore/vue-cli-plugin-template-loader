# vue-cli-plugin-template-loader

A plugin for @vue/cli 3.0 to setup a vue scaffolding using [vue-template-loader](https://github.com/ktsn/vue-template-loader).

## With this plugin

When one uses this plugin in combination with TypeScript,

1.  Type safety is kept accross files
2.  When writing tests, autocompletion with most editors work
3.  Intellisense and documentation in typescript is kept
4.  Shims for .vue files are a thing of the past

## To use this plugin

```bash
npm install --global @vue/cli
vue create my-vue-app --default
cd my-vue-app
vue add template-loader
```
