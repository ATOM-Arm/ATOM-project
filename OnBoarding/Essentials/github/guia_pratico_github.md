# Treinamento Básico de Git e GitHub


# Terminal
---

## 1. Preparação Inicial

### Clonar o repositório ATOM

```bash
git clone https://github.com/ATOM-Arm/ATOM-project.git
cd ATOM-project
```

### Criar um branch para o seu treinamento

```bash
git checkout -b seu_nome-treinamento-github
```
### Criar um arquivo de treinamento
```bash
touch OnBoarding/Essentials/github/treinamento.md
```

### Editar o arquivo de treinamento
Abra o arquivo `treinamento.md` no seu editor de texto favorito e adicione as seguintes informações:

```markdown
# TREINAMENTO
Olá ATOM! Este é o meu treinamento básico de Git e GitHub. Estou aprendendo a usar o Git para versionamento de código e colaboração em projetos.
```

### Adicionar o arquivo ao Git

```bash
git add OnBoarding/Essentials/github/treinamento.md
```
### Fazer commit das alterações

```bash
git commit -m "Adiciona treinamento básico de Git e GitHub"
```

### Enviar o branch para o repositório remoto

```bash
git push origin treinamento-github
```
### Criar um Pull Request
Acesse o repositório no GitHub e crie um Pull Request a partir do branch `treinamento-github`. Descreva brevemente o que você fez e por que está fazendo isso.

## 2. Revisão do Pull Request
Peça a um mentor ou colega para revisar o seu Pull Request. Eles podem sugerir melhorias ou aprovar as suas alterações.
## 3. Merge do Pull Request
Após a aprovação, faça o merge do seu Pull Request no branch principal (`main` ou `master`). Você pode fazer isso diretamente no GitHub.
## 4. Limpeza do Branch
Após o merge, você pode excluir o branch de treinamento local e remoto:

```bash
git branch -d treinamento-github
git push origin --delete treinamento-github
```

## 5. Conclusão
Parabéns! Você completou o treinamento básico de Git e GitHub. Agora você está pronto para contribuir com os projetos do ATOM e continuar aprendendo mais sobre controle de versão e colaboração em equipe.

---


# GitHub Desktop

---

## 1. Preparação Inicial

### Clonar o repositório ATOM

1. Abra o GitHub Desktop.
2. Clique em **File > Clone repository...**.
3. Cole a URL `https://github.com/ATOM-Arm/ATOM-project.git` e escolha a pasta de destino.
4. Clique em **Clone**.

### Criar um branch para o seu treinamento

1. No topo da janela, clique no menu suspenso de branch.
2. Clique em **New Branch**.
3. Nomeie o branch como `seu_nome-treinamento-github` e clique em **Create Branch**.

### Criar um arquivo de treinamento

1. No explorador de arquivos do seu sistema, navegue até a pasta do repositório clonado.
2. Crie o arquivo `OnBoarding/Essentials/github/treinamento.md`.

### Editar o arquivo de treinamento

Abra o arquivo `treinamento.md` no seu editor de texto favorito e adicione as seguintes informações:

```markdown
# TREINAMENTO
Olá ATOM! Este é o meu treinamento básico de Git e GitHub. Estou aprendendo a usar o Git para versionamento de código e colaboração em projetos.
```

### Adicionar e fazer commit das alterações

1. Volte ao GitHub Desktop.
2. Você verá o arquivo criado na lista de alterações.
3. Marque a caixa ao lado do arquivo para adicioná-lo ao commit.
4. No campo **Summary**, escreva: `Adiciona treinamento básico de Git e GitHub`.
5. Clique em **Commit to treinamento-github**.

### Enviar o branch para o repositório remoto

1. Clique em **Push origin** no topo da janela para enviar seu branch e commit para o GitHub.

### Criar um Pull Request

1. Após o push, o GitHub Desktop mostrará um botão para criar um Pull Request.
2. Clique em **Create Pull Request**.
3. No navegador, preencha o título e a descrição do Pull Request e envie.

## 2. Revisão do Pull Request

Peça a um mentor ou colega para revisar o seu Pull Request. Eles podem sugerir melhorias ou aprovar as suas alterações.

## 3. Merge do Pull Request

Após a aprovação, faça o merge do seu Pull Request no branch principal (`main` ou `master`) diretamente pelo GitHub.

## 4. Limpeza do Branch

Após o merge, exclua o branch de treinamento:

1. No GitHub Desktop, mude para o branch principal.
2. Clique em **Branch > Delete...** e selecione `treinamento-github`.
3. Clique em **Push origin** para atualizar o repositório remoto.

## 5. Conclusão

Parabéns! Você completou o treinamento básico de Git e GitHub usando o GitHub Desktop. Agora você está pronto para contribuir com os projetos do ATOM e continuar aprendendo mais sobre controle de versão e colaboração em equipe.
