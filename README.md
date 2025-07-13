# Meu Projeto Git
 segundo teste 
 # COMANDO DE EXECULÇÃO NO TERMINAL:(git diff) vai mostra a modificação, colocar esse comando no terminal do vs code, obs: sempre uasr o git diff antes de fazer o commmit, e muito importante para ver se realmente o codigo esta correto.

 # ok! agora entendi, sempre vou digita aqui, e não no terminal! porque estou usado o vscode e isso fica diferente como vo digitar os codigo eu digito aqui na pasta do codigo no vscode e execulto eles no terminal, tanto do powershell quanto do vs code, mais nesse momento estou usando o vc code.


 # COMANDO DE EXECULÇÃO NO TERMINAL:(git --no-pager diff)  Mostra tudo de uma vez, sem paginar, esse comando aqui não deixa a pagina do terminal fazer:

  Por que isso acontece?
 Paginação automática:

O Git usa o programa less (ou more no Windows) para exibir saídas longas.

Quando o conteúdo não cabe na tela, ele pára e mostra (END) ou : no final, esperando seu comando para continuar.

# COMANDO DE EXECULÇÃO NO TERMINAL:(git config --global core.pager "")  # Desativa o pager para todos os comandos

esse comando desativa o pager automatico globalmente em todos os arquivo.

# COMANDO DE EXECULÇÃO NO TERMINAL: (git diff --name-only) para saber o nome do arquivo que foi modificado

# COMANDO DE EXECULÇÃO NO TERMINAL: (git commit -am "Edit Readme") aqui eu vou comita um arquivo existente, se fosse a primeira vez seria git commit.

# COMANDO DE EXECULÇÃO NO TERMINAL: (git log) para ver quem fez a mudanças

# COMANDO DE EXECULÇÃO NO TERMINAL: (git show para ver o que foi feito de mudança no codigo)


# COMANDO DE EXECULÇÃO NO TERMINAL: (git checkout README.md) O comando g tem uma função específica no Git, e é importante entender quando e como usá-lo corretamente. Aqui está a explicação detalhada:
O que git checkout README.md faz?
Esse comando tem dous usos principais, dependendo do contexto:

Descartar alterações não commitadas no arquivo README.md:

Se você modificou o arquivo mas não fez git add, ele volta ao estado do último commit.

⚠️ Atenção: Todas as alterações não salvas serão perdidas!

Quando usar?
Cenário 1: Você editou o README.md e quer desfazer as alterações (antes de fazer git add).

Cenário 2: Você precisa restaurar o README.md para uma versão anterior (sem afetar outros arquivos).

O comando git reset HEAD é uma ferramenta poderosa para desfazer operações no Git. Vou explicar de forma clara e prática:

# COMANDO DE EXECULÇÃO NO TERMINAL: ( git reset HEAD) O que  faz?
Ele remove arquivos da área de staging (também chamada de "index"), mas mantém suas alterações no diretório de trabalho. É útil quando você adicionou arquivos com git add mas ainda não quer commitá-los.


Diferença para Comandos Similares:
Comando	O que Faz?
git reset HEAD	Tira arquivos do staging (mantém alterações)
git checkout -- arquivo	Descarta alterações não adicionadas (perde mudanças!)
git reset --hard HEAD	Perde tudo: alterações em staging e diretório de trabalho








