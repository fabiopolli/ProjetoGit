Git comandos

Gerar chave SSH
ssh-keygen -C "joaopaulomoreira"
Consultar a public key ssh
cat ~/.ssh/id_rsa.pub
Configurar a chave no azure
Testar a conexão
ssh -T git@ssh.dev.azure.com
Retorno
remote: Shell access is not supported.
shell request failed on channel 0


Gerar chave HTTPS
Configurando o git para terminal
Abra o Git Bash e siga com os códigos abaixo 
Git config  —global user.name “Fabio Polli
Git config  —global user.email “fabio.polli@neon.com.br”


Git Controle de versões primeiro cenário de desenvolvimento, com um único desenvolvedor  
Digitar Cd nome da pasta
Ex: 
Cd aulas
Cd git
Cd local
Para sair basta digitar 
Cd ..
Cd ..
Cd ..
Para facilitar o acesso a uma pasta
Cd aulas/git/local
Para limpar as linhas de comandos
Clear
Para criação de um repositório
Git init
Para Status
Git status
Para Track
Git add exemplo: readme.txt(Após incluir os arquivos no repositório)
Para adicionar todos os arquivos de textos
Git add *.txt(para abrir todos os arquivos txt por exemplo)
Git add .(para add todos os arquivos do seu diretório)

Depois de adicionar todos os arquivos 
Digite git status
Irá aparecer todos os arquivos disponíveis para commitar 
Git commit -m ˜Msg para identificar o seu commit”
Exemplo: Git commit -m ˜commit inicial˜
Git commit -a -m(Pula o add)

Analisando alterações mais detalhadas
Cd aulas/git/local
Git diff(Vermelho=removeu Verde=adicionou)
Git diff —staged(Quando não aparecer alterações)
Git log(Histórico de todos os log comitts e tem número de versões para rollback)
Git log -p(todos Logs + alterações) 
Git log -p -1(Apenas um log e alterações)
Gitk (Visualiza relatório em uma interface melhor)
Git log —pretty=online(Código de cada comitt e a msg desse comitt)

Para abrir uma branch utilizar o seguinte comando
Git Checkout + código da branch
Git Pull 
Git Fetch —all (Tentar resolver o problema, atualizando as brenchs)