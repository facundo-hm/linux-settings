# linux-settings

####PS1 Customized

Model:
```
┌─[ user@linux ]---[ ~ ]
└─➤
```
Code:
```
\[\033[01;31m\]┌─[ \[\033[0;32m\]\u@\h\[\033[01;31m\] ]---[ \[\033[0;32m\]\w\[\033[01;31m\] ]\[\033[01;31m\]\n\[\033[01;31m\]└─➤ \[\033[00m\]
```

####Terminal Tabs Customized
~/.config/gtk-3.0/gtk.css
```
@define-color tab-active #2f2f2f;
@define-color text-grey #b7b7b7;
@define-color tab-grey #3b3b3b;

TerminalWindow .notebook {
    border: 0;
    padding: 0;
    color: #ddd;
}

TerminalWindow .notebook tab:active {
    background-color: shade(@tab-active, 1);
}

TerminalWindow .notebook tab {
    color: shade(text-grey, 1);
    border-radius: 0px;
    padding: 3px;
    background-color: shade(@tab-grey, 1);
}
```
