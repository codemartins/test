# Praticando Comandos do Git

Mais utilizados
---
git status <br>
git commit -a -m "texto" <br>
git checkout <br>
git branch <br> 
git push <br>


Iniciando repositório
---
git init (inicia o repositório git)
git status <br>
git add + NomeArquivo <br>
git add . (Adiciona todos os arquivos) <br>
git commit -a -m "texto" <br>
-a (pedindo pra add todos os arquivos no commit) <br>
-m (mensagem) <br>


Clonando Projeto
---
git clone + (link do repositorio) + espaço NomeDaPasta que desejar <br>
ex: git clone https://github.com/codemartins/test.git  PastaTeste


Projeto Remoto
---
git remote -v <br>
git pull (baixa todo o conteúdo atualizado do repositório remoto para o repositório local)


Trabalhando com Versões
---
git checkout -b NovaVersao (Cria nova versão e a torna padrão) <br>
git branch (Verifica as versoes) <br>
git checkout NomeDaBranch (para trocar de versão) <br>

git merde nomebranch (Unindo Branch) <br>
obs.: alterar git checkout + branch que irá receber alteração <br>
Ex: git checkout main <br>
git merge teste <br>
git push <br>

git branch -D nome (Deletando Branch)<br>

Diferenças entre Branch: <br>
git diff nomebrach..nomebranch


Log
---
git log  <br>
git log nome do arquivo <br>


Restaurando commit
---
git reset --hard idcomit  <br>


Remover do Stage antes do commit
---
git clean -n (Mostra o que será apagado) <br>
git clean -f (Deleta tudo fora do commit) <br>
git checkout + NomeDoArquivo (Restaura para versão anterior do commit) <br>

 Remover do stage e marcá-lo para exclusão após commit: <br>
git rm --cached file.html 

comparando arquivos: <br>
git diff arquivo


Info
---
Necessário está com o Git instalado na máquina. 

git --version <br>
Para verificar a versão instalada.


by: [Germeson Martins](https://github.com/germeson-martins) 06/11/2024
