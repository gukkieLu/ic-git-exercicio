# Exercício 7
`git clone <URL>` copia um repositório do GitHub para o computador do usuário. Cria-se uma cópia local ligada ao GitHub, e traz consigo todo o histórico de commits.
<br>
`git add <ficheiro>` seleciona uma versão do *working directory* para a *staging area*, edita-se os ficheiros, mas ainda não pertencem ao histórico (ainda não foi criado um commit).
<br>
`git commit -m "mensagem"` guarda as alterações no hitórico **local** com uma mensagem a fim de guiar o que foi mudado dentro do commit.
<br>
`git push` envia os commits locais para o GitHub (remoto). Apenas depois deste comando é que outras pessoas da equipa (ou outras cópias pessoais) poderão ver as alterações.
<br>
`git push` é o contrário do push. Recolhe as alterações do GitHub para o repositório local. Caso alterem a mesma linha em versões diferentes, gera um **conflito**.