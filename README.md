# grip_remove_header

## grip CLI

To install grip, simply:

```sh
pip install grip
```

On OS X, you can also install with Homebrew:

```sh
brew install grip
```

[grip documentation and usage](https://github.com/joeyespo/grip)

Now, here is the megtod to remove annoying header from grip CLI markdown output

```sh
# create a file ~/.grip/settings.py
touch ~/.grip/settings.py
```

With the following content :

```python
STYLE_URLS = ["https://raw.githubusercontent.com/KillianGDK-FDTI/grip_remove_header/master/grip.css"]
```

then run grip foo.md --export foo.html
