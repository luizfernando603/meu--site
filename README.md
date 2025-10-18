# Barbearia do Luiz

Site estático com sistema simples de reservas via WhatsApp e painel admin local (localStorage).

Instruções rápidas para publicar no GitHub:

1. Abra PowerShell na pasta do projeto.
2. Substitua SEU_USUARIO e NOME_REPO pelos seus dados.

Sem GitHub CLI (crie o repositório no site do GitHub e depois execute):

```powershell
git init;
git add .;
git commit -m "Initial commit";
git branch -M main;
git remote add origin https://github.com/SEU_USUARIO/NOME_REPO.git;
git push -u origin main
```

Com GitHub CLI (cria o repo e faz o push automaticamente):

```powershell
# se não tiver, instale o gh: https://cli.github.com/
gh auth login
gh repo create NOME_REPO --public --source=. --remote=origin --push
```

Ativar GitHub Pages (após push):
- Vá em Settings → Pages → selecione branch `main` e root (/) → Salvar.
- Ou use o site do GitHub para ativar.

Observações:
- Substitua `meuWhats` dentro do `index.html` pelo número correto do salão.
- Se quiser que eu crie o repositório remoto para você via GitHub CLI, rode os comandos acima e me diga se encontrou algum erro.
