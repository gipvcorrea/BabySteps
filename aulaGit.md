**Passos Básicos do Git**



**Este documento reúne os comandos essenciais do Git para iniciar projetos, criar branches, versionar arquivos e enviar alterações para o GitHub.**



&#x20;**1. Inicializar um repositório**



**Cria um repositório Git dentro da pasta atual.**



**git init**



&#x20;**2. Verificar o status do repositório**



**Mostra arquivos modificados, não rastreados e o branch atual.**



**git status**



&#x20;**3. Criar e mudar para um novo branch**



**Cria um branch e já muda para ele.**



**git checkout -b nome-do-branch**



**Mudar para outro branch:**



**git checkout nome-do-branch**



&#x20;**4. Adicionar arquivos ao controle de versão**



**Adicionar um arquivo específico:**



**git add nome-do-arquivo**



**Adicionar todos os arquivos modificados:**



**git add .**



&#x20;**5. Fazer um commit**



**Registra as alterações no histórico do Git.**



**git commit -m "Mensagem do commit"**



&#x20;**6. Conectar ao repositório remoto (GitHub)**



**Adicionar o repositório remoto:**



**git remote add origin https://github.com/usuario/repositorio.git**



**Verificar se foi adicionado:**



**git remote -v**



&#x20;**7. Enviar alterações para o GitHub**



**Enviar o branch atual pela primeira vez:**



**git push -u origin nome-do-branch**



**Enviar commits futuros:**



**git push**



&#x20;**8. Atualizar o repositório local**



**Baixar alterações do repositório remoto:**



**git pull**



&#x20;**9. Ver histórico de commits**



**git log**



&#x20;**10. Desfazer alterações (básico)**



**Remover arquivo da área de staging:**



**git restore --staged nome-do-arquivo**



**Descartar alterações locais:**



**git restore nome-do-arquivo**

