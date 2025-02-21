# Moments

Este projeto foi gerado com [Angular CLI](https://github.com/angular/angular-cli) versão 13.3.11.

## Descrição do Projeto

O projeto "Moments" é uma aplicação web desenvolvida em Angular que permite aos usuários criar, visualizar, atualizar e deletar momentos. Cada momento pode conter uma descrição, uma imagem e comentários de outros usuários.

## Páginas Desenvolvidas

### Home

- **Descrição**: Página inicial da aplicação que lista todos os momentos criados.
- **URL**: `/`
- **Componentes**: `HomeComponent`

### Criar Momento

- **Descrição**: Página para criar um novo momento.
- **URL**: `/moments/new`
- **Componentes**: `NewMomentComponent`

### Detalhes do Momento

- **Descrição**: Página que exibe os detalhes de um momento específico, incluindo a descrição, imagem e comentários.
- **URL**: `/moments/:id`
- **Componentes**: `MomentDetailComponent`

### Editar Momento

- **Descrição**: Página para editar um momento existente.
- **URL**: `/moments/edit/:id`
- **Componentes**: `EditMomentComponent`

## Funcionalidades Implementadas

- **CRUD de Momentos**: Permite criar, visualizar, atualizar e deletar momentos.
- **Comentários**: Usuários podem adicionar comentários aos momentos.
- **Upload de Imagens**: Suporte para upload de imagens ao criar ou editar momentos.

## Estrutura do Projeto

- **src/app/components**: Contém os componentes relacionados aos momentos.
- **src/app/services**: Contém os serviços que fazem a comunicação com a API.
- **src/app**: Contém os modelos de dados utilizados na aplicação.
