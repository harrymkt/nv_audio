# NV Audio
`nv_audio` is a new, redesigned audio and sound management (sound pool) system written in and/or for [NVGT](https://nvgt.dev) scripting game engine.

You can run [test.nvgt](test.nvgt) for basic testing. To see more tests, go to the [test directory](test).

## Notes
- This is still in development, and should be able to use in your projects as a basic system.

## Contribution
We accept contributions as long as the established [contributions guidelines](.github/CONTRIBUTING.md) are followed.

## Documentation Status
[Documentation](docs) has been written, but this does not mean that it is complete. We appreciate any contributions regarding the documentation.

## Features
NV Audio module advertises the following features:

- Ease of Use: NV Audio is easy to integrate, use, and make changes.
- Custom Sound Types: Add to or modify any sound type as you wish if it does not meet your requirements. Add custom sound types by directly making child classes of specific sound types you want, as well as extend and modify existing sound types by directly making a child class of them.
- Custom NV Audio: Add to or otherwise modify the NV Audio module by making a child class of `nv_audio` to integrate your changes, custom logic, custom verifications and how sound types are added, without ever directly touching the main NV Audio module which would otherwise be painful especially if you have to copy and paste , and update all the time when the main NV Audio module is updated.
