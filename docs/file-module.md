ファイルモジュールを利用することで、ディレクトリの作成やファイルの作成が可能となる。
```bash
- name: Create directory
    file: 
    path: /home/ec2-user/filemodule
    state: directory

- name: Create file
    file: 
    path: /home/ec2-user/filemodule/filemodule.txt
    state: touch
```