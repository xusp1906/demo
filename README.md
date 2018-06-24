# demo
1，将连接方式从http更换为ssh。注意，github.com后面一定有(冒号):

git remote rm origin 
git remote add origingit@github.com:username/respository.git 

    1
    2

2，生成新的ssh key。这里会提示要不要rewrite，键入y，还有提示输入passPhrase，输入空格即可。

cd ~/.ssh
ssh-keygen  

    1
    2

3，测试一下连接。
ssh -T -v git@github.com

test
test


