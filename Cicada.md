# install
0. 切换到非root用户(不然会有坑)
1. 配置代理(可选) `export http_proxy=http://192.168.65.2:10811 && export https_proxy=http://192.168.65.2:10811`  
如果下载很慢尝试开关代理 `export http_proxy= && export https_proxy=`
> `ping host.docker.internal` 获取宿主机ip(需要先在v2ray上开启局域网访问)
2. `curl https://install.meteor.com/ | sh ` 装meteor
3. `nvm install 14.19.3` 装node
4. `yarn`
这一步访问github需要代理

# start
`yarn dsv`

# lasaASDAhttps://developer.rocket.chat/rocket.chat/rocket-chat-environment-setup/linux
sudo apt-get update && sudo apt-get dist-upgrade -y && \
sudo apt-get install build-essential git curl python3-minimal pkg-config && \
curl https://install.meteor.com/ | sh && \
