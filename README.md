# work2git

直接从本地把文件checkout出来就可以了，用不着从远程服务器上pull下来，因为，所有的历史版本你的本地都有的。
 
具体做法 git checkout file 同时恢复多个被删除的文件：
git ls-files -d | xargs -i git checkout {}
this is on the cloud I don`t konw why I cannot commit   
