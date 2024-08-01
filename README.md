# This project is deprecated use [ADTMeta](https://github.com/Luzifix/ADTMeta) insted!

# Deprecated: ADTHeightDump
Automatically dumps tileset metadata from World of Warcraft ADT files into a JSON file and saves it to the [Output](Output) folder.

## Generated Metadata
- [Texture info by file id](Output/TextureInfoByFileId.json)
- [Texture info by file path](Output/TextureInfoByFilePath.json)
- [Texture info with file id and file path](Output/TextureInfoMeta.json)

## Usage
Arguments:  `ADTHeightDump.exe <wowProd> (outputFolder)`  

### Examples
`ADTHeightDump.exe wowt` (load WoW PTR, streams from CDN, slower)    
