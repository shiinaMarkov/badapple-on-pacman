# badapple-on-pacman
## Requirements
```
mame version 0.220
```

## Install MAME
- Install mame from here: https://www.mamedev.org/
- Activate lua plugin: https://docs.mamedev.org/plugins/console.html

## MAME Settings
Make sure to have the pacman rom (pacman.zip) downloaded and moved into a recognized ROM directory. You can put it in the default MAME ROM directory or your own

## Generate frame text files
You would need to generate text files based on the video frames. This is done through the vid2pix repo.
- vid2pix: https://github.com/shiinaMarkov/vid2pix

Move these into the frames directory

## Running lua script
Go into directory where the lua script is and then run the following command in the command line

- Linux
```
mame -window -plugin console -autoboot_script badappleanim.txt pacman

```

Once the ROM is running, insert a coin and the animation will play

## Testing
This has only been tested in Linux specifically at the moment
