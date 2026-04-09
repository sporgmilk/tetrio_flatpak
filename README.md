# tetrio_flatpak
A flatpak build of tetr.io (v10)

# Build instructions:

### Install flatpak-builder

    flatpak install org.flatpak.Builder

### Install dependencies

    flatpak install org.electronjs.Electron2.BaseApp/x86_64/25.08 org.freedesktop.Sdk/x86_64/25.08

### Build/install

    flatpak run org.flatpak.Builder --user --install build-dir io.osk.tetrio.yml
