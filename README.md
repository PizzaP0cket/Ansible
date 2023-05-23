# Ansible

## List of Programs to Auto Install

| Application to install | Pass | Fail |
| ---------------------- | ---- | ---- |
| Test Color             | ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) | ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) |
| Visual Studio Code     |      |      |
| Steam                  |      |      |
| Epic Games             |      |      |
| EA Play                |      |      |
| Uplay                  |      |      |
| Battle.net             |      |      |
| Rockstar Launcher      |      |      |
| Spotify                |      |      |
| Firefox                |      |      |
| Firefox `(Ublock)`     |      |      |
| Firefox `(AdGuard)`    |      |      |
| Firefox `(AdBlocker)`  |      |      |
| Firefox `(Ghostery)`   |      |      |
| Firefox `(Honey)`      |      |      |
| Yuzu                   |      |      |
| Geforce Experience     |      |      |
| Geforce Broadcast      |      |      |
| OBS                    |      |      |
| Paint.net              |      |      |

> Add any applications that windows installs by default.

| Application to uninstall | Pass | Fail |
| ------------------------ | ---- | ---- |
| Dsiney+                  |      |      |
| Skype                    |      |      |
| Microsoft News           |      |      |
| Tiktok                   |      |      |
| Prime Video              |      |      |




## Process for Setting up Ansible
### Ensure pip is installed
> User what ever variation of Python works for you e.g. (python, python3, py).
```python
$ python -m pip -V
```

### Make sure python3 is set up
>Might be worth adding directory to PATH before running this command
>C:\Users\USER\AppData\Local\Programs\Python\Python311\Scripts
```Python
$ python -m pip install ansible
$ python -m pip install --upgrade --user ansible
```
