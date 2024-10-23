
Resumo do Git

#### Iniciando um Repositório:
1. **Criar o Repositório Localmente**:
   git init
   > Nota: Antes de executar o `git init`, crie o repositório manualmente no GitHub.

2. **Adicionar Arquivos**:
   - Para adicionar todos os arquivos:
     git add .
   - Para adicionar um arquivo específico (ex: `test.txt`):
     git add test.txt

3. **Comitar as Alterações**:
   git commit -m "meu commit"

4. **Conectar ao Repositório Remoto**:
   git remote add origin <URL_DO_GITHUB>

5. **Subir as Alterações para o GitHub**:
   git push -u origin main
   > O `-u` define `origin main` como a upstream para o seu branch local.

#### Iniciando uma Branch:
1. **Criar e Mudar para uma Nova Branch**:
   git checkout -b "nome_da_branch"

2. **Adicionar Arquivos**:
   - Para adicionar todos os arquivos:
     git add .
   - Para adicionar um arquivo específico (ex: `test.txt`):
     git add test.txt

3. **Comitar as Alterações**:
   git commit -m "meu commit"

4. **Subir a Nova Branch para o GitHub**:
   git push origin "nome_da_branch"

5. **Mesclar a Branch com a Master (ou Main)**:
   - Primeiro, mude para a branch `main` ou `master`:
     git checkout main
   - Em seguida, mescle a branch:
     git merge nome_da_branch

### Observações
- **Pull Requests**: Se estiver colaborando, considere criar um Pull Request no GitHub para revisar e mesclar suas alterações.
- **Conflitos**: Durante a mesclagem, você pode encontrar conflitos que precisarão ser resolvidos manualmente.
