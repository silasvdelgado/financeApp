# financeApp — Contexto do Projeto

## O que é
App de finanças domésticas em HTML/CSS/JS puro, hospedado no GitHub Pages.
URL: https://silasvdelgado.github.io/financeapp/
Repo: https://github.com/silasvdelgado/financeapp

## Stack
- Single HTML file (index.html)
- Vanilla JS, sem frameworks
- Chart.js para gráficos
- Dados salvos em localStorage
- Font: Outfit (Google Fonts)
- Tema escuro

## Abas
1. Visão Geral — resumo do mês, gráficos
2. Transações — lançamentos com filtros, edição e exclusão
3. Recorrentes — despesas/receitas fixas mensais com "Aplicar ao mês"
4. Orçamento — limites por categoria
5. Planejamento — projeção de 12 meses com gráfico e detalhamento

## Funcionalidades principais
- Lançamentos parcelados no cartão (cria N transações futuras)
- Edição/exclusão de parcelas individualmente ou em grupo
- Categorias customizáveis via Configurações (ícone de engrenagem)
- Modal de confirmação customizado (sem confirm() nativo)
- GitHub Pages atualiza automaticamente a cada git push

## Workflow Git
cd ~/Documents/financeApp
git add index.html
git commit -m "descrição"
git push