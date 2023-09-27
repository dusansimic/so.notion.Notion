# Notion Flatpak

This Flatpak can be build for local use with [fp-build](https://github.com/lionirdeadman/fp-build)
script.

Icons are stored in this repo since I'm lazy to add a module for asar and unpack it to extract the
icons during build. You'll need Git LFS to clone those icons too.

Work is based on [Alexanders][https://github.com/outergod/so.notion.Notion] manifest and instead of
repackaging Notion from Windows builds, I use build from [notion-repackaged](https://github.com/notion-enhancer/notion-repackaged)
project. They are a bit out of date tho.
