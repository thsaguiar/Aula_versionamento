# Aula_versionamento
Here, we are going to put the cods about github x VScode

git -v < indicará qual é a versão do git instalado no computador. >

git clone linkrepositorio < o git instalado no computador + o terminal do VS code sincronizará/baixará os arquivos da parte do link >

git add . < adiciona a alteração ao arquivo >

git commit -m "comentario aqui" < adiciona comentários sobre a alteração >

git config --global user.email "" < para sincronizar, pode ser necessário adicionar um e-mail >

git config --global user.name "" < para sincronizar, pode ser necessário adicionar um nome de usuário >

git push origin main < git push é o comando que faz upload, origin é o repositorio remoto e main é o nome do ramo (branch) que está sendo enviado >

git pull origin main < faz o download dos arquivos que estão no github. se alguém mexeu no arquivo durante o tempo que eu estava mexendo, isso fará com que eu sempre tenha os arquivos atualizados na minha máquina >

clear < limpa a tela de comandos >

git log < acessa todo o historico de alteracao >

git log --oneline < resume o commit em uma linha, simplificando a visualização dela no terminal>

git log --stat < exige uma estatistica de quais arquivos foram alterados e a quantidade de linhas alteradas de maneira simplificada Pode ser usado --stat -- oneline em uma única linha de comando. >

git log -p < irá exigir as alterações que foram realizadas em cada commit. >

git log --author e o --grep < consegue pesquisar sobre um determinado autor ou por algum texto que tenha sido escrito na linha do tempo>

