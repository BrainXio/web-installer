# web-installer

Repository containing installer scripts for dotfiles web-install function

Embed the block below in your .bashrc or .bash_aliases to easily install resources or wherever you want it.

```bash
web-install(){
    curl -s https://raw.githubusercontent.com/brainxio/web-installer/main/install-${1}.sh | sh
}
echo "available: 'web-install <app>'"
```
