# ItsRenjiLabs VPM listing

The package listing for ItsRenjiLabs tools in the VRChat Creator Companion (VCC).

**[Add to VCC](https://itsrenjilabs.github.io/vpm/)**, or add this URL under Settings > Packages > Add Repository:

```text
https://itsrenjilabs.github.io/vpm/index.json
```

## Packages

| Package | Description |
| --- | --- |
| [Conduit](https://github.com/ItsRenjiii/Conduit) | MCP-native Unity bridge that gives AI coding agents the whole editor, UdonSharp and the VRChat SDK. |

## How it updates

The listing is built by GitHub Actions from the releases of each repository in [`source.json`](source.json) and published to GitHub Pages. It rebuilds when `source.json` changes, when a package release sends a `package-released` dispatch, or when the workflow is run by hand.

Built from VRChat's [template-package-listing](https://github.com/vrchat-community/template-package-listing).
