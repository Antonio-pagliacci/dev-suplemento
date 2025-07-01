# DevSuplementos

DevSuplementos é uma loja online de suplementos voltada para profissionais de tecnologia e atletas que buscam performance com qualidade. Este projeto inclui páginas de apresentação, contato, lista de produtos e um carrinho de compras simples com persistência no `localStorage`.

---

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5
- FontAwesome

---

## Funcionalidades

- Navegação entre páginas (Home, Sobre, Contato, Meu Carrinho)
- Formulário de contato com integração para busca de endereço via CEP (usando API ViaCEP)
- Lista dinâmica de produtos com opção de adicionar ao carrinho
- Carrinho de compras que salva dados no `localStorage`
- Remoção de itens do carrinho
- Total do carrinho calculado dinamicamente
- Layout responsivo com Bootstrap

---

## Estrutura do Projeto

```
/assets
    /img          # Imagens do projeto (logo, produtos, etc)
/js
    main.js       # Scripts JS principais, incluindo manipulação do carrinho e busca de CEP
/styles
    style.css     # Estilos gerais e específicos das páginas
index.html        # Página principal
sobre.html        # Página Sobre Nós
contato.html      # Página Contato com formulário e busca CEP
carrinho.html     # Página do carrinho de compras
README.md         # Documentação do projeto
```

---

## Como usar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/devsuplementos.git
```

2. Abra o arquivo `index.html` no navegador para navegar pelo site.

3. Na página de produtos, clique em "Adicionar ao Carrinho" para adicionar itens.

4. Acesse "Meu Carrinho" para visualizar os itens adicionados, remover itens ou finalizar a compra.

5. Na página de contato, insira seu CEP para que os campos de endereço sejam preenchidos automaticamente.

---

## Personalizações

- Atualize o arquivo `produtos` no JavaScript para alterar a lista de suplementos.
- Adapte o estilo no CSS conforme sua identidade visual.
- Amplie as funcionalidades do carrinho para incluir quantidade, pagamento, etc.

---

## Contato

DevSuplementos - Turbinando seu corpo e mente para alta performance!

- Email: contato@devsuplementos.com
- Telefone: (21) 99999-9999
- Redes sociais: Instagram, Facebook, WhatsApp (links na página)

---

## Licença

Este projeto está sob a licença MIT.

---

**Desenvolvido por [Seu Nome]**
