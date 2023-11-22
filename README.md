# minio

Minio - Minio - Docker compose

- MINIO_ROOT_USER: 账号

- MINIO_ROOT_PASSWORD: 密码

- MINIO_SERVER_URL: minio 服务地址

- MINIO_CONFIG_ENV_FILE: 环境变量文件

```
docker compose up -d
```

# docker

```
sudo yum install -y yum-utils
sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
```

```
sudo yum install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
```

```
sudo systemctl start docker
```
