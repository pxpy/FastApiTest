# aliyun-bigmodel

## 启动
1. python版本3.10

## 创建隔离环境(可选)
> python -m venv myenv

## 依赖包安装
> pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple/

### 后端服务
uvicorn  main:app  --host  0.0.0.0  --port  8080  --log-config  log.json