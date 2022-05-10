Oh My Zsh のインストール
```bash
$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
テーマ
```diff
- ZSH_THEME="robbyrussell"
+ ZSH_THEME="ys"
```
ソースの反映
```bash
$ source ~/.zshrc
```
プラグインのインストール
```bash
$ git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
$ mv zsh-syntax-highlighting ~/.oh-my-zsh/plugins

$ git clone https://github.com/zsh-users/zsh-completions.git
$ mv zsh-completions ~/.oh-my-zsh/plugins

$ git clone https://github.com/zsh-users/zsh-autosuggestions.git
$ mv zsh-autosuggestions ~/.oh-my-zsh/plugins

$ git clone https://github.com/zsh-users/zsh-history-substring-search.git
$ mv zsh-history-substring-search ~/.oh-my-zsh/plugins
```
.zshrcの編集
```
plugins=(
  git
  zsh-syntax-highlighting
  zsh-completions
  zsh-autosuggestions
  zsh-history-substring-search
)
```
プラグインの反映
```
$ source ~/.zshrc
```
