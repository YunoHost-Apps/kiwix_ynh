### How to add zim files?

- Download one or more ZIM files, e.g. from [https://download.kiwix.org/zim/](https://download.kiwix.org/zim/)
- Put the ZIM files into `__DATA_DIR__`
- Add them to the library with the following command:
```
__INSTALL_DIR__/kiwix-manage __DATA_DIR__/library.xml add __DATA_DIR__/*.zim
```

- Restart the service:

`yunohost service restart kiwix`
