# obs-pipewire-audio-capture-flatpak
https://github.com/dimtpap/obs-pipewire-audio-capture
https://github.com/stashymane/obs-retro-effects-flatpak

Flathub configuration for OBS PipeWire Audio Capture

Run the following commands to install

```sh
git clone https://github.com/BenStensaa/obs-pipewire-audio-capture-flatpak.git
cd obs-pipewire-audio-capture-flatpak
# Install
flatpak remote-add --user --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo
flatpak-builder --force-clean --user --install-deps-from=flathub --repo=repo --install build/ com.obsproject.Studio.Plugin.PipeWireAudioCapture.yaml
```
