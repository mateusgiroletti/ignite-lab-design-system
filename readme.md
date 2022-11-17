# Ignite Lab Design System

Aplicação realizada durante evento Ignite Lab edição Design System da [RocketSeat](https://www.rocketseat.com.br/)

## O Projeto

O projeto consiste em um design system completo, desde a prototipação no figma, documentação dos componentes com storybook, desenvolvimento da interface com React, testes e por fim deploy automatizado com o GitHub Actions e GitHub Pages.
Visando assim a aprendizagem de um desenvolvimento completo de uma aplicação moderna front-end web.

## Tecnologias

As seguintes tecnologias foram utilizadas no desenvolvimento do projeto:

<ul>
    <li>
        Figma
        <p>
            Ferramenta utilizada para prototipar a interface, criando palhetas de cores e componentes.
        </p>
    </li>
    <li>
        Vite
        <p>
            Utilizado para criação do projeto, uma opção muito mais rápida  que o create-react-app, suporta typescript (utilizado no projeto) e outras tecnologias de ponta.
        </p>
    </li>
    <li>
        React
        <p>
            A biblioteca mais popular atualmente para desenvolvimento de interfaces front-end web, evoluindo a cada versão e tendo uma enorme comunidade suportando.
        </p>
    </li>
    <li>
        TypeScript
        <p>
            Adicionando tipagem ao javascript, facilitando a detecção de erros durante o desenvolvimento e incluindo IntelliSense da IDE, facilitando assim o desenvolvimento.
        </p>
    </li>
    <li>
        Storybook
        <p>
            Solução para documentar o front-end, criando os componentes, seus atributos, propriedades e até mesmo as páginas da aplicação, ajudando a manter um design system. Possui integração completa com o react e testes.
        </p>
    </li>
    <li>
        Tailwind CSS
        <p>
            Biblioteca que traz classes CSS e demais elementos prontos para utilizar no desenvolvimento, acelerando assim a criação das interfaces. Mas é possível também alterar as paletas de cores e demais classes de um jeito fácil e sem precisar mexer diretamente o código CSS.
        </P>
    </li>
    <li>
        Radix-ui
        <p>
            Ferramenta que traz componentes reutilizáveis, sem estilização prontos para serem utilizados na criação da interface. 
        </p>
    </li>
    <li>
        Jest
        <p>
            Framework JS para realizar testes automatizados e simples, possui integração com React e storybook, podendo assim realizar testes a cada interação na própria documentação.
        </p>
    </li>
    <li>
        Mock Service Worker: MSW
        <p>
            Utilizado para interceptar requisições externas e simular respostas de uma determinada API.
        </p>
    </li>
    <li>
        GitHub Actions
        <p>
            Utilizado para automatizar o workflow, realizando o deploy contínuo do design system a cada commit realizado no repositório remoto.
        </p>
    </li>
    <li>
        GitHub Pages
        <p>
            Solução grátis para hospedar arquivos estáticos, utilizado para o design system.
        </p>
    </li>
</ul>

## Prototipo da Interface

Durante as aulas foi desenvolvido no Figma o prototipo da interface, que pode ser visto [aqui](https://www.figma.com/file/deUKSSFh08h5fqtXUX7dKF/Ignite-Lab-Design-System?node-id=5%3A58&t=RcYClD8T6i8OyODS-1).

<img src="./.github/images/figma.png" alt="Figma Prototype" />

## Documentação do Design System

A documentação do Design System pode ser acessada [aqui](https://mateusgiroletti.github.io/ignite-lab-design-system/).


## Teste o projeto você mesmo

Para executar o projeto localmente basta clonar o repositório e executar os seguintes comandos. 

Clone em sua maquina:

```console
git clone https://github.com/mateusgiroletti/app-service-provider-server.git
```

Mude para o diretório do projeto e instale as dependências via npm
```console
cd ignite-lab-design-system && npm install
```

Pare executar o storybook rode:

```console
npm run storybook
```

Acessando o link fornecido na saída do console, o resultado esperado é este:

<img src="./.github/images/storybook.png" alt="Storybook" />

E para rodar a interface desolvida:

```console
npm run dev
```

Acessando o link fornecido na saída do console, o resultado esperado é este:

<img src="./.github/images/application.png" alt="Application" />
