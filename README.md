# zshrc
zsh 設定管理用リポジトリ

### .zshrc に書いておくべきこと
```
FPATH="${HOME}/.zshrc-git:${FPATH}"

autoload -Uz zshrc-base && zshrc-base
autoload -Uz zshrc-zplug && zshrc-zplug
autoload -Uz zshrc-prompt && zshrc-prompt
autoload -Uz zshrc-alias && zshrc-alias
autoload -Uz zshrc-python && zshrc-python
```

ホームディレクトリに .zshrc-git フォルダを作り、そこに clone する
