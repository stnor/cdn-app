# CdnApp

1. Run the `build`.
2. Add `127.0.0.1	cdn.local` to your `/etc/hosts`
3. Run `serve`
4. Navigate to `http://localhost:4300/`.
5. Open the Network tab (all) and verify that the scripts and styles are loaded from cdn.local
6. Nota that the image `angular_white.png` is loaded from localhost. 

Expected behaviour would be that the image should be loaded from http://cdn-local:4300/ since the style asset and scripts are?
