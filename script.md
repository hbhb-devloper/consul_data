- 导出kv键值
  consul kv export --http-addr=127.0.0.1:8500 -token=xxx '' > consul_kv.json
- 导入kv键值
  consul kv import --http-addr=127.0.0.1:8500 -token=xxx '' > consul_kv.json
- 查看value实际值
  echo 'value' | base64 -d
