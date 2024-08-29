<p align="center">
  <img src="https://img.icons8.com/color/96/000000/zoo.png" width="100" />
</p>
<p align="center">
    <h1 align="center">Animais Fantásticos</h1>
</p>
<p align="center">
    <em>Projeto web responsivo que apresenta informações sobre vários animais de forma interativa</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="license">
	<img src="https://img.shields.io/badge/version-1.0.0-blue.svg?style=flat-square" alt="version">
</p>
<hr>

## 🔗 Links Rápidos

> - [ Visão Geral](#-visão-geral)
> - [ Características](#-características)
> - [ Estrutura do Repositório](#-estrutura-do-repositório)
> - [ Começando](#-começando)
>   - [ Instalação](#-instalação)
>   - [ Executando o Projeto](#-executando-o-projeto)
> - [ Personalização](#-personalização)
> - [ Compatibilidade](#-compatibilidade)
> - [ Contribuindo](#-contribuindo)
> - [ Licença](#-licença)

---

## 📍 Visão Geral

Animais Fantásticos é um projeto web responsivo que apresenta informações sobre vários animais de forma interativa. O projeto inclui uma interface com abas para descrições de animais, uma seção de FAQ em estilo accordion e navegação com scroll suave.

---

## 🔮 Características

- Design responsivo que se adapta a diferentes tamanhos de tela
- Interface interativa com abas para exibir informações sobre os animais
- Seção de FAQ em estilo accordion
- Navegação com scroll suave
- Estilização personalizada com animações CSS

---

## 🧩 Estrutura do Repositório

```sh
└── animais-fantasticos/
    ├── index.html
    ├── style.css
    └── script.js
````
## 🚀 Começando

**Requisitos**

Certifique-se de ter um navegador web moderno instalado.

### ⚙️ Instalação

1. Clone o repositório Animais Fantásticos:

   ```sh
   git clone https://github.com/camilarozendo/animais-fantasticos.git
   ````

2. Navegue até o diretório do projeto:
    ```sh 
    cd animais-fantasticos
    ```


## 👩‍💻 Executando o Projeto
Abra o arquivo index.html em seu navegador web.

## 🎨 Personalização

### Adicionando Novos Animais

1. Adicione um novo elemento `<li>` com uma imagem na seção `.animais-lista` do `index.html`
2. Crie uma `<section>` correspondente na div `.animais-descricao` com as informações do animal

### Modificando Estilos

O arquivo `style.css` contém todos os estilos do projeto. Você pode modificar cores, fontes e layout editando este arquivo.

### Estendendo a Funcionalidade

O arquivo `script.js` contém três funções principais:

- `initTabNav()`: Gerencia a interface com abas para descrições de animais
- `initAccordion()`: Gerencia a funcionalidade de acordeão para a seção de FAQ
- `initScrollSmooth()`: Implementa a rolagem suave para os links de navegação

Você pode estender ou modificar essas funções para adicionar novos recursos ou alterar o comportamento existente.

## 💻 Compatibilidade

Este projeto usa recursos modernos de CSS e JavaScript. Ele deve funcionar em todas as versões recentes dos principais navegadores, mas pode ser necessário adicionar polyfills ou ajustar o código para compatibilidade com navegadores mais antigos.

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou criar issues para melhorar o projeto.

### Diretrizes de Contribuição

1. **Fork o Repositório**: Comece fazendo um fork do repositório do projeto para sua conta do GitHub.
2. **Clone Localmente**: Clone o repositório forkado para sua máquina local.
3. **Crie uma Nova Branch**: Sempre trabalhe em uma nova branch.
4. **Faça Suas Alterações**: Desenvolva e teste suas alterações localmente.
5. **Commit Suas Alterações**: Faça commit com uma mensagem clara descrevendo suas atualizações.
6. **Push para o GitHub**: Faça push das alterações para seu repositório forkado.
7. **Envie um Pull Request**: Crie um PR contra o repositório original do projeto.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo [LICENSE](LICENSE) para obter detalhes.

## 🙏 Créditos

Desenvolvido como parte do curso da [Origamid](https://www.origamid.com/).