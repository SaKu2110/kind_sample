# TODO

- 実行するコマンド  

`kind create cluster --name k8s-cluster --config k8s-cluster.yaml`  
上のコマンドの実行結果から環境変数`KUBECONFIG`を設定しろって言われるのでやる  
`export KUBECONFIG="$(kind get kubeconfig-path --name="k8s-cluster")"`  

- 解説  

`--name`: clusterの名前を設定する  
`--config`: 作成するclusterの設定ファイルを指定する  
