# CURSO GIT E VERSIONAMENTO

## CONCEITOS
Git - ferramente de versionamento de código

Existem 4 status que o arquivo pode estar:

UNTRACKED - Arquivo adicionado ao local e não versionado
UNMODIFIED - Esta mapeado pelo git, ja passou pelo Staged e dado commit
MODIFIED - Apos editar modificação de algum arquivo e não enviar ao repositório, ele fica neste status.
STAGED - pronto para dar o commit


##COMANDOS

git --config user.name "NOME" - adiciona o nome do usuário adicionado.
git --config user.email EMAIL - adiciona o email a ser usado no repositório remoto.

git init - inicializa o versionamento de modo local.

git add - adiciona o arquivo ao staged

git diff - verifica o que foi alterado, quais linhas
git diff --staged - demonstra as alterações após ser enviada para o staged.

git commit -m "Informação do commit enviado" - informar o que foi modificado ou incluido ao repositório 

git log - demonstra as modificações ocorridas nos arquivos após os commits

git restore NOMEARQUIVO - retorna ao ponto anterior
git restore --staged NOMEARQUIVO - retorna da área do staged para a área de modified


git push remote orign - envia os comandos para o repositório remotos
git pull - baixa os comandos que constam no repositório remoto, após alteração de outra pessoa.
git fetch -  Consulta os comandos que foram adicionados, para então realizar o git pull

git branch NOME - Cria uma nova branch com nome definido

git log --oneline --decorate - consulta em qual branch esta sendo apontada

git checkout NOME - Altera a branch para a nomeada

git merge NOME - Puxa todos arquivos que estava em outra branch - unindo os fluxos
