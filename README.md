# grip_remove_header
The css to remove header from grip CLI markdown output


create a file ~/.grip/settings.py with

STYLE_URLS = ["https://raw.githubusercontent.com/KillianGDK-FDTI/grip_remove_header/master/grip.css"]

then run grip foo.md --export foo.html
