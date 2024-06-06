# CURSO GIT E VERSIONAMENTO

## CONCEITOS
Git - ferramente de versionamento de código

##COMANDOS

git --config user.name "NOME" - adiciona o nome do usuário adicionado.
git --config user.email EMAIL - adiciona o email a ser usado no repositório remoto.

git init - inicializa o versionamento de modo local.

git add - adiciona o arquivo ao staged

git diff - verifica o que foi alterado, quais linhas
git diff --staged - demonstra as alterações após ser enviada para o staged.

git commit -m "Informação do commit enviado" - informar o que foi modificado ou incluido ao repositório 

Existem 4 status que o arquivo pode estar:

UNTRACKED - Arquivo adicionado ao local e não versionado
UNMODIFIED - Esta mapeado pelo git, ja passou pelo Staged e dado commit
MODIFIED - Apos editar modificação de algum arquivo e não enviar ao repositório, ele fica neste status.
STAGED - pronto para dar o commit
