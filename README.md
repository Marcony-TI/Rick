# 📱 Rick & Morty Characters List

Aplicativo desenvolvido em **React Native com Expo**, consumindo a API pública "Rick and Morty API" para exibir uma lista de personagens.

Este projeto foi feito para fins acadêmicos, seguindo os requisitos de:

* Uso de **useState**
* Uso de **useEffect**
* Uso de **FlatList**
* Consumo de API real
* Renderização em forma de cards com imagem e informações

---

# 🚀 Como rodar o projeto

Siga os passos abaixo para executar o aplicativo no seu dispositivo ou emulador.

## 1️⃣ Pré-requisitos

Certifique-se de ter instalado:

* **Node.js** (versão atual recomendada)
* **Expo CLI** (instalado automaticamente ao usar create-expo-app)
* **Expo Go** (caso queira testar no celular Android/iOS)

## 2️⃣ Criar ou entrar no projeto

Se você já criou o projeto, entre na pasta:

```bash
cd meuApp
```

Caso ainda não tenha criado:

```bash
npx create-expo-app meuApp --template blank
cd meuApp
```

## 3️⃣ Instalar dependências (caso necessário)

Normalmente já vêm instaladas, mas você pode garantir com:

```bash
npm install
```

## 4️⃣ Rodar o app

Execute o projeto:

```bash
npx expo start
```

O Expo abrirá no navegador. Agora você pode:

* Ler o QR Code com **Expo Go** (Android/iPhone)
* Apertar **a** para abrir no emulador Android
* Apertar **w** para abrir no navegador

---

# 📡 O que foi implementado

## ✔ Consumo de API Real

O app faz requisição para:

```
https://rickandmortyapi.com/api/character
```

Essa rota retorna:

* id
* name
* status
* species
* image

## ✔ Estados e Ciclo de Vida

* `useState` para armazenar os personagens
* `useEffect` para buscar dados ao montar a tela

## ✔ Renderização com FlatList

A lista de personagens é exibida usando:

* `FlatList`
* `keyExtractor` baseado no `id`
* Renderização em **cards** estilizados

## ✔ Layout básico atendendo aos requisitos

Cada card exibe:

* Imagem do personagem
* Nome
* Status (Alive / Dead / Unknown)
* Espécie
* ID

Com borda, padding, espaçamento e organização simples.

---

# 📂 Estrutura básica do arquivo App.js

O arquivo contém:

* busca da API com fetch
* armazenamento no estado
* listagem com FlatList
* estilos básicos com StyleSheet

*(O arquivo completo está no projeto e já preparado para rodar.)*

---

# 📌 Observações finais

Este projeto é uma **primeira versão simplificada**, focada apenas nos requisitos obrigatórios.
Pode ser expandido futuramente com:

* Paginação
* Tela de detalhes
* Busca por pers

