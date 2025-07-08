## images 项目说明

### random-pic-api.tar.gz

- 随机壁纸 `API` 镜像

- 下载镜像并加载

```bash
wget -c https://images.meimolihan.eu.org/random-pic-api.tar.gz && \
bash <(curl -sL gitee.com/meimolihan/script/raw/master/sh/compose/docker_load_all_images.sh) && \
rm random-pic-api.tar.gz
```

### hexo_images.tar.gz

- hexo 博客镜像

```bash
wget -c https://images.meimolihan.eu.org/hexo_images.tar.gz && \
bash <(curl -sL gitee.com/meimolihan/script/raw/master/sh/compose/docker_load_all_images.sh) && \
rm hexo_images.tar.gz
```

