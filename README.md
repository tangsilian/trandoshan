我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

# Trandoshan dark web crawler

This repository is a complete rewrite of the Trandoshan dark web crawler. Everything has been written inside a single
Git repository to ease maintenance.

## Why a rewrite?

The first version of Trandoshan [(available here)](https://github.com/trandoshan-io) is working great but
not really professional, the code start to be a mess, hard to manage since split in multiple repositories, etc..

I have therefore decided to create & maintain the project in this specific directory, where all process code will be available
(as a Go module).

## How to start the crawler

Since the docker image are not available yet, one must run the following script in order to build the crawler fully.

```shell script
./scripts/build.sh
```

The crawler can be started using the start script:

```shell script
./scripts/start.sh
```
