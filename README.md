# wybug --致力于高程度还原安全研究员发觉的经典漏洞

wybug是自己在企业内部安全培训的时候，为程序员特意编写的一些wooyun上安全研究员经典的漏洞环境，立志于抛开不相关的业务模型，直奔漏洞本身。自己在入门安全的道路上走了不少弯路，也希望通过此项目将自己的成长与所得分享给大家。用P神的Vulhub一样使用docker-compose，可快速构建漏洞环境。

目的主要是在黑盒发现安全问题的基础上，能通过白盒分析，并掌握思考相关的修复方案

## 使用方法

安装使用方法与vulhub一致请参考：
```bash
https://github.com/vulhub/vulhub/blob/master/README.md
```

国内在进行`docker-compose build`这一步时候会比较缓慢，建议更新docker源：
```bash
vi /etc/docker/daemon.json
```

添加：
`
{
    "registry-mirrors": ["https://dftbcros.mirror.aliyuncs.com"]
}
`

## 注意事项

务必不要在企业生产网络上激活此环境，可能给企业的信息安全造成相当大的危害。


