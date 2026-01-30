# 🧮 Calculadora em React (CDN) + TailwindCSS

Este projeto é uma calculadora web desenvolvida com **React** e **TailwindCSS**, utilizando apenas CDN (sem build tools ou bundlers como Vite/Webpack).

Foi criado como exercício de aprendizado seguindo os fundamentos ensinados pela Rocketseat.

## 🚀 Funcionalidades

- Operações básicas: soma, subtração, multiplicação e divisão
- Suporte a números decimais (vírgula)
- Botões:
  - `C` limpa tudo
  - `CE` apaga o último caractere
  - `=` calcula o resultado
- Histórico de operações salvo no **localStorage**
- Botão para limpar o histórico
- Interface estilizada com TailwindCSS e variáveis CSS customizadas

## 🧠 Conceitos praticados

- Componentização com React
- Criação de componentes reutilizáveis (`Text`, `Button`, `Card`)
- Uso de **Context API** para compartilhar o histórico
- Criação de **Custom Hook** (`useCalculator`) para encapsular a lógica da calculadora
- Manipulação de estado com `useState`
- Efeitos colaterais com `useEffect`
- Persistência de dados com `localStorage`
- Renderização de listas e eventos de clique

## 📂 Estrutura

Tudo está em um único arquivo `index.html`, contendo:

- Importação de:
  - React e ReactDOM via CDN
  - Babel para interpretar JSX no navegador
  - TailwindCSS via CDN
- Componentes React
- Contexto global da calculadora
- Hook customizado com as regras das operações
- Renderização principal do `<App />`

## ▶️ Como executar

1. Salve o código em um arquivo chamado, por exemplo:

```bash
index.html
Abra esse arquivo diretamente no navegador (duplo clique). Não é necessário instalar dependências nem rodar servidor.

## 💾 Histórico de operações

As operações realizadas ficam salvas no navegador usando localStorage. Mesmo recarregando a página, o histórico continua lá até você clicar em “Apagar Histórico”.

## 🎨 Estilo

-Fonte: Rubik (Google Fonts
-Cores e sombras definidas em variáveis CSS (:root)
-Layout responsivo usando TailwindCSS

## 📚 Aprendizado

-Projeto desenvolvido para praticar fundamentos de:
-React sem ferramentas de build
-Organização de lógica em hooks e contextos
-Boas práticas de componentização

Baseado nos ensinamentos da Rocketseat.
