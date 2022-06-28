### How to add zim files?

- Download one or more ZIM files, e.g. from [https://download.kiwix.org/zim/](https://download.kiwix.org/zim/)
- Put the ZIM files into `/home/yunohost.app/kiwix/`
- Add them to the library with the following command:
```
/var/www/kiwix/kiwix-manage /home/yunohost.app/kiwix/library.xml add /home/yunohost.app/kiwix/*.zim
```

- Restart the service:

`yunohost service restart kiwix`
