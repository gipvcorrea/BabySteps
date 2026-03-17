**1 - Certificar que vc não está dentro da branch que vc quer excluir, para isso fazer o comando para entrar na branch main**





**--rodar esse comando**

**git checkout main**



**e a próxima linha deverá ficar com mais no final:** 



**Exemplo: giovana.p.correa@L00712 MINGW64 \~/Documents/Workspace/BabySteps (main)**



**Assim certificamos que não estamos dentro da branch que vamos excluir.** 



**2 - No meu caso, o nome da minha branch que vai ser excluída é teste5**



**então eu rodo o comando assim:** 



**git branch -d teste5 --MUDAR PARA O NOME DA BRANCH QUE VC VAI EXCLUIR**



**Depois de rodar esse comando, dando tudo certo, deve aparecer isso:** 



**giovana.p.correa@L00712 MINGW64 \~/Documents/Workspace/BabySteps (main)**

**$ git branch -d teste5**

**warning: deleting branch 'teste5' that has been merged to**

&#x20;        **'refs/remotes/origin/teste5', but not yet merged to HEAD**

**Deleted branch teste5 (was 536b0c2).**



**3- Agora precisamos empurrar essa alteração para o git** 



**git push origin --delete teste5 --MUDAR PARA O NOME DA BRANCH QUE VC VAI EXCLUIR**



**Dando tudo certo, aparecerá isso:** 



**giovana.p.correa@L00712 MINGW64 \~/Documents/Workspace/BabySteps (main)**

**$ git push origin --delete teste5**

**To github.com:gipvcorrea/BabySteps.git**

&#x20;**- \[deleted]         teste5**





**é ir no seu git, atualizar a pagina e ver a branch já não aparece mais lá**



