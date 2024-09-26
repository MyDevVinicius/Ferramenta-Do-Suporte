
# Ferramenta do Suporte

**Ferramenta do Suporte** é um software projetado para simplificar e gerenciar o processo de suporte técnico. Com a Ferramenta do Suporte, você pode criar, rastrear e resolver tickets de suporte com eficiência, permitindo uma melhor organização e resposta rápida às solicitações dos clientes.

## Índice

1. [Introdução](#introdução)
2. [Funcionalidades](#funcionalidades)
3. [Requisitos](#requisitos)
4. [Contribuição](#contribuição)
5. [Licença](#licença)
6. [Contato](#contato)
7. [Detalhes de Versões](#detalhes-de-versões)

## Introdução

A Ferramenta do Suporte é uma solução completa para o gerenciamento de tickets, projetada para equipes de suporte técnico. Oferece uma interface intuitiva e recursos robustos para garantir que cada solicitação seja tratada de forma eficiente e eficaz.

## Funcionalidades

- **Criação de Tickets**: Permite que os usuários criem tickets de suporte com detalhes sobre o problema através do WhatsApp.
- **Rastreamento de Status**: Acompanhe o status de cada ticket em tempo real.
- **Prioridade e Categorias**: Defina a prioridade e categorias dos tickets para uma melhor organização.
- **Comunicação Integrada**: Troque mensagens diretamente no ticket para manter toda a comunicação centralizada.
- **Relatórios e Análises**: Gere relatórios detalhados sobre o desempenho do suporte e a satisfação do cliente.
- **Integração com WhatsApp**: Receba e envie notificações de WhatsApp relacionadas aos tickets.
- **Controle de Ativos**: Controle todos os equipamentos da sua empresa e tenha mais segurança.
- **Arquivo do Cliente**: Área exclusiva por cliente para armazenar informações como acessos, contratos e observações.

## Requisitos

Antes de instalar e executar a Ferramenta do Suporte, certifique-se de que seu ambiente de desenvolvimento atende aos seguintes requisitos:

- **Sistema Operacional**:
  - Windows 10 ou superior
  - macOS 10.14 ou superior
  - Uma distribuição Linux compatível (Ubuntu 20.04 ou superior, Fedora 34 ou superior, etc.)

- **Linguagem de Programação**:
  - **Node.js** para o back-end

- **Banco de Dados**:
  - MySQL 8 ou superior
  - Alternativamente, MariaDB 10.5 ou superior

- **Ambiente de Desenvolvimento**:
  - **IDE/Editor de Código**: Visual Studio 2022 ou superior, Visual Studio Code, ou outro editor de código compatível com C# e JavaScript.
  - **Node.js**: Versão 18.x ou superior (necessário para desenvolvimento com React)
  - **npm**: Incluído com o Node.js ou **Yarn** (opcional, para gerenciamento de pacotes)
  - **Git** para controle de versão

- **Front-End**:
  - **React**: Biblioteca JavaScript para construção de interfaces de usuário
  - **Vite**: Ferramentas de configuração para iniciar o projeto React

- **Dependências de Bibliotecas**:
  - Consulte o arquivo `requirements.txt` para o back-end e `package.json` para o front-end para uma lista completa de bibliotecas e pacotes necessários.

- **Navegadores Suportados**:
  - Google Chrome (última versão estável)
  - Mozilla Firefox (última versão estável)
  - Safari 14 ou superior
  - Microsoft Edge (última versão estável)

- **Configurações de Hardware**:
  - Mínimo: 2 GB de RAM e 2 CPUs
  - Recomendado: 4 GB de RAM e 4 CPUs para um desempenho ideal





## Contribuição

Contribuições são bem-vindas! Se você deseja ajudar a melhorar a Ferramenta do Suporte, siga as diretrizes abaixo para garantir que suas contribuições sejam integradas da melhor forma possível.

### Como Contribuir

1. **Fork o Repositório**

   Primeiro, faça um fork do repositório para sua própria conta no GitHub. Isso criará uma cópia do projeto onde você poderá fazer suas alterações.

   ```bash
   git clone https://github.com/seuusuario/ferramenta-do-suporte.git
   cd ferramenta-do-suporte
   git remote add upstream https://github.com/organização/ferramenta-do-suporte.git

2. **Crie uma Branch**
Crie uma nova branch para suas alterações. É uma boa prática nomear a branch de forma descritiva, por exemplo: melhoria/interface ou correcao/botao.

`git checkout -b minha-nova-funcionalidade`

3. **Faça Alterações e Teste**
Faça as alterações necessárias e teste seu código para garantir que tudo está funcionando conforme o esperado. Se você estiver adicionando uma nova funcionalidade, certifique-se de incluir testes para cobrir essa funcionalidade.

4. **Adicione e Faça Commit das Suas Alterações**
Adicione suas alterações ao índice e faça commit com uma mensagem clara e descritiva. As mensagens de commit devem explicar o "o quê" e o "porquê" das alterações.

`git add .`

`git commit -m "Adiciona nova funcionalidade de exportação de relatórios"`

5. **Envie suas Alterações**
Envie suas alterações para seu repositório forkado no GitHub.

`git push origin minha-nova-funcionalidade
`

6.**Abra um Pull Request**

Vá até a página do seu repositório forkado no GitHub e clique em "New Pull Request". Escolha a branch do seu fork e a branch principal do repositório original (geralmente main ou master). Adicione uma descrição detalhada do que foi alterado e por quê. Depois, envie o pull request.

### Diretrizes de Contribuição
- **Seguir o Guia de Estilo:** Certifique-se de seguir o guia de estilo definido no projeto. Isso inclui formatação de código, convenções de nomenclatura e organização.

- **Testar:** Execute todos os testes para garantir que suas alterações não quebram a funcionalidade existente. Inclua novos testes se estiver adicionando novas funcionalidades.

- **Documentar:** Atualize a documentação do projeto, se necessário, para refletir suas alterações.

- **Manter o Código Limpo:** Evite adicionar código desnecessário ou redundante. Mantenha o código o mais limpo e compreensível possível.

- **Respeitar as Diretrizes do Projeto:** Leia e siga qualquer orientação específica para contribuição que possa estar listada no repositório.

### Relatar Problemas
Se você encontrar um problema ou bug, sinta-se à vontade para abrir um issue no GitHub. Certifique-se de fornecer detalhes suficientes para que possamos entender e reproduzir o problema. Isso inclui:

- Um título claro e descritivo
- Uma descrição do problema
- Passos para reproduzir o problema
- Qualquer mensagem de erro recebida
- Capturas de tela, se aplicável
Agradecemos suas contribuições e feedback! Sua ajuda é fundamental para melhorar a Ferramenta do Suporte.
### Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo  para mais detalhes.

### Contato
Se você tiver dúvidas ou precisar de ajuda, entre em contato conosco:

- E-mail: suporte@ferramentadosuporte.com
- GitHub: github.com/MyDevVinicius/ferramenta-do-suporte

### Detalhes De Versões 

**Versão Gratuita**
- Restrição de Tickets 50 tickets por mês.
- Controle de Ativos não incluso.
- Capacidade de 3 Usuarios e 1 administrador.
- Relatorio : Apenas de quantidade de Tickets


### Ajustes Realizados

1. **Correção de Formatação**: Ajustei algumas inconsistências na formatação do Markdown.
2. **Adição de Seções**: Adicionei a seção "Detalhes de Versões" após a seção "Contato", para manter a ordem lógica e clareza.
3. **Correção de Texto**: Corrigi alguns pequenos erros e inconsistências de digitação e estilo.

Esta versão revisada garante que a documentação esteja clara, consistente e profissional, facilitando a compreensão e a colaboração.



