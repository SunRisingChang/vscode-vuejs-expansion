# VSCode Vue.js Expansion

#### 包含扩展的简要说明

- **AL Code Outline** - 代码大纲
- **Auto Close Tag** - 自动添加 HTML / XML 关闭标记
- **Auto Rename Tag** - 自动重命名配对的 HTML / XML 标记
- **Bracket Pair Colorizer** - 使用颜色标识匹配括号
- **change-case** - 快速更改当前选择或当前单词的大小写
- **Chinese (Simplified) Language Pack for Visual Studio Code** - 中文（简体）语言包扩展
- **Code Spell Checker** - 一个与 camelCase 代码配合良好的基本拼写检查程序
- **CSS Peek** - 允许窥视 css ID 和类字符串作为从 html 文件到相应 CSS 的定义。允许查看和转到定义
- **ESLint** - 将 ESLint JavaScript 集成到 VS 代码中
- **GitLens** - 增强 Visual Studio 代码内置的 Git 功能
- **HTML CSS Support** - CSS 支持 HTML 文档
- **Icon Fonts** - 流行图标字体的片段
- **Import Cost** - 在编辑器中显示导入/需要包大小
- **Markdown Preview Enhanced** - Markdown 预览增强
- **npm** - npm 支持 VS Code
- **npm Intellisense** - 用于在 import 语句中自动填充 npm 模块
- **Path Intellisense** - 自动填充文件名
- **Prettier** - 格式化您的 JavaScript / TypeScript / CSS
- **Sorting HTML and Jade attributes** - 按指定顺序对标记属性进行排序
- **TODO Highlight** - 突出显示 TODO，FIXME 和任何关键字，注释......
- **Vetur** - Vue 工具
- **vscode-fileheader** - 插入标题注释，并自动更新时间
- **vscode-icons** - Visual Studio 代码的图标
- **Vue Peek** - 允许对 Vue 单文件组件进行 peek 和 goto 定义
- **VueHelper** - Vue，Vue-router 和 Vuex 的代码片段
- **Web-Dev-Snippets** - Web 开发代码片段集合

#### 将这些推荐设置粘贴到 VS 代码工作区设置中，以增强您的 vs 代码。

```json
{
  "workbench.startupEditor": "newUntitledFile",
  "workbench.iconTheme": "vscode-icons",
  //创建文件的用户名
  "fileheader.Author": "Sun Rising",
  //更新文件的用户名
  "fileheader.LastModifiedBy": "Sun Rising",
  //文件头注释模板
  "fileheader.tpl": "/**\r\n * @Author: {author} \r\n * @Date: {createTime} \r\n * @Last Modified by: {lastModifiedBy} \r\n * @Last Modified time: {updateTime} \r\n * @Description: \r\n */\r\n",
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  //html属性排序
  "attrsSorter.order": ["data-.+", "aria-.+", "class"],
  //使用js-beautify-html格式化vue
  "vetur.format.defaultFormatter.html": "js-beautify-html",
  //格式化参数
  "vetur.format.defaultFormatterOptions": {
    "js-beautify-html": {
      //属性不换行
      "wrap_attributes": "auto"
    },
    "prettyhtml": {
      "printWidth": 500,
      "singleQuote": false,
      "wrapAttributes": true,
      "sortAttributes": false
    }
  },
  // 启用保存时自动修复
  "eslint.autoFixOnSave": true,
  "eslint.options": {
    "extensions": [".js", ".vue", ".jsx"]
  },
  //一组语言标识符指定要验证的文件
  "eslint.validate": ["javascript", "javascriptreact", "vue", "vue-html"],
  //高亮注释关键字
  "todohighlight.keywords": [
    {
      "text": "@Author",
      "color": "#000",
      "backgroundColor": "#808695"
    },
    {
      "text": "@Date",
      "color": "#000",
      "backgroundColor": "#c5c8ce"
    },
    {
      "text": "@Last Modified by",
      "color": "#000",
      "backgroundColor": "#dcdee2"
    },
    {
      "text": "@Last Modified time",
      "color": "#000",
      "backgroundColor": "#e8eaec"
    },
    {
      "text": "@Description",
      "color": "#000",
      "backgroundColor": "#f8f8f9"
    }
  ],
  //注释高亮默认注释
  "todohighlight.defaultStyle": {
    "fontWeight": "5000",
    "color": "#000",
    "backgroundColor": "#0dbc79",
    "cursor": "pointer",
    "border": "0px solid #eee",
    "borderRadius": "0px",
    "letterSpacing ": "2px",
    "isWholeLine": false
  },
  //是否启用注释高亮
  "todohighlight.isEnable": true,
  "search.exclude": {
    "**/node_modules": true,
    "**/bower_components": true,
    "**/dist": true,
    "**/build": true
  },
  "editor.fontSize": 16,
  //markdown样式
  "markdown-preview-enhanced.codeBlockTheme": "atom-dark.css",
  //markdown字体
  "markdown.preview.fontFamily": "\"Microsoft YaHei\",-apple-system, BlinkMacSystemFont, \"Segoe UI\", Roboto, Helvetica, Arial, sans-serif, \"Apple Color Emoji\", \"Segoe UI Emoji\", \"Segoe UI Symbol\"",
  //提示单词
  "cSpell.allowCompoundWords": true,
  //是否开启单词检查
  "cSpell.enabled": true,
  //添加单词字典
  "cSpell.userWords": ["Vetur", "vuex"]
}
```

#### 积分

- 感谢上述插件的原作者和贡献者。
