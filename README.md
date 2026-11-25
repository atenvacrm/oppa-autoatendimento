# Oppa Sushi & BBQ — Autoatendimento

Sistema demonstrativo completo do Oppa, com cardápio fotográfico, busca, personalização, carrinho, revisão, pagamento simulado e notinha.

## Continuar em outro chat

Conecte o GitHub da conta `atenvacrm` e informe este repositório: **atenvacrm/oppa-autoatendimento**. Leia o conteúdo atual da branch `main` antes de editar. O projeto inteiro está aqui, incluindo imagens e fontes. As alterações devem ser salvas em commits.

## Executar

Site estático, sem dependências ou compilação:

```bash
python3 -m http.server 8080
```

Abra http://localhost:8080.

## Arquivos

| Arquivo | Função |
| --- | --- |
| `index.html` | Estrutura das telas |
| `app.js` | Fluxos, busca, personalização e carrinho |
| `menu-data.js` | Categorias, pratos e preços |
| `styles.css` | Layout, animações e responsividade |
| `brand.css` | Identidade visual do Oppa |
| `assets/` | Fotografias, fundos e fontes |

## Identidade

Impact nos títulos; Arial Black nos pratos e preços; Inter nos textos e interface. Paleta: #171917, #F4F0E7, #354437, #BC995B e #C92A2D.

## Publicação

Este projeto pode ser hospedado em qualquer servidor estático. A publicação original no ChatGPT Sites é independente: editar o GitHub não modifica automaticamente aquela publicação. Use a hospedagem conectada a este repositório para atualização após cada push.

## Demonstração

Não cobra valores nem envia pedidos à cozinha. O carrinho usa `sessionStorage`. Fotos, valores e disponibilidade devem ser confirmados com o restaurante. Marca, fotografias e fontes pertencem aos respectivos titulares.
