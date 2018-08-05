This is test data for exiftool to extract metadata without all the extra image data :)

## Files: 

| filename | Description |
| --- | --- |
| raw.jpg | copy metadata from jpeg sources into this |
| raw.png | copy metadata from png sources into this |
| disney.jpg | metadata from a photo i took at disneyland |
 
## Copying Metadata

[source](http://u88.n24.queensu.ca/exiftool/forum/index.php?topic=3440.0)

```
> cp raw.jpg new.jpg
> exiftool -TagsFromFile "path/to/source" new.jpg
```