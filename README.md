# wuji-registry

ReqPack catalog for **Wuji** — driver plugins and CLI packages.

## Catalog

`packages.json` lists:

- **wuji-ai-cli** — CLI frontend (`.rqp` index in `wuji-ai-cli-index.json`)
- **llama**, **echo**, **vllm**, **a1111**, **ffmpeg**, **raggo**, **gorag** — driver plugins from [wuji-driver](https://github.com/Coditary/wuji-driver)

## Install

```bash
# Via Wuji ReqPack plugin (package manager system "wuji")
rqp install wuji llama
rqp install wuji wuji-ai-cli

# Direct CLI package (once .rqp releases are published)
rqp install wuji-ai-cli
```

## Publishing wuji-ai-cli

Add platform entries to `wuji-ai-cli-index.json` (see [teez-cli-index.json](https://github.com/Coditary/teez-registry/blob/main/teez-cli-index.json) for format) pointing at GitHub release `.rqp` artifacts.

## Related

- [rqp-plugin-wuji](https://github.com/Coditary/rqp-plugin-wuji)
- [wuji-driver](https://github.com/Coditary/wuji-driver)
- [wuji-core](https://github.com/Coditary/wuji-core)
- [wuji-ai](https://github.com/Coditary/wuji-ai)
