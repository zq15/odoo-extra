# odoo-extra
这个项目会记录我的odoo相关的一些想法

## 已有的模块
multi
这个模块使用docker-compose部署odoo，自动集成了redis，解决了odoo的分布式session问题
切换到odoo-extra 目录，运行 `docker-compose up 即可`
nginx反向代理暴露 8000 端口 
