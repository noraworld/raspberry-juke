# Raspberry Juke
Raspberry Juke lets your Raspberry Pi to play sound or music easily.



# Setup
Put some sound or music under the `$HOME/.pibox/` directory.

```shell
mkdir $HOME/.pibox
mv /path/to/sound-or-music-file $HOME/.pibox
```



## Usage
Play sound or music.

```shell
juke play /path/to/sound-or-music-file
```

You can also play multiple sound or music simultaneously.

```shell
juke play /path/to/sound-or-music-file /path/to/another-sound-or-music-file
```

Stop sound or music.

```shell
juke stop /path/to/sound-or-music-file
```

You can also stop all sound and music at once.

```shell
juke stop all
```



## License
All codes of this project are available under the MIT license. See the [LICENSE](/LICENSE) for more information.
