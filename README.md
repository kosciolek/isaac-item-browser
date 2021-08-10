Messy code, written over 2 years ago

# Live

[Link.](https://kosciolek.github.io/isaac-item-browser/)

# Isaac Item Browser

A visual item browser for The Binding of Isaac.

## Extractor

1. Extracts item data from game files.
2. Scrapes item descriptions from Isaac's wiki

To extract, edit the config [./gameDataExtractor/src/index.ts](./gameDataExtractor/src/index.ts) and fire:
```
yarn extract-build && yarn extract
```

Custom tags may be added here [./gameDataExtractor/customData/customData.json](./gameDataExtractor/customData/customData.json)

## Build

```
yarn build
```

![](https://i.imgur.com/ooxsYsE.png)
![](https://i.imgur.com/Wt4URhc.png)
