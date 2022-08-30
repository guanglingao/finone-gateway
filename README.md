## 网关

#### 注册中心
1. 使用consul作为注册中心与配置中心
2. 本地服务启动命令
    ```
    consul agent -dev
    ```
#### 路由配置
使用动态路由配置

#### 配置中心配置
1. 在key/value中创建config文件夹
   ```
   http://localhost:8500/ui/dc1/kv
   
   config/
   ```
2. 在config文件夹中创建应用名称文件夹，此处为finone-gateway
   ```
   finone-gateway/
   ```
3. 创建dev-config的key/value存储，此处的dev-config是自定义的名称，值我直接拷贝的application.yml，保存为yml格式。