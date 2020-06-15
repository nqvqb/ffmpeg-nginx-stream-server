# ffmpeg-nginx-stream-server
ffmpeg-nginx-stream-server
##### reference
1. https://askubuntu.com/questions/235347/what-is-the-best-way-to-uninstall-nginx
2. https://www.nginx.com/blog/video-streaming-for-remote-learning-with-nginx/
3. https://obsproject.com/
4. https://benwilber.github.io/nginx/rtmp/live/video/streaming/2018/03/25/building-a-live-video-streaming-website-part-1-start-streaming.html
5. https://stackoverflow.com/questions/1735933/streaming-via-rtsp-or-rtp-in-html5
6. https://videojs.com/
7. https://www.npmjs.com/package/videojs-contrib-hls
8. https://www.kurento.org/
9. https://realpython.com/getting-started-with-django-channels/
10. https://blog.heroku.com/in_deep_with_django_channels_the_future_of_real_time_apps_in_django
11. https://dzone.com/articles/hls-streaming-by-nginx-and-apche-tomcat
12. https://flashphoner.com/browser-based-webrtc-stream-from-rtsp-ip-camera-with-low-latency/
13. https://stackoverflow.com/questions/40921664/redirect-ip-camera-stream-from-a-raspberry-to-my-website
14. https://docs.huihoo.com/gnu_linux/squid/html/x505.html
15. https://www.digitalocean.com/community/tutorials/how-to-forward-ports-through-a-linux-gateway-with-iptables
16. https://www.digitalocean.com/community/tutorials/understanding-nginx-http-proxying-load-balancing-buffering-and-caching#:~:text=The%20most%20straight%2Dforward%20type,mainly%20found%20in%20location%20contexts.
17. https://andrewbrookins.com/django/how-does-djangos-streaminghttpresponse-work-exactly/
18. https://github.com/http-party/node-http-proxy
19. https://www.sipios.com/blog-tech/a-simple-reverse-proxy-in-python
20. 


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