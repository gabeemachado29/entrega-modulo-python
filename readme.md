# Entrega do Projeto Python

Este repositório contém o script desenvolvido no módulo anterior, bem como um facilitador de execução em Shell Script.

# 🚀 Como executar o arquivo .sh

Para rodar este projeto utilizando o script executável, siga os passos abaixo no seu terminal Linux ou WSL:

# 1. Certifique-se de que você está na pasta do projeto.
# 2. Dê permissão de execução para o arquivo (necessário apenas na primeira vez):
   ```bash
   chmod +x run.sh
 
3. Execute o script:
    ```bash
    ./run.sh
Passo 4: Hospedar os arquivos (Subir para o GitHub)

Agora vamos enviar o `app.py`, o `run.sh` e o `README.md` para o repositório criado.

**Opção A: Via Linha de Comando (Recomendado)**
Abra o terminal na pasta do seu projeto e digite:

```bash
git init
git add .
git commit -m "Primeira entrega: scripts e documentação"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPO.git
git push -u origin main