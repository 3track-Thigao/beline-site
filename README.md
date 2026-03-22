# BE.LINE — Site Oficial

> Alta costura feminina. Cada peça nasce uma vez.

Site institucional e e-commerce da **BE.LINE** — HTML/CSS/JS puro, sem dependências de frameworks. Design editorial inspirado em YSL, Jacquemus e The Row.

---

## Como usar

### Visualizar offline
Abra `src/index-standalone.html` diretamente no navegador.
Todas as imagens já estão embutidas no arquivo.

### Versão com fotos reais
1. Coloque as fotos das peças em `assets/images/`
2. Atualize os `src` das imagens em `src/index.html`
3. Abra via servidor local ou faça deploy

### Deploy no Netlify (grátis)
1. Acesse [netlify.com/drop](https://netlify.com/drop)
2. Arraste a pasta `beline-final`
3. Receba um link público em segundos

---

## Estrutura

```
beline-final/
├── src/
│   ├── index.html              ← versão para desenvolvimento (fotos via assets/)
│   └── index-standalone.html  ← versão offline (fotos embutidas)
├── assets/
│   └── images/                ← colocar fotos das peças aqui
├── docs/
│   └── STYLE-GUIDE.md         ← guia de identidade visual
└── README.md
```

---

## Identidade visual

| Cor | Hex | Uso |
|-----|-----|-----|
| Carmim | `#8C0502` | Cor primária — textos em fundo branco |
| Rubro | `#680A08` | Variação escura |
| Ébano | `#0d0d0d` | Fundo seções escuras |
| Algodão | `#ffffff` | Textos em fundo escuro |
| Ouro | `#9D753E` | Destaques, badges, preços |

**Tipografia:** Cormorant Garamond (títulos) + Saira (logo/labels) + Poppins (corpo)

**Regra:** Fundo branco → Carmim + Ouro · Fundo preto → Algodão + Ouro

---

## Páginas implementadas

- [x] Home completa (desktop + mobile)
- [x] Menu hambúrguer mobile
- [x] Seção coleção com grid editorial
- [x] Manifesto com 4 pilares
- [x] Arquivo de coleções passadas
- [x] Formulário lista VIP
- [ ] Página de produto individual *(próxima entrega)*
- [ ] Página de coleção completa
- [ ] Página Sobre

---

## Próximos passos técnicos

1. Abrir CNPJ (antes do gateway de pagamento)
2. Lista VIP com Klaviyo (grátis até 250 contatos)
3. Instagram com 3 posts/semana (bastidores)
4. Quando as peças estiverem prontas → Shopify + Pagar.me + fotos reais
5. Mês 3+ → Meta Ads remarketing

---

*Desenvolvido com Claude AI como parceiro de tecnologia da marca.*
