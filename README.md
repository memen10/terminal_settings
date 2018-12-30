# iterm, terminal 設定関連 備忘録
zsh, vim
色設定：solarized-dark

oh-my-zsh は入れていない

# リンクメモ
## zsh 設定
./config/.zshrc
を実環境にコピペ。（for Mac）
（cd 後の自動ls, cd 入力なしでのディレクトリ移動などができる）

## terminal, vim 色設定
https://qiita.com/HeRo/items/363b2aa18e7f225a8069

なお、
```
ターミナル → 環境設定 → プロファイル → Solarized Dark → ボールドテキストに明るい色を使用
```
の部分のチェックを外さないと、ls に色が適用されていないように見えてしまうので外す。


## iterm
まず solarized darkのカラーテーマ読み込み（Preference → Profiles → Color → Color presets）

その後、terminal におけるsolarized darkの設定と同様に
```
iTerm2 → Preference → Profiles → Colors
にある
[ ] Bold
```
の部分のチェックを外す。