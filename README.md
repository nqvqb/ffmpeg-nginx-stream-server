# ffmpeg-nginx-stream-server
ffmpeg-nginx-stream-server
##### reference
1. https://askubuntu.com/questions/235347/what-is-the-best-way-to-uninstall-nginx
2. https://www.nginx.com/blog/video-streaming-for-remote-learning-with-nginx/
3. https://obsproject.com/
4. https://benwilber.github.io/nginx/rtmp/live/video/streaming/2018/03/25/building-a-live-video-streaming-website-part-1-start-streaming.html

##### install
```sh
# remove existing nginx
git clone https://github.com/arut/nginx-rtmp-module.git
git clone https://github.com/nginx/nginx.git
cd nginx
./auto/configure --add-module=../nginx-rtmp-module
make
sudo make install
```