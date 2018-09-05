# HLS & DASH example

## Running this example locally

You can run this example locally with Docker

```
% docker run -p 3030:80 -v $PWD/videos:/opt/static/videos -v $PWD/nginx.conf:/usr/local/nginx/conf/nginx.conf tecfu/nginx-vod-module
```
