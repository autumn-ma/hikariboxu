# hikariboxu

## Description

GO project which will encode and decode any data to video.

This has dependencies with ffmpeg https://ffmpeg.org/

## Installation


```bash
git clone git@github.com:myan-ish/hikariboxu.git
cd hikariboxu

#Check env file for some configuration

#To encode
go run main.go <file_path> encode

#This will generate encoded_vid.mkv

#To decode
go run main.go <encoded_file> decode

#This will create file name decoded give the original extension to it and you can use it as expected

```

## TODO:

- [ ] Add buffer to save initial name and extension type
- [ ] Add integration to yt, fb, ... to upload and download vid


![image](https://github.com/user-attachments/assets/c4c39816-71de-41fa-9e94-d7d3c9d97f81)
