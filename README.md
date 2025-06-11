```bash
cd ~/.config
git init
git remote add origin git@github.com:enzolazz/dotfiles.git
git fetch
git checkout -t origin/main
git submodule update --init --recursive
```
