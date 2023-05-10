# firefoxic.zsh-theme

## About

This zsh theme is a fork of the `bureau` theme.

The appearance has not changed much, only the `node.js` version and git state have been rearranged for convenience.

[![The output of the `ls -lah` command, transformed by the `firefoxic` theme.][appearance]][appearance]

The most important change is that the `node.js` version indicator now works regardless of how `node.js` is installed. With the `firefoxic` theme you can use any `node.js` version manager (I use `volta` by the way 👀), it is not bound to `nvm`.

[![The output of the `git status` command. And also `node.js` version display with automatic version switching using Volta.][git+volta]][git+volta]

## Adding this theme

Run these commands:

```shell
cd $ZSH_CUSTOM/themes
git clone git@github.com:firefoxic/firefoxic-zsh-theme.git
ln -s ./firefoxic-zsh-theme/firefoxic.zsh-theme firefoxic.zsh-theme
```

Now specify the `firefoxic` theme in the `~/.zshrc` file:

```diff
-ZSH_THEME="bureau"
+ZSH_THEME="firefoxic"
```

And restart the terminal. Enjoy!

[appearance]: https://github.com/ohmyzsh/ohmyzsh/assets/3382798/5e4b87e6-9894-438a-97c1-45fbe8a78f7b
[git+volta]: https://github.com/ohmyzsh/ohmyzsh/assets/3382798/a02c87b2-20fe-45d0-9656-cb0b4840db34
