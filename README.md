# Configs

My configuration files

## Installer

```
wget -qO- https://raw.github.com/IonicaBizau/configs/master/installer.sh | sh
```

## VIM files

 - `.vimrc`
 - VIM colors
 - plugins: Zencoding

## Johnny's apps

Small scripts that make the work faster. Put them in root:

```
sudo cp -r john<tab> /
```

Exmample:

Instead of:

```
git tag -d dev
git tag dev
git push --tags
```
we can use:

```
/j<tab>m<tab>
```

...where `<tab>` means <kbd>TAB</kbd> key press.

NodeJS JSON Validator:

```
node /j<tab>j<tab> test.json
```


## Applications

### Qt

```
wget -qO- https://raw.github.com/IonicaBizau/configs/master/utils/qt.sh | sh
```
