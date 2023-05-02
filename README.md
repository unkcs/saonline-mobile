# mt4mobile 

An experimental implementation of MTA and SAMP for GTA SA v210 aarch64 (for more details look at OpenSA repo)

## Project aims
- Complete replacement of build69 (SAMP for armv7a GTASA v1.8 !deprecated!)

## Todo
- [ ] Load our 3 (three) texture databases at startup
- [ ] Produce two database directories (we need to take advantage of all game texture database system, given a facilities to the user to load or replace game objects and textures)
- [ ] To hook InitializeRenderWare() (`On ARMv7a game version`) and to load our texture databases (for samp and mta) into the engine RenderWare memory space (The renderware will try to load all database from a relative path inside of .../files/texdb/`DATABASE_NAME`)

## Done

- [x] Hooking aarch64 functions

