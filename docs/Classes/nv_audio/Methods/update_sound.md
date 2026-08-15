# update_sound
Updates a sound.

`bool update_sound(nv_audio_item@ snd, vector cd, bool call_main_update = true);`

## Arguments:
- `nv_audio_item@ snd`: A handle to the sound you want to update.
- `vector position`: The sound's position in vector form to update.
- `bool call_main_update = true`: Should the update also call the main `update_sound_positions` internal method?

## Return value:
`bool`: true on success, false on failure.
