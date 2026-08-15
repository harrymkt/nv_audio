# destroy
Stops and removes one or more sounds.

1. `bool destroy(nv_audio_item@ handle);`
2. `int destroy(nv_audio_item@[] handles);`
3. `int destroy(const string &in owner);`

## Arguments (1):
- `nv_audio_item@ handle`: A handle to the sound you want to remove.

## Arguments (2):
- `nv_audio_item@[] handles`: An array of handles to the sounds you want to remove.

## Arguments (3):
- `const string &in owner`: The sound's owner to remove. This will remove all sounds under this owner.

## Returns:
1. `bool`: true on success, false on failure.
2. `int`: The number of sounds that have been removed.
3. `int`: The number of sounds that have been removed.
