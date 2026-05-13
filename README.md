# Dashboard Financeiro - RachaAí

Projeto desenvolvido em Blazor para a disciplina de IHC e UX.

## Objetivo

Criar uma dashboard financeira utilizando:

- Hierarquia visual
- Componentização
- Bootstrap
- Heurísticas de UX

## Tecnologias

- Blazor Server
- C#
- Bootstrap
- .NET

## Estrutura

- Models/Grupo.cs
- Shared/GrupoCard.razor
- Pages/Dashboard.razor

## Funcionalidades

- Cards de resumo financeiro
- Lista de grupos
- Indicação visual de crédito/débito
- Responsividade
- Tratamento de lista vazia

## Conceitos de IHC aplicados

### Hierarquia Visual
Os cards superiores possuem maior destaque visual.

### Feedback Visual
Cores verdes e vermelhas ajudam o usuário a entender rapidamente a situação financeira.

### Componentização
O componente GrupoCard foi criado para reutilização de interface.

### Responsividade
Uso do sistema de grid do Bootstrap.

## Dificuldades encontradas

A principal dificuldade foi entender a componentização no Blazor e o uso de parâmetros entre componentes.
