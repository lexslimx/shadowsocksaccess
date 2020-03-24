1. Setup linux vm (tested with 16.04)
2. OPen ports 80, 443, 8388
3. Install docker cummunity for ubuntu
4. Run shadowsocks docker container with
docker run -e PASSWORD=<password> -p8388:8388 -p8388:8388/udp -d shadowsocks/shadowsocks-libev
5. Download shadowsocks windows client
https://github.com/shadowsocks/shadowsocks-windows/releases (Shadowsocks-4.1.9.2.zip)
6. Connect to server port:ip
7. Configure firefox to use socks5 proxy on localhost with the port configurd in the client
8. Profit!
