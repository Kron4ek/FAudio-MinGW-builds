# FAudio-MinGW-builds
Latest FAudio MinGW builds (dlls) for Wine. Compiled with FFmpeg support.

To install, unpack dlls from archive to "prefix_path/drive_c/windows/system32" directory and override them to "Native" in winecfg. Or just use "wine_setup_native" script.

    export WINEPREFIX="$HOME/.wine"
    ./wine_setup_native

Source: https://github.com/FNA-XNA/FAudio
