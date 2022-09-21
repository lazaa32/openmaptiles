## OpenMapTiles style

### Fonts

To download fonts use `make download-fonts` target. 

It downloads _Noto Sans_ fonts (~70MB) and extract them into [openmaptiles/data/fonts](../data/fonts) directory.

### Icons

All related icons for OpenMapTiles style are located in [openmaptiles/style/icons](icons).

You can add your own svg icons into directory. 


To generate sprite run `make build-sprite`. Sprite 
will be generated into [build/style](../build/style) directory.

TO-DO
Check resize with Nick - is it something to share?
### Build style

To build style run `make build-style`

### Start tileserver-gl

```commandline
make start-tileserver
```

And go to [localhost:8080](localhost:8080).
