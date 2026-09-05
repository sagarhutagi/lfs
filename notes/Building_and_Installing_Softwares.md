# Archiving

## tar

- tar -cf filename.tar /folder -> create a .tar file with folder
- tar -xf filename.tar -> extract a .tar file
- tar -tf filename.tar -> peek inside a .tar file

## gzip

- gzip filename -> compress a file
- gunzip or gzip -d filename.gz -> decompress the file

## both combined

- tar -czf filename.tar /folder -> create a .tar.gz file with folder
- just add z to compress it in the flags
- zstd filename
- unzstd filename.zst

