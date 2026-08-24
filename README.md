# Shell Tavern Portrait Assets

Original SFW character portraits for the Shell Tavern roleplay UI.

The `portraits/` directory is published through jsDelivr. Pin consumers to a
commit URL instead of the mutable `main` branch when building a character card:

```text
https://cdn.jsdelivr.net/gh/JSML0707/shell-tavern-portraits@<commit>/portraits/<file>.png
```

The image files are public assets. The accompanying `portrait-manifest.json`
contains the character ID and filename mapping used by the card build.

The Shen Qianxia card has two non-destructive portrait releases. The original
set uses `shen-qianxia-portrait-manifest.json` and
`portraits/shen-qianxia/`. The second, more theatrical Japanese mystery-VN set
uses `shen-qianxia-v2-portrait-manifest.json` and
`portraits/shen-qianxia-v2/`. Consumers must pin either release to an immutable
commit URL.
