## 日常使いしてるもの

### OS

#### Ubuntu

2019年2月くらいから個人のPCにはUbuntuを入れている。

GNOMEの改造や、Keybindの改造(JISをUS仕様に変更)などすごくHackableで気に入ってる。

Makeをするのも速いし、DockerBuildも速いし文句がないくらい最高。

#### Mac

スタートアップで働いていた時や、UUUMの業務で使っている。また、iOS開発のときに使っている。

### Editor

日常使いしてるエディタが5つあるのでそれぞれについて書いていく。

#### Emacs

repo: [takeokunn/.emacs.d](https://github.com/takeokunn/.emacs.d)

Ubuntu使うときは必ず使うエディタ。もともとCommonLispを書くために導入したのだが、想像以上に自由度が高くハマっている。

やればやるほど欲しい機能が増えていき、最近は自分でEmacsLispを書くようになった。

US Keyboardでないと使いにくいのでUbuntuで使うようにしてる。

#### Sublime Text

プログラミングはじめた頃から、Macで日常的に使ってる汎用テキストエディタ。

細かい設定をしなくてもそれなりに動くので好き。

#### Vim

config: [.vimrc](https://github.com/takeokunn/dotfiles/blob/master/modules/vim/dot.vimrc)

gitの編集やちょっとしたサーバー内のコードの編集をしたいときに使うエディタ。

最低限の操作は理解している。

NeoBundleで最低限のpluginを入れてる。

#### Nano

config: [.nanorc](https://github.com/takeokunn/dotfiles/blob/master/modules/nano/dot.nanorc)

一時的にサーバー内に入って使うためのエディタ。最低限syntax highlightをするように設定している。

#### lem

config: [.lem](https://github.com/takeokunn/.lem)

CommonLisp製のテキストエディタ。Lispを書く使う。

#### Atom

Webフロントエンド専用テキストエディタ。 `.jsx` や `.vue` のような syntax highlightしづらい言語のために使う。

### Shell周り

#### Bash

config: [dotfiles](https://github.com/takeokunn/dotfiles/blob/master/modules/bash/Makefile)

`bash-it` を使っている。

#### Fish

config: [dotfiles](https://github.com/takeokunn/dotfiles/tree/master/modules/fish)

pathの管理や自前のfunctionなどを用意してる。

peco/ghq/zなどを使っている。

pluginはomfを使っている。

#### Tmux

config: [.tmux.conf](https://github.com/takeokunn/dotfiles/blob/master/modules/tmux/dot.tmux.conf)

tmuxはガッツリ使っている。

pluginはtpmを使っている。

### Browser

#### Chrome

日常的に使っている。 `chromemacs(vimmiumのemacs版)` というextension入れてる。

#### Firefox

Firefoxのほうが電池もちが良いので出先でよく使う。

Chromeと同様Emacs Keybindにしたかったのでxkeysnailを入れてる。

* [Ubuntu FirefoxをEmacs Keybindにする](https://takeokunn.xyz/blog/post/ubuntu-firefox-emacs-keybind)
