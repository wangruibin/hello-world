# hello-world
2 配置代理
mkdir -p /etc/systemd/system/docker.service.d
vi /etc/systemd/system/docker.service.d/http-proxy.conf
增加如下内容：
[Service]
Environment="http_proxy=http://ptaishanpublic2:Huawei123@172.18.32.221:8080" "https_proxy=http://ptaishanpublic2:Huawei123@172.18.32.221:8080"
