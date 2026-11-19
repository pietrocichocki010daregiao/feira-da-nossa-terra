# Feira da Nossa Terra — Santa Izabel do Oeste e região

Projeto acadêmico para a atividade **Estilização com Flexbox**, do curso Técnico em Informática.

## 1. Problema identificado
Moradores podem ter dificuldade para descobrir quais alimentos são produzidos na região, conhecer pequenos produtores e encontrar informações sobre a feira alimentar. Ao mesmo tempo, produtores locais precisam de mais espaços para divulgar seu trabalho.

## 2. Solução proposta
Um site informativo que apresenta categorias de produtos, explica a importância da agricultura familiar e oferece um formulário demonstrativo para manifestar interesse em participar ou divulgar produtos.

> Os produtos e categorias exibidos são exemplos ilustrativos. Antes de apresentar o site como serviço oficial, devem ser confirmados os feirantes, produtos, endereço, dias e horários reais.

## 3. Tecnologias e requisitos
- **HTML5:** estrutura semântica com `header`, `nav`, `main`, `section`, `article`, `form` e `footer`.
- **CSS3:** cores, espaçamentos, tipografia, cartões e estados de interação.
- **Flexbox:** organização da navegação, seção inicial, benefícios, cartões, conteúdo e rodapé.
- **Media Queries:** adaptação para telas menores (760px e 420px).
- **Sem JavaScript:** o projeto foi feito somente com HTML e CSS, conforme o conteúdo estudado em aula.

## 4. Como executar
1. Extraia os arquivos.
2. Abra a pasta no Visual Studio Code.
3. Abra `index.html` no navegador. Também é possível usar a extensão Live Server.

## 5. Publicação
### GitHub
Crie um repositório chamado `feira-da-nossa-terra`. No terminal, dentro da pasta do projeto:

```bash
git init
git add .
git commit -m "Cria site Feira da Nossa Terra"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/feira-da-nossa-terra.git
git push -u origin main
```

### Vercel
1. Entre em https://vercel.com/ e conecte sua conta GitHub.
2. Escolha **Add New → Project**.
3. Importe o repositório `feira-da-nossa-terra`.
4. Como é um site estático, não precisa configurar framework ou comando de build.
5. Clique em **Deploy** e copie a URL pública gerada.

## 6. Roteiro para apresentação
1. **Tema:** Feira da Nossa Terra — Santa Izabel do Oeste e região.
2. **Demanda:** facilitar a divulgação dos alimentos e dos produtores locais.
3. **Solução:** site com apresentação da proposta, categorias de produtos, valorização dos produtores e formulário demonstrativo.
4. **HTML:** explicar a organização semântica das seções e os campos do formulário.
5. **CSS/Flexbox:** mostrar como `display: flex`, `justify-content`, `align-items`, `gap` e `flex-wrap` organizam os elementos.
6. **Responsividade:** redimensionar o navegador e mostrar as Media Queries.
7. **Demonstração:** navegar pelo site e mostrar o formulário. Ele é demonstrativo e ainda não envia mensagens.
8. **Publicação:** apresentar os links do GitHub e da Vercel depois de realizar o deploy.

## 7. Melhorias futuras
- Cadastrar produtores reais com autorização.
- Informar endereço, dias e horários confirmados da feira.
- Adicionar fotos reais e lista atualizada de produtos.
- Conectar o formulário a um serviço de recebimento de mensagens, se isso for estudado posteriormente.
