Exercicio 01:

# A) Foi criado o arquivo.txt #
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ echo 01 > arquivo.txt 

# B) Foi adicionado o arquivo.txt no stagging e verificado o status
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git add  arquivo.txt 
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git status

# C) Foi commitado o arquivo 
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git commit -m "git add example - arquivo.txt"

# D) O arquivo foi sobrescrevido
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ echo 02 > arquivo.txt 

# E) Verificado o diff no arquivo
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git diff arquivo.txt

# F) Foi adicionado o arquivo no stagging e conferido o status
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git add arquivo.txt 
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git status

# G) Foi verificado o diff no arquivo
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git diff arquivo.txt

# H) O arquivo foi sobrescrevido 
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ echo 03 > arquivo.txt 

# I) Foi verificado o diff no arquivo 
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git diff arquivo.txt

# J) Foi realizado o restorer do arquivo na área de staging
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git restore --staged arquivo.txt
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git status arquivo.txt 

# K) Foi realizado o commit do arquivo e verificado o log
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git commit -m "Exercicio 01 - arquivo.txt" arquivo.txt 
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git log  arquivo.txt

# L) Foi criado um arquivo .gitignore e colocado o conteúdo *.txt
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ echo *.txt > .gitignore
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git log .gitignore

# M) Foi criado um arquivo chamado novo.txt e verificado o log
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ echo > novo.txt
@gusttavodutra ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git log novo.txt
