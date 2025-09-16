# 🏢 Conference Event Planner - BudgetEase ---> link do projeto: https://douglas-pedroso.github.io/conference_event_planner/

Este projeto foi desenvolvido como parte de um laboratório prático para criar um **Planejador de Despesas de Conferência** para a empresa fictícia **BudgetEase**.  

O sistema permite que clientes calculem facilmente os custos de eventos em um centro de conferências, escolhendo salas, equipamentos adicionais e refeições para os convidados.  

---

## 🛠️ Funcionalidades

✔️ Interface de usuário dinâmica que se atualiza em tempo real  
✔️ Componentes React para seleção de salas, complementos e refeições  
✔️ Gerenciamento de estado com **Redux Toolkit**  
✔️ Fatias Redux (`slices`) para diferentes partes da aplicação  
✔️ Renderização dinâmica de dados a partir de arrays de objetos  
✔️ Tabela em janela pop-up mostrando itens escolhidos, preços unitários e totais  
✔️ Cálculo de subtotais e valor total com base nas escolhas do usuário  
✔️ Deploy via **GitHub Pages**  

---

## 🎓 Objetivos de aprendizado

Durante este projeto, aprendi a:

- **Criar componentes React** reutilizáveis usando composição e aninhamento  
- **Gerenciar estados com hooks**: `useState` e `useEffect`  
- **Integrar Redux** em uma aplicação React (ações, reducers, store)  
- **Criar slices no Redux Toolkit** para modularizar o estado da aplicação  
- **Renderizar dados dinamicamente** a partir de arrays de objetos  
- **Lidar com eventos** do usuário e aplicar renderização condicional  
- **Criar uma tabela dinâmica** para exibir dados calculados  
- **Publicar uma aplicação React com Vite** no GitHub Pages  

---

## 📂 Estrutura do projeto

- `src/components` → componentes React (salas, opções extras, refeições, tabela de custos)  
- `src/store.js` → configuração da store do Redux  
- `src/*Slice.js` → fatias do Redux para cada parte do estado (ex.: refeições, extras)  
- `vite.config.js` → configuração do build e deploy no GitHub Pages  

---

## 📋 Tarefas concluídas

- [x] Configurar o ambiente do projeto (React + Vite + Redux)  
- [x] Revisar e organizar a estrutura do componente `ConferenceEvent.jsx`  
- [x] Implementar Redux Toolkit para estados globais  
- [x] Criar lógica para cálculo de subtotais e custo total  
- [x] Criar tabela dinâmica para mostrar os itens escolhidos  
- [x] Aplicar design web responsivo para melhor UX  
- [x] Implantar no GitHub Pages  

---

## 🚀 Deploy

O projeto está disponível no GitHub Pages:  
👉 [Conference Event Planner](https://Douglas-Pedroso.github.io/conference_event_planner)

---

## 🧑‍💻 Pré-requisitos para rodar localmente

- Conhecimento básico de **HTML e CSS**  
- JavaScript intermediário  
- Familiaridade com **React, Hooks e Redux Toolkit**  
- Git e GitHub para versionamento de código  

---

## ⚙️ Como rodar localmente

```bash
# Clonar o repositório
git clone https://github.com/Douglas-Pedroso/conference_event_planner.git

# Entrar na pasta
cd conference_event_planner

# Instalar dependências
npm install

# Rodar em ambiente de desenvolvimento
npm run dev

# Build para produção
npm run build

# Preview do build
npm run preview
