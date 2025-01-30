# Conversor de Moedas - Giphy App

Este projeto Flutter permite buscar e exibir GIFs da API do Giphy. O usuário pode visualizar GIFs em tendência e pesquisar novos GIFs através de um campo de pesquisa.

## 📌 Funcionalidades
- Exibe GIFs populares da API do Giphy.
- Permite pesquisa de GIFs pelo nome.
- Mostra os resultados em um layout responsivo em grade.

## 🛠 Tecnologias Utilizadas
- **Flutter**: SDK para desenvolvimento de aplicativos multiplataforma.
- **Dart**: Linguagem de programação usada no Flutter.
- **HTTP**: Biblioteca para fazer requisições à API do Giphy.
- **Giphy API**: Fonte de GIFs animados.

## 📦 Dependências
```yaml
dependencies:
  flutter:
    sdk: flutter
  http: ^1.2.2
```

## 🚀 Como Rodar o Projeto
1. **Clone o repositório**
   ```sh
   git clone https://github.com/seu-usuario/buscador_de_gifs.git
   cd conversor_de_moedas
   ```
2. **Instale as dependências**
   ```sh
   flutter pub get
   ```
3. **Execute o projeto**
   ```sh
   flutter run
   ```

## 🖼️ Estrutura do Projeto
```
/lib
  ├── main.dart            # Arquivo principal do aplicativo
  ├── home_page.dart       # Tela principal com a busca de GIFs
  ├── widgets/
      ├── gif_grid.dart    # Widget responsável pela exibição dos GIFs
```

## 🔑 Chave da API
O projeto utiliza a chave de API do Giphy. Para alterar a chave, edite as URLs nas requisições HTTP dentro do arquivo `home_page.dart`.

## 📄 Licença
Este projeto está licenciado sob a [MIT License](LICENSE).
