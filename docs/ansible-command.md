Host file 
```
ansible-playbook install_nginx.yaml -v
```

Inventory file
```bash
ansible-playbook -i inventory.txt install_nginx.yaml -v
```

見え方が多少異なる。

-vオプションを使うことにより、出力結果の詳細を知ることが可能となる。
標準出力を受け取っているイメージ？

