# リモートホストのSSHエージェントが停止した時の処理
ssh-agent bash  
sudo cp ec2-key.pem ~/.ssh/  
ssh-add ~/.ssh/ec2-key.pem  