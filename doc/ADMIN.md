### How to add zim files?

#### Add a zin file through its URL
- Click on the "Upload content" tab above.

#### Add a zim file by hand
- Download one or more ZIM files, e.g. from [https://download.kiwix.org/zim/](https://download.kiwix.org/zim/)
- Put the ZIM files into `__DATA_DIR__`
- Add them to the library with the following command:
```
sudo yunohost app shell __APP__
./kiwix-manage __DATA_DIR__/library.xml add __DATA_DIR__/*.zim
```

- Restart the service:

`yunohost service restart kiwix`
