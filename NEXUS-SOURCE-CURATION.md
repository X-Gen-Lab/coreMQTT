# Nexus selected-source curation

Upstream release: coreMQTT v2.3.1 (MQTT 3.1.1).
Upstream commit: `2beef04725328923e05e576b884212d53ec97af7`.
Upstream tree: `c216ae5b6848f60d43b498aea71701d9ac5a5159`.

This source SDK integration uses the official production C sources unchanged.
Nexus host contracts use the separately pinned GoogleTest/GoogleMock framework.
The upstream CMock test dependency is therefore excluded from this curated
branch's declarations and Git tree:

- Original path/name: `test/unit-test/CMock`
- Original URL: `https://github.com/ThrowTheSwitch/CMock`
- Original gitlink: `afa294982e8a28bc06f341cc77fd4276641b42bd`

No CMock source is redistributed by this selection. This metadata-only
curation does not change upstream algorithm sources, the original MIT license,
or the immutable upstream tag. It does not qualify firmware or hardware.
