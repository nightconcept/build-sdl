# build-sdl

Checks and builds new SDL3 and satellite libraries for Windows, MacOS, and Linux.

## Notes

- SDL_mixer is in a strange transitional state and as of 5/26/25. My use of [SDL3-CS](https://github.com/edwardgushchin/SDL3-CS) will refer SDL2_mixer as SDL3_mixer despite being API-wise SDL2. build-release-sdl3-mixer.yml builds off of the main branch which is versioned as SDL3.

## Credits

- [Zyko0/go-sdl3: SDL3 bindings for Go](https://github.com/Zyko0/go-sdl3) for the basis of all of my build workflows.
