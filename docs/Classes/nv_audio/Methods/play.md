# play
Play a sound.

1. `nv_audio_stationary@ play(const string &in filename, pack_interface@ pack, bool looping = false, bool persist = false, bool wait = false, bool immediate = true, float pan = 0, double volume = 0, double pitch = 100, const string &in owner = "", const string &in data = "");`

## Arguments (1):
- `const string &in filename`: The sound to play.
- `pack_interface@ pack`: The pack to use. This property can be entirely omitted.
- `bool looping = false`: Toggle sound looping.
- `bool persist = false`: Should the sound be cleaned up when it is finished playing?
- `bool wait = false`: Should the program be paused while the sound is playing?
- `bool immediate = true`: Should the sound play immediately the moment this sound is initialized?
- `float pan = 0`: The pan of the sound.
- `double volume = 0`: The volume of the sound.
- `double pitch = 100`: The pitch of the sound.
- `const string &in owner = ""`: The owner of the sound. Usually empty.
- `const string &in data = ""`: The data of the sound, useful for loading from memory. Usually empty.

## Returns:
`nv_audio_item@`: The sound item class (i.e. positional or stationary) on success, null otherwise.

## Remarks:
To determine which sound class returns by this function is, you can use casting or specify the return value, for instance, `nv_audio_positional@ s = sound_manager.play`. You can also use the `type` property to verify the sound type.
