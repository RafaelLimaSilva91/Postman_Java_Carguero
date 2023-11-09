# 🚀 Projeto de Automação de Teste Carguero.

Este projeto é sobre a automação de teste de API dos metodos GET e POST, utilizando Javascript, Postman e Newman.

### API: http://jsonplaceholder.typicode.com/posts

## 🛠️ Ferramentas utilizadas para execução dos testes e gerar o relatório com os resultados dos testes.

- [Node.js](https://nodejs.org/): Plataforma para executar JavaScript.
- [Postman](https://www.postman.com/downloads/): Ferramenta para automatizar, executar e documentar os testes de APIs.
- [Newman](https://www.npmjs.com/package/newman-reporter-htmlextra): Ferramenta para executar os testes e gerar relatório.

## 📦 Instalação do Projeto.

1. Instale o Node.js (LTS - Recommended For Users) e verifique se foi instalado com sucesso, acessando o terminal e consultado.

      ```bash
   node -v
   ```

2. Clone este repositório:

   ```bash
   git clone https://github.com/RafaelLimaSilva91/Postman_Java_Carguero.git
   ```
   
3. Abra o terminal e acesse a pasta do projeto:
   
   ```bash
   cd Postman_Java_Carguero
   ```

4. Instale o Newman:

   ```bash
   npm install -g newman
   ```

5. Instale o plugin do Newman para gerar o relatorio em html:
   
   ```bash
   npm install -g newman-reporter-htmlextra
   ```

## 🚀 Execução do testes e gerando o relatório html

1. Acesse a pasta do projeto e abra o Terminal.

2. Execute o comando a seguir para executar os testes e gerar o relatório em html:

 ```bash
newman run "Teste Carguero.postman_collection.json" -r htmlextra
```

## Observação: 

O relatório será gerado e estará disponível na pasta newman.

