# nesa
*使用的python3.12虚拟环境，环境文件在/root/.nesa/pythonenv*
## 教程
### 官方文档
[文档](https://docs.nesa.ai/nesa/run-a-nesa-node/installation)
*文档没有更新，能看的只有下载命令*
### 第三方教程
[教程](https://cryptonodehindi.medium.com/nesa-run-a-nesa-miner-node-61d619cfe36b)

## 命令
### 查看日志
```
docker logs --tail 100 -f orchestrator
```
### 获取id
```
cat ~/.nesa/identity/node_id.id
```
### 关闭容器
*容器是从/root/.nesa/docker/compose.community.yml启动的*
```
docker compose /root/.nesa/docker/compose.community.yml down
```
### 启动容器
```
docker compose /root/.nesa/docker/compose.community.yml up -d
```
## 相关网页
[状态查询](https://node.nesa.ai/nodes/H8VCdNsCaFW5qzPz5bwYiVsVnXTB2GirFdz9UJh9MPar)
[explore](https://explorer-test.nesa.ai/nesa-testnet-3/dashboard)
