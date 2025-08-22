# Flutter Confeitaria App

Bem-vindo ao **Flutter Confeitaria App**, um projeto criado com Flutter para demonstrar a criação de UI moderna e prática, utilizando conceitos de gerenciamento de estado e design dinâmico. Este README tem como objetivo oferecer uma visão geral do que foi desenvolvido neste projeto, além de listar as principais dependências utilizadas.

---

## 🛠️ O que foi feito?

O projeto consiste em uma implementação de uma aplicação de restaurante simplificada, que permite aos usuários visualizar detalhes de um restaurante, seu menu de pratos populares e adicionar itens à sacola de compras. Abaixo está uma explicação detalhada sobre os componentes principais do projeto:

### **Principais funcionalidades:**

1. **Tela de Restaurante**:
    - Exibe informações básicas sobre um restaurante, como o nome e uma imagem do restaurante.
    - Lista os pratos mais pedidos, permitindo aos usuários adicionarem os itens do menu à sacola de pedidos.

2. **Gerenciamento de Estado**:
    - Foi utilizado o **Provider**, uma biblioteca de gerenciamento de estado, para armazenar e manipular o estado dos itens na sacola de compras.

3. **Componentes reutilizáveis**:
    - Uma barra de ferramentas personalizada (_AppBar_) foi criada para melhorar a consistência e a reutilização do código em várias telas.

4. **Imagens e navegação**:
    - Utilização de imagens locais para exibição dos itens, como a imagem do restaurante e os pratos populares na tela.

---

## 📦 Dependências principais

O projeto utiliza as seguintes dependências para viabilizar sua execução:

1. **Flutter SDK**:
    - Framework base para o desenvolvimento do aplicativo.
    - Criação de interfaces responsivas e nativas para plataformas Android e iOS.

   ```yaml
   flutter: 3.29.3
   ```

2. **Provider**:
    - Gerenciamento de estado leve e eficiente.
    - Utilizada para gerenciar a lógica da sacola de compras.

   ```yaml
   provider: ^6.0.5
   ```

3. **Material Design**:
    - Utilização dos widgets padrões do Flutter para construir uma interface moderna e elegante, utilizando o design system do Material Design.

4. **Assets (Imagens)**:
    - Imagens de pratos e restaurantes foram organizadas na pasta `assets/`, permitindo que sejam carregadas dinamicamente na interface.

---

## 📂 Estrutura de Pastas

A estrutura de diretórios do projeto foi organizada em camadas para facilitar a manutenção e escalabilidade:

- **model/**: Contém os modelos de dados (ex.: `Dish` e `Restaurant`).
- **ui/**: Reúne toda a lógica e organização das telas do aplicativo.
    - **_core/**: Contém widgets e provedores reutilizáveis, como a AppBar personalizada e o `BagProvider`.

---

## 🚀 Como rodar o projeto?

Certifique-se de que possui o Flutter instalado em sua máquina. Se necessário, siga o [guia de instalação oficial](https://flutter.dev/docs/get-started/install).

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-repositorio/flutter-tech-taste.git
   cd flutter-tech-taste
   ```

2. Baixe as dependências do projeto:
   ```bash
   flutter pub get
   ```

3. Execute o aplicativo:
   ```bash
   flutter run
   ```

---

## 🧑‍💻 Contribuições

Sinta-se à vontade para contribuir com este projeto, seja corrigindo bugs, adicionando novas funcionalidades ou melhorando a documentação. Feedbacks e sugestões são sempre bem-vindos!

1. Faça um **fork** do projeto.
2. Crie uma nova branch para suas alterações:
   ```bash
   git checkout -b minha-feature
   ```
3. Submeta um **pull request** após testar suas alterações.

---

## 🧰 Recursos futuros

- Implementação de navegação entre múltiplas telas.
- Persistência de dados em um banco local utilizando sqlite ou hive.
- Sistema de autenticação e login para usuários.

---

## 📝 Licença

Este projeto é distribuído sob a licença MIT. Sinta-se livre para usá-lo da maneira que preferir. ❤️

---

Obrigado por explorar o **Flutter Confeitaria App**! Se tiver dúvidas ou sugestões, entre em contato. 😊
