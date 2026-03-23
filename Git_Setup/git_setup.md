# Git config
```
mkdir ~/.ssh
```
```
ssh-keygen -t ed25519 -C "GH_00m3_RepNm" -f ~/.ssh/id_ed25519_GH_00m3_RepNm
```
```
ssh-add ~/.ssh/id_ed25519_GH_00m3_RepNm
```
***Check added***
```
ssh-add -l
```
***Delete added***
```
ssh-add -d ~/.ssh/id_ed25519_GH_00m3_RepNm
```
### Define user name and user email globaly
```
git config --global user.name "00m3"
```
```
git config --global user.email "00m3@private"
```
### Config SSH agent aliases
```
/home/qwerty/.ssh/config
```
```
Host RepNm
        Hostname github.com
        IdentityFile=/home/qwerty/.ssh/id_ed25519_GH_00m3_RepNm
```
