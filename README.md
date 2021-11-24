# 2021-ad-cal

2021アドカレのネタ

## how to use

```shell
docker-compose build
docker-compose up -d

# nginxインストールの処理がskipされる確認
docker-compose exec ansible ansible-playbook -i hosts/docker playbooks/nginx-install.yml

# hogeの中身確認
docker-compose exec ansible ansible-playbook -i hosts/docker playbooks/echo-vars.yml

# built-in methodsの確認
docker-compose exec ansible ansible-playbook -i hosts/docker playbooks/built-in-methods.yml
```
