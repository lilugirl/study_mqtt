# study_mqtt

```
npm init 
npm install mosca --save
```


生成browserMqtt.js文件，并拷贝的项目根目录下
```
cd node_modules/mqtt
npm install .
 webpack mqtt.js ./browserMqtt.js --output-library mqtt
 ```

启动服务器端服务
```
node index
```

打开另一个终端，启动客户端 观察服务端变化
```
node client
```

打开客户端页面 http://localhost:3000 观察服务端变化
