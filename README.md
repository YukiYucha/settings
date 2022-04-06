## 設定
- アクティビティバー非表示にする
- Auto Save->afterDelay
- Tab Size->2
- Word Wrap->on
- Diff Word Wrap->on
- Emmet lang->ja
- Trigger Expansion On Tab->チェック
- Font Size->18
- Render Whitespace->all
- Font Family->Ricty Diminished
- Minimap: Enabled->チェックを外す
- Hover: Enabled->チェックを外す
- Encoding->UTF-8
- Render Line Highlight->gutter
- Unicode Highlight: Invisible Characters->チェックを外す
- Unicode Highlight: Non Basic ASCII->false
- Title->${dirty}\${activeEditorMedium}${separator}${rootName}
- Tree: Indent->12
- Tree: Render Indent Guides->always
- Integrated: Font Size->18
- Bracket Pair Colorization: Enabled->チェック
- editor.folding->チェックを外す
- Suggest: Basic->チェックを外す
- Word Separators->$を消す

```
// 保存時にコードが整形される
"editor.formatOnSave": true,
// 無駄なホワイトスペースを削除
"files.trimTrailingWhitespace": true,
//ブレークポイントの領域を消す
"editor.glyphMargin": false,
"terminal.integrated.fontSize": 18,
// 字間と行間を小さくする。
"editor.letterSpacing": -0.3,
"editor.lineHeight": 20,

// プレビューモードで開かれないようにする。
"workbench.editor.enablePreview": false,
"workbench.editor.enablePreviewFromQuickOpen": false,
// 素早い補完(Tailwind CSS)
"editor.quickSuggestions": {
        "strings": true
    },
```

## 拡張機能

### デフォルト
- Activitus Bar
- Code Spell Checker
- Dracula Official->Dracula Soft
- EditorConfig for VS Code
- Japanese Language Pack for Visual Studio Code
- Live Server
- vscode-icons
- indent-rainbow
- Path Intellisense
- GitLens - Git supercharged
- Git History
- DotENV
- Auto Rename Tag
- Docker

### Laravel
- Laravel Snippets
- Laravel Blade Snippets
- Laravel Artisan
- Laravel Blade Spacer

### PHP
- PHP Intelephense
- PHP DocBlocker
- PHP Debug
- php cs fixer

### Tailwind CSS
- Tailwind CSS IntelliSense
