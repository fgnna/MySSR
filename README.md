# MySSR
sudo apt-get install privoxy
sudo gedit /etc/privoxy/config

forward-socks5t   /               127.0.0.1:1081 .

gedit ~./bashr

python /home/someday/Develop/SSR/shadowsocks/local.py -c /home/someday/Develop/SSR/shadowsocks/ssr_config.json -d start

sudo cp ./ssproxy /usr/local/bin
sudo chomd u+x /usr/local/bin/ssproxy
sudo 777 /usr/local/bin/ssproxy 

