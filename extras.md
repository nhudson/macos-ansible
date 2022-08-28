# Extra install

This will be the place to know about and setup extra things manually

## fzf-tab

[https://github.com/Aloxaf/fzf-tab#oh-my-zsh](https://github.com/Aloxaf/fzf-tab#oh-my-zsh)

Add `fzf-tab` to the plugin section of `$HOME/.zshrc`

```bash
git clone https://github.com/Aloxaf/fzf-tab ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/fzf-tab
```

# forgit

After installation you need to source this in your `$HOME/.zshrc`

```bash
# forgit shell environment
if [ -f "$HOME/.shell/forgit/forgit.plugin.zsh" ]; then
  source $HOME/.shell/forgit/forgit.plugin.zsh
fi
```
