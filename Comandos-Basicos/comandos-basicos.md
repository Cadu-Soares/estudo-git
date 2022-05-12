<h1>Comandos Básicos</h1>

 - <h2>GIT INIT</h2>
O comando "git init" irá inicializar o repositório em sua máquina local.

 - <h2>GIT STATUS</h2>
O comando "git status", irá nos mostrar o estado do repositório; se esse repositório possuí arquivos "untracked", "tracked" ou "staged".

 - <h2>GIT ADD</h2>
 O comando "git add", irá preparar os arquivos que serão empacotados no commit; transferindo-os para a "staged area".<br>
 Ele pode ser feito de duas formas, preparando um arquivo individualmente ou todos os arquivos contidos no repositório de uma só vez:
 <h3>git add nome_arquivo.md</h3>
 <h3>git add .</h3>
 <h3>git add * (se estiver no git bash)</h3>


 - <h2>GIT COMMIT</h2>
 Preparados os arquivos, após o "git add", é hora de enviar a atualização para o repositório através do comando "git commit".<br>
 <h3>git commit -m "Descrição do commit"</h3><br>

<h2>OBS: ✏️ </h2>

 - <h3>UNTRACKED FILES</h3>
"Untracked files", como o próprio nome diz, são arquivos que não estão sendo rastreados pelo GIT. Estes arquivos podem até estar em seu repositório, mas não foram preparados para ser empacotados em um "commit".

 - <h3>MERGED FILES</h3>
"Merged Files", são arquivos prontos a serem commitados, você já apontou através do comando "add"

- <h3>TRACKED FILES</h3>
Ao contrário dos "untracked files", estes serão aqueles arquivos que já foram empacotados e identificados em um "commit". Logo após realizar um commit, se você der um "git status", ele identificará os arquivos que foram rastreados.

