# Kedrogy.github.io

```sh
bundle exec jekyll serve
```

## setup

follow this to get jekyll but

```sh
# otherwise fails:
# something wrong with LDFLAGS="-L/opt/homebrew/opt/llvm/lib"
# so 
unset LDFLAGS

ruby-install ruby 3.4.1
```

then

```sh
echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.bash_profile
echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.bash_profile
echo "chruby ruby-3.4.1" >> ~/.bash_profile # run 'chruby' to see actual version

> ruby -v
ruby 3.4.1 (2024-12-25 revision 48d4efcb85) +PRISM [arm64-darwin25]
```
