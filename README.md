# rmpc-dots

- place inside of your `~/.config/rmpc` directory
- swap the colors to whatever you desire :)
- press `tab` to swap between the main view and the Artists tab. these are the only two tabs i have set up!
- these were created to be used at a specific window size, so may require some adjustment to look proper on your system!
- the on-song-change scripts dynamically swap the lyrics pane with a cava pane if no lyrics are found locally/if none can be automatically downloaded for that track. edit `theme` and `on-song-change` in `config.ron` if you want to use only one of these instead.
- the spiral hearts on either side of the Status (i.e. Playing/Paused/Stopped) denote the following: left side is shuffle, right side is consume. bold means on. normal means off. (for consume, dimmed is one-shot)

## to use the smol album art w/ queue:

```
cd ~/.config/rmpc
cp configs/smol-art.bak config.ron
```

<img width="684" height="715" alt="09-16-2026-02:57:11-annotated" src="https://github.com/user-attachments/assets/3b3d4f1c-a708-4866-ad6d-36fc0f30e7da" />
<img width="684" height="715" alt="artists-tab" src="https://github.com/user-attachments/assets/99e9b55c-3de7-4b9e-8077-1e8e7ebf584b" />

## to use the large album art w/o queue:

```
cd ~/.config/rmpc
cp configs/large-art.bak config.ron
```

<img width="717" height="955" alt="large-art" src="https://github.com/user-attachments/assets/1ea687c6-0c30-4581-a1b7-c499689498b5" />

## to use the large queue

```
cd ~/.config/rmpc
cp configs/large-queue.bak config.ron
```

<img width="681" height="710" alt="09-16-2026-02:59:21-annotated" src="https://github.com/user-attachments/assets/b08ef167-a893-4251-8502-2a02f417ba96" />
<img width="681" height="710" alt="09-16-2026-20:46:54-annotated" src="https://github.com/user-attachments/assets/b652e8ac-9fe5-46c2-bc93-fbd6d566b323" />
