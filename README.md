# danhancach/OTA

OTA metadata (JSON + changelog) cho các ROM cá nhân.

Layout mỗi ROM: một thư mục, hai file theo device:

| ROM | Path |
|-----|------|
| Evolution X | `evoX/<device>.json`, `evoX/changelog_<device>.txt` |
| Cherish | `cherish/<device>.json`, `cherish/changelog_<device>.txt` |
| voidUI | `voidUI/<device>.json`, `voidUI/changelog_<device>.txt` |

Ví dụ pdx237 (Evolution X):

- `https://cdn.jsdelivr.net/gh/danhancach/OTA@main/evoX/pdx237.json`
- `https://cdn.jsdelivr.net/gh/danhancach/OTA@main/evoX/changelog_pdx237.txt`

Binary (zip / images) trên SourceForge — repo này chỉ metadata.
