# pyradio-fluxfm
PyRadio config with FluxFM Playlist

## Download and install PyRadio
Follow this [instructions](https://github.com/coderholic/pyradio#installation)

## Configure PyRadio
Copy flux.csv to ~/.config/pyradio/
```bash
cd ~/.config/pyradio/
wget https://raw.githubusercontent.com/myrdrks/pyradio-fluxfm/main/flux.csv
```
Set FluxFM playlist as default
```bash
nano ~/.config/pyradio/config
```
change ```default_playlist = stations``` to ```default_playlist = flux```

Start PyRadio
```bash
pyradio
```

Enjoy!
