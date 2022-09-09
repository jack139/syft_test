# pySyft 测试



## 安装

安装py包

```bash
sudo pip3 install syft hagrid
```



## 使用docker

### 注意事项

- docker-ce 版本需要支持 docke compose 2.x
- docker 执行时需要不用 sudo 



### 启动docker

```bash
hagrid launch test
```



### 停止docker

```bash
hagrid land test
```



### 管理端 UI

```
http://localhost:8081

用户密码：
info@openmined.org
changethis
```



### py中登陆

```python
import syft as sy
domain = sy.login(email="info@openmined.org", password="changethis", port=8081)
```



## 测试

