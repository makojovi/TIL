# Apacheのインストール手順
---

sudo yum update -y  

・Apacheのインストール  
> sudo yum -y install httpd  

・起動
> sudo systemctl start httpd.service  
> sudo systemctl status httpd.service  

ここでactiveが表示されればOK  

・サーバーが起動したときに一緒に起動するように設定  
> sudo systemctl enable httpd.service
