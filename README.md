basic script with colors on, changes to green

you can already press "z" key to color top on most linux distros, 
but for alpine i didn't have this feature,
so i thought this would've been nice 

if anybody knows how to fix kb to gb that would be amazing

put this in /etc/profile ( replace $HOME/Downloads/top to wherever this file is ) to override top:
```
top() {
    command $HOME/Downloads/top $@
}
```
