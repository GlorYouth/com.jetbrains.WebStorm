``` bash
zypper in flatpak-builder
flatpak-builder --force-clean --install-deps-from=flathub --repo=repo --install --user builddir com.jetbrains.WebStorm.yaml
```
