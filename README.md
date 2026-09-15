# rmpc-dots

- swap the colors to whatever you desire :)
- press `tab` to swap between the main view and the Artists tab. these are the only two tabs i have set up!
- lyrics/cava pane is visible on the artists tab as well as the main view :p
- these were created to be used at a specific window size, so may require some adjustment to look proper on your system!
- the on-song-change scripts dynamically swap the lyrics pane with a cava pane if no lyrics are found locally/if none can be automatically downloaded for that track. edit `theme` and `on-song-change` in `config.ron` if you want to use only one of these instead

## to use the smol album art w/ queue:

```
cd ~/.config/rmpc
cp config.ron.smol-art.bak config.ron
```

<img width="688" height="718" alt="smol-art" src="https://github.com/user-attachments/assets/2507fc68-23a5-4379-81d5-dd86ed82b1c1" />
<img width="688" height="718" alt="artists-tab" src="https://github.com/user-attachments/assets/99e9b55c-3de7-4b9e-8077-1e8e7ebf584b" />

## to use the large album art w/o queue:

```
cd ~/.config/rmpc
cp config.ron.large-art.bak config.ron
```

<img width="717" height="955" alt="large-art" src="https://github.com/user-attachments/assets/1ea687c6-0c30-4581-a1b7-c499689498b5" />
