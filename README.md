这个时间段的rancher/rancher:latest对应是rancehr/rancher:v2.10.0

修改步骤：

1、创建自己的SSL证书并将.pem和.key文件重命名为cacerts.pem、cacerts.key放到certs文件夹下

2、修改values.yaml，将<your-domain>和<rancher.domain>替换为你自己的域名。我这里harbor和rancher部署在一台服务器中，所以两个域名对应的ip都是同一个。
