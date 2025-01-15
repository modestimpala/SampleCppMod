# SampleCppMod

Basic template for creating UE4SS C++ mods.

## Setup

1. Clone this repo
2. Update `MOD_OUTPUT_PATH` in CMakeLists.txt:
```cmake
set(MOD_OUTPUT_PATH "C:/Users/[username]/AppData/Roaming/r2modmanPlus-local/VotV/profiles/[profile-name]/shimloader/mod/[mod-name]/dlls")
```

3. Update mod info in `src/dllmain.cpp`:
```cpp
ModName = STR("YourModName");
ModVersion = STR("1.0");
ModDescription = STR("Your mod description");
ModAuthors = STR("Your name");
```

## Building

Requires:
- CMake 3.18+
- MSVC compiler (14.38-14.40 recommended)
- UE4SS development files

## Documentation

See [UE4SS 3.0.0 C++ Setup](https://github.com/modestimpala/RE-UE4SS)

See [UE4SS official modding guide](https://docs.ue4ss.com/guides/creating-a-c++-mod.html) for details.