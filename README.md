# 📊 Budget Tracker — Controle de Gastos Pessoais

Uma planilha interativa de controle financeiro pessoal, desenvolvida com HTML, CSS e JavaScript puro. Funciona direto no navegador, sem precisar instalar nada.

---

## ✨ Funcionalidades

- 📅 Lançamento de receitas e despesas por mês
- 💾 Dados salvos automaticamente no navegador (localStorage)
- ✏️ Campos totalmente editáveis — renomeie, adicione ou exclua categorias
- 📥 Exportação para Excel (.xlsx) com aba por mês e resumo anual
- 💡 Sugestão automática de investimento com base no saldo do mês
- 🗂️ Histórico anual com total de receitas, despesas e saldo
- 📱 Responsivo — funciona no celular e no computador

---

## 🚀 Como usar

### Opção 1 — Pelo navegador (GitHub Pages)
Acesse o link abaixo e use diretamente no navegador:

```
https://SEU_USUARIO.github.io/budget-tracker
```

> Substitua `SEU_USUARIO` pelo seu nome de usuário do GitHub.

### Opção 2 — Localmente
1. Faça o download do arquivo `index.html`
2. Abra o arquivo em qualquer navegador (Chrome, Firefox, Edge)
3. Pronto — nenhuma instalação necessária!

---

## 📋 Categorias de Despesas (padrão)

| # | Categoria |
|---|-----------|
| 1 | 💳 Cartão de Crédito |
| 2 | 🏠 Prestação da Casa |
| 3 | 💧 Água |
| 4 | ⚡ Luz |
| 5 | 🌐 Internet |
| 6 | 📱 Telefone |
| 7 | 🔥 Gás |
| 8 | 🏡 IPTU |
| 9 | 🫧 PIX |
| 10 | ⛽ Combustível |
| 11 | 🛒 Mercado |
| 12 | 🎓 Faculdade |

> Todas as categorias podem ser renomeadas, reordenadas ou excluídas pelo botão **✏️ Editar Campos**.

---

## 💡 Sugestão de Investimento

A planilha analisa o saldo do mês e sugere automaticamente onde investir:

| Saldo | Sugestão |
|-------|----------|
| Negativo | ⚠️ Revisar gastos |
| Até R$ 199 | 🐷 Poupança ou CDB |
| R$ 200 – R$ 999 | 💰 Tesouro Selic ou CDB |
| R$ 1.000 – R$ 2.999 | 📈 Diversificação (renda fixa + fundos) |
| Acima de R$ 3.000 | 🚀 Carteira completa (ações, FIIs, renda fixa) |

---

## ⚠️ Sobre os dados salvos

Os dados ficam armazenados no **localStorage** do seu navegador. Isso significa:

- ✅ Os dados permanecem mesmo após fechar o navegador
- ❌ Não sincronizam entre dispositivos diferentes
- 💡 **Recomendado:** use o botão **📥 Baixar Excel** mensalmente para fazer backup

---

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- [SheetJS (xlsx)](https://sheetjs.com/) — exportação para Excel

---

## 📄 Licença

Este projeto é de uso livre e pessoal.

---

Desenvolvido com 💙 para facilitar o controle financeiro do dia a dia.
