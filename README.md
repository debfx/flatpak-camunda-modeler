# Flatpak for Camunda Modeler

## Install

```
flatpak install flathub org.freedesktop.Sdk//20.08
flatpak install flathub org.electronjs.Electron2.BaseApp//20.08
flatpak-builder --user --install --force-clean build-dir com.camunda.Modeler.yaml
flatpak-builder --user --install --force-clean build-dir com.camunda.Modeler.Plugin.Linter.yaml
flatpak-builder --user --install --force-clean build-dir com.camunda.Modeler.Plugin.TransactionBoundaries.yaml
```
