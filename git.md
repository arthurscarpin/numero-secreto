# Dicas de comandos GIT

Esse modelo tem como objetivo documentar comandos do Git afim de estudos.

## Comando: `git log`
**Descrição:** Visualização padrão do histórico de commits.

---

## Comando: `git log --oneline`
**Descrição:** Visualização sucinta do histórico de commits.

---

## Comando: `git log -p`
**Descrição:** Visualização detalhada do histórico de commits.

---

## Comando: `git log --graph`
**Descrição:** Visualização do histórico de commits em forma de grafo que demonstra as ramificações dos commits, util quando trabalhamos com Branches.

---

## Comando: `git log --pretty` ou `git log --format`
**Descrição:** Visualização do histórico de commits em um formato customizável de acordo com as preferências do usuário.

---

## Comando: `git <comando> --help`
**Descrição:** Comando de ajuda que abre um manual para execução de cada comando GIT.

---

## Comando: `git show <HASH>`
**Descrição:** Visualizar a alteração que o commit especificado pelo HASH fez, se um HASH não for passado será mostrado as alterações do último commit indicado pelo ponteiro HEAD.

---

## Comando: `git status`
**Descrição:** Visualizar qual branch estamos e se há algo para ser adicionado ao Stage Area para seguir com o commit.

---

## Comando: `git diff`
**Descrição:** Mostra a diferença entre dois estados, o que temos modificado sem termos adicionado para commitar e o nosso HEAD.

---

## Comando: `git diff <HASH 1>..<HASH 2>`
**Descrição:** Mostra a diferença entre dois commits, o primeiro é o mais antigo e o segundo o mais novo.

---

## Comando: `git branch`
**Descrição:** Visualiza todas as ramificações (Branches) da minha árvore de trabalho.

---

## Comando: `git branch -m <Nome antigo da Branch> <Novo nome da Branch>`
**Descrição:** Comando para renomear uma branch já existente.

---

## Comando: `git branch -d <Branch>`
**Descrição:** Comando para deletar uma branch específica. 

**Obs:** Não é possível deletar a branch atual no qual o ponteiro HEAD se encontra.

---

## Comando: `git branch <Branch>`
**Descrição:** Comando para criar uma nova branch. 

**Obs:** Esse comando apenas cria a nova branch mas não muda o ponteiro HEAD para ela.
---

## Comando: `git checkout <Branch>` (Antigo) ou `git switch <Branch>` (Novo)
**Descrição:** Comando para mudar para a branch especificada.

---

## Comando: `git checkout -b <Branch>` (Antigo) ou `git switch - c <Branch>` (Novo)
**Descrição:** Comando para criar uma Branch e já mover para ela.

---