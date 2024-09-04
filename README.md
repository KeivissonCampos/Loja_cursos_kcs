# Projeto KCS Cursos

Bem-vindo ao repositório do projeto **KCS Cursos**! Este projeto é uma página de apresentação para um site de cursos, utilizando o framework Bootstrap para estilização e layout.

## Tecnologias Utilizadas

- **HTML**: Linguagem de marcação usada para estruturar o conteúdo da página.
- **CSS**: Estilos básicos adicionados diretamente no HTML para personalização.
- **Bootstrap**: Framework CSS popular para desenvolvimento web responsivo e moderno.
- **jQuery**: Biblioteca JavaScript utilizada para simplificar interações com a DOM, eventos e manipulação de elementos.

## Como Utilizar

### 1. Configuração do Ambiente

Certifique-se de ter um editor de código, como [Visual Studio Code](https://code.visualstudio.com/), instalado em seu computador.

### 2. Estrutura do Projeto

O projeto inclui os seguintes arquivos principais:

- `index.html`: O arquivo HTML principal que contém a estrutura da página.
- `bootstrap.min.css`: Arquivo CSS do Bootstrap incluído diretamente do CDN.
- `bootstrap.min.js`: Bootstrap incluído diretamente do CDN.
- `main.css`: Arquivo CSS para estilos personalizados (se necessário).
- `jquery.min.js`: Arquivo da biblioteca jQuery incluído diretamente do CDN.
- `validation.js`: Arquivo JavaScript para validação de formulários utilizando jQuery.

### 3. Inclusão do Bootstrap e jQuery

O Bootstrap e o jQuery são incluídos na página através de links para os respectivos CDNs no `<head>` do arquivo HTML. Isso fornece acesso às classes e componentes do Bootstrap e às funcionalidades do jQuery para manipulação e validação de formulários.

```html
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/5.3.0/css/bootstrap.min.css">
<script src="https://stackpath.bootstrapcdn.com/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

