git config --global user.name "xnzaa"
git config --global user.email "xu649981201@163.com"


ssh-keygen -t rsa -C "xu649981201@163.com"


������ɵ� SSH key �� ssh-agent��
ssh-add ~/.ssh/id_rsa

ssh -T git@github.com


�ο���https://segmentfault.com/a/1190000002645623