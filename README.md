![invideo](assets/icon.png)

# invideo editor plugin for Claude

[invideo](https://invideo.io) is a professional video editor with a multitrack timeline. This plugin connects Claude to it. Claude trims, captions, grades and mixes on your timeline while you watch every change land, and you can take over at any frame. Upload footage, describe the edit, review the cut, export.

This plugin covers editing only. Its skills do not use invideo's generation features.

## Install

```sh
claude plugin marketplace add invideoio/invideo-editor-claude-plugin
claude plugin install invideo-editor@invideo-editor
```

On first use Claude installs the [invideo CLI](https://github.com/invideoio/cli) with npm (or Homebrew or uv) and opens a browser tab for you to sign in.

## Skills

| Skill | For |
|---|---|
| `invideo` | Read first: how to connect, the work loop, cost, and every job type, from launch videos and ads to invitations and captions |
| `invideo-media` | Uploads, stock, checking media, voice and music craft |
| `invideo-timeline` | Frame math, tracks, keyframes, color, effects and the mix |
| `invideo-pipeline` | Many videos from data, scripted runs, CI, several agents in one project |
| `higgsfield-to-invideo` | Finish Higgsfield clips: cuts, captions, music |
| `runway-to-invideo` | Finish Runway clips: cuts, captions, music |
| `magnific-to-invideo` | Finish Magnific video: layout, captions, music |
| `remotion-to-invideo` | Finish a Remotion composition: cuts, captions, music |
| `hyperframes-to-invideo` | Finish a HyperFrames composition: cuts, captions, music |
| `openedit-to-invideo` | Finish an OpenEdit plan: cuts, captions, music |

## Docs

The docs are at [docs.invideo.io](https://docs.invideo.io), with the references for the [CLI](https://docs.invideo.io/reference/cli) and the [edit operations](https://docs.invideo.io/reference/edit-operations).

## License

[Apache-2.0](LICENSE)
