# Projeto-Bootcamp-Web-Responsivo

# Portfólio Profissional

**Evidência do projeto:** [Acessar arquivos e evidências no Google Drive](https://drive.google.com/drive/folders/1tyQ72rrsZjRiTdkztWITO-eOsVGBY61t?usp=drive_link)

Site de portfólio profissional desenvolvido para apresentar a atuação de **Pedro Giglioti na área de Segurança da Informação**, reunindo informações profissionais, serviços, pesquisas, vulnerabilidades reportadas, certificações e formas de contato.

O projeto foi desenvolvido utilizando **HTML, CSS e JavaScript puro**, sem a utilização de frameworks front-end, com foco em **responsividade e acessibilidade**.

## Sobre o Projeto

O projeto conta com diferentes seções para organizar as informações:

* Apresentação profissional
* Sobre e formação
* Certificações
* Serviços oferecidos
* Pesquisas e vulnerabilidades/CVEs
* Atuação em programas de Bug Bounty
* Formulário de contato
* Rodapé com informações adicionais

## Funcionalidades

### Tema Claro e Escuro

O site possui suporte a **tema claro e escuro**, permitindo que o usuário escolha sua preferência.

A escolha é armazenada no navegador para que o tema selecionado seja mantido durante novas visitas.

### Design Responsivo

A interface foi desenvolvida para se adaptar a diferentes tamanhos de tela, incluindo:

* Smartphones
* Tablets
* Notebooks
* Monitores de diferentes resoluções

### Menu Responsivo

Em dispositivos menores, o menu de navegação é substituído por um botão no formato **hambúrguer**.

No desktop, os links de navegação são apresentados normalmente.

### Navegação Inteligente

Durante a rolagem da página, a seção atualmente visualizada é identificada e seu respectivo item no menu de navegação é destacado.

Isso facilita a localização do usuário dentro da página.

### Formulário de Contato

O site possui um formulário de contato com validação dos campos diretamente no navegador.

São verificadas informações como:

* Nome
* E-mail
* Mensagem
* Preenchimento dos campos obrigatórios

> **Observação:** como o projeto é exclusivamente front-end, o formulário atualmente não possui integração com um servidor ou banco de dados. A validação e a mensagem de confirmação são realizadas diretamente no navegador.

### Acessibilidade

Foram aplicadas boas práticas de acessibilidade, incluindo:

* Utilização de elementos semânticos do HTML5
* Navegação utilizando teclado
* Estrutura organizada de títulos e seções
* Contraste adequado entre texto e fundo
* Elementos interativos acessíveis
* Link de acesso rápido relacionado à acessibilidade

## Tecnologias Utilizadas

O projeto foi desenvolvido sem frameworks, utilizando diretamente as principais tecnologias da web:

### HTML5

Responsável pela estrutura e organização do conteúdo da página.

### CSS3

Responsável pela aparência e layout da aplicação.

### JavaScript

Utilizado para implementar a interação e o comportamento dinâmico da página.

Entre as funcionalidades desenvolvidas estão:

* Menu mobile
* Alternância de tema
* Persistência do tema no navegador
* Identificação da seção atual durante o scroll
* Animação de estatísticas
* Validação do formulário
* Atualização automática do ano no rodapé

O código foi desenvolvido de maneira modular, fazendo com que a ausência de um determinado elemento não impeça o funcionamento das demais funcionalidades.

## Testes Realizados

O projeto foi testado em diferentes situações para garantir seu funcionamento.

### Responsividade

Foram realizados testes em:

* Celular
* Tablet
* Notebook
* Monitor de alta resolução

Também foram realizados testes utilizando o modo de simulação de dispositivos disponível nas ferramentas de desenvolvedor dos navegadores.

### Temas

Foram testados os modos:

* Tema claro
* Tema escuro

Verificando principalmente a legibilidade dos textos e elementos da interface.

### Formulário

Foram realizados testes com:

* Campos preenchidos corretamente
* Campos obrigatórios vazios
* Dados inválidos
* Mensagens de validação

### Navegação por Teclado

A navegação foi testada utilizando exclusivamente a tecla `Tab`, verificando se os principais links e botões poderiam ser acessados sem a utilização do mouse.

## Dificuldades e Soluções

Durante o desenvolvimento, alguns desafios foram encontrados.

### Ordem dos arquivos CSS

Foi necessário compreender a importância da ordem de carregamento dos arquivos CSS.

Dessa forma, as regras específicas de responsividade podem sobrescrever as regras gerais quando necessário.

### Menu Responsivo

Foi necessário adaptar o comportamento da navegação para diferentes tamanhos de tela, garantindo que:

* O menu completo aparecesse em telas maiores;
* O botão hambúrguer fosse exibido em telas menores;
* A navegação continuasse funcional em ambos os casos.

### Persistência do Tema

Um dos problemas encontrados foi o aparecimento momentâneo de uma página clara antes da aplicação do tema escuro escolhido anteriormente.

Para resolver isso, foi utilizado um pequeno trecho de JavaScript executado antecipadamente, permitindo verificar a preferência armazenada antes da renderização completa da interface.

### Formulário sem Back-end

Como o projeto não possui um servidor próprio, o formulário não realiza atualmente o envio real de mensagens.

A solução implementada foi realizar a validação diretamente no navegador e apresentar uma mensagem de confirmação ao usuário.

## Resultado

O resultado final é um **site de portfólio profissional estático, responsivo e funcional**, compatível com navegadores modernos e sem dependência de servidor ou banco de dados.

Por utilizar apenas HTML, CSS e JavaScript, o projeto pode ser hospedado em diversas plataformas de hospedagem de sites estáticos.

## Aprendizados

O desenvolvimento deste projeto permitiu trabalhar de maneira integrada com os três principais pilares do desenvolvimento web front-end:

**HTML → Estrutura**

**CSS → Estilo**

**JavaScript → Comportamento**

A escolha de desenvolver o projeto sem frameworks também possibilitou compreender melhor o funcionamento dessas tecnologias individualmente, desde a estrutura semântica da página até a manipulação do DOM e criação de interações com JavaScript.

## Referências

* [MDN Web Docs](https://developer.mozilla.org/) — Documentação de HTML, CSS e JavaScript.
* [Visual Studio Code](https://code.visualstudio.com/) — Editor de código utilizado no desenvolvimento.

## Informações do Projeto

**Projeto:** Portfólio Profissional
**Área:** Segurança da Informação
**Tecnologias:** HTML5, CSS3 e JavaScript
**Tipo:** Site estático / Front-end
**CNPJ:** 68.535.479/0001-02


Desenvolvido com foco em **semântica, responsividade, acessibilidade e boas práticas de desenvolvimento front-end**.

