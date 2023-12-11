# cloudquery-helm
cloudquery kubernetes helm install

询盾cloudquery 
一体化数据库操作管控云平台
https://www.cloudquery.club

v2.6.0压缩包 转 helm部署

下载helm包,进入目录

kubectl create ns cloudquery

helm install cloudquery . -n cloudquery --set storageClassName=sc的名字

弄的粗糙，忽怪

初始账户密码： admin001/Hello123$