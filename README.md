![1715749515821](https://github.com/Thronedodyssey2235/8888/assets/171140648/1387fa0b-2b75-4524-a1a3-3d85c813485e)
# 8888
docker run \   -v &lt;CONFIG_FILE_PATH>:/etc/alloy/config.alloy \   -p 12345:12345 \   grafana/alloy:latest \     run --server.http.listen-addr=0.0.0.0:12345 --storage.path=/var/lib/alloy/data \     /etc/alloy/config.alloy
