# 設定

アクティビティ バー非表示にする

Files: Auto Save->afterDelay

Editor: Tab Size->2

Editor: Word Wrap->on

Diff Editor: Word Wrap->on

Emmet: Variables->lang - ja

Emmet: Trigger Expansion On Tab->チェックを外す(GoでTabが使えなかったから)

Editor: Font Size->18

Editor: Render Whitespace->all

Editor: Font Family->Ricty Diminished

Editor › Minimap: Enabled->チェックを外す

Editor › Hover: Enabled->チェックを外す

Files: Encoding->UTF-8

Editor: Render Line Highlight->gutter

Editor › Unicode Highlight: Invisible Characters->チェックを外す

Editor › Unicode Highlight: Non Basic ASCII->false

Window: Title->${dirty}\${activeEditorMedium}${separator}${rootName}

Workbench › Tree: Indent->12

Workbench › Tree: Render Indent Guides->always

Terminal › Integrated: Font Size->18

Editor › Bracket Pair Colorization: Enabled->チェック

Editor: Folding->チェックを外す

PHP › Suggest: Basic->チェックを外す

Editor: Word Separators->$を消す

Files: Eol→\n

Editor: Default Formatter->Prettier

```json
// 保存時にコードが整形される

"editor.formatOnSave": true,

// 無駄なホワイトスペースを削除

"files.trimTrailingWhitespace": true,

// 番号左ブレークポイントの領域を消す(デバック時以外)

"editor.glyphMargin": false,

// 字間と行間を小さくする。

"editor.letterSpacing": -0.3,

"editor.lineHeight": 20,

// プレビューモードで開かれないようにする。

"workbench.editor.enablePreview": false,

"workbench.editor.enablePreviewFromQuickOpen": false,

// 素早い補完(Tailwind CSS用)

"editor.quickSuggestions": {

"strings": true

},
```

# **拡張機能**

- Activitus Bar
- Auto Rename Tag
- Code Spell Checker
- Docker
- DotENV
- Dracula Official->Dracula Soft
- EditorConfig for VS Code
- Git Graph
- Git History
- indent-rainbow
- Japanese Language Pack for Visual Studio Code
- Live Server
- Path Intellisense
- Prettier - Code formatter
- vscode-icons

### **Laravel**

- Laravel Snippets
- Laravel Blade Snippets
- Laravel Artisan
- Laravel Blade Spacer

### **PHP**

- PHP Intelephense
- PHP DocBlocker
- PHP Debug
- php cs fixer

### **Tailwind CSS**

- Tailwind CSS IntelliSense

### Golang

- Go
