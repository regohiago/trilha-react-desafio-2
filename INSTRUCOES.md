# Trilha React - Desafio 2

## Passo a passo para testar o projeto

1. **Entre na pasta do projeto:**
   ```bash
   cd trilha-react-desafio-2
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Inicie o servidor de desenvolvimento:**
   ```bash
   npm start
   ```

4. **Acesse a aplicação:**
   - O navegador deve abrir automaticamente em `http://localhost:3000`
   - Ou acesse manualmente o endereço acima

5. **Como testar a funcionalidade:**
   - Digite um usuário/repositório no formato `usuario/repositorio` (ex: `facebook/react`)
   - Clique em **Adicionar**
   - O repositório será listado na tela
   - Clique em **Remover** para excluir um repositório da lista

6. **Rodar os testes automatizados (opcional):**
   ```bash
   npm test
   ```

---

## Passo a passo para fazer commit no seu repositório

1. **Verifique o status dos arquivos:**
   ```bash
   git status
   ```

2. **Adicione os arquivos ao stage:**
   ```bash
   git add .
   ```
   Ou para um arquivo específico:
   ```bash
   git add caminho/do/arquivo
   ```

3. **Faça o commit com uma mensagem descritiva:**
   ```bash
   git commit -m "Sua mensagem descrevendo a alteração"
   ```
   Exemplo:
   ```bash
   git commit -m "Implementa botão remover com filter"
   ```

4. **Envie para o GitHub:**
   ```bash
   git push -u origin master
   ```
   Se preferir usar a branch `main`:
   ```bash
   git branch -M main
   git push -u origin main
   ```

5. **Para commits futuros** (após o primeiro push):
   ```bash
   git add .
   git commit -m "Descrição da alteração"
   git push
   ```

### Configuração inicial do remote (se necessário)

Se o `origin` apontar para outro repositório, altere para o seu:

```bash
git remote set-url origin https://github.com/regohiago/trilha-react-desafio-2.git
```
