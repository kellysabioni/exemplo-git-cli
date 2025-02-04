# Usando o Git e GitHub via Linha de Comando (CLI)

## Comandos para operações mais comuns

- `git initi`               -> inicializa uma pasta como **repositório** Git
- `git status`              -> exibe informações do repositório/branch
- `git branch -m main`      -> renomear a branch de **master** para **main**
- `git add .`               -> adicionar arquivos ao **stage**
- `git commit -m "Texto"`   -> comitar com mensagem as alterações feitas (texto entre aspas duplas será inserido no commit)
- `git log`                 -> exibe o histórico de comits no repositório
- `git remote add ENDEREÇO_REPOSITÓRTIO` -> adiciona o repositório remoto como referência para o local (cria a conexão entre a pasta local com o repositório do GitHub - endereço utilizado no exemplo: `"git remote add origin https://github.com/kellysabioni/exemplo-git-cli.git"`)
- `git push origin main`    -> executa o push enviando as alterações para o repositório remoto (origin)
