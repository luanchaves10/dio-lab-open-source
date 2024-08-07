<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Guia de Contribuição</span>
</h1>

[![Star](https://img.shields.io/github/stars/digitalinnovationone/dio-lab-open-source?style=social)](https://github.com/digitalinnovationone/dio-lab-open-source/stargazers)
[![Forks](https://img.shields.io/github/forks/digitalinnovationone/dio-lab-open-source?style=social)](https://github.com/digitalinnovationone/dio-lab-open-source/forks)
[![GitHub Issues](https://img.shields.io/github/issues/digitalinnovationone/dio-lab-open-source?style=social)](https://github.com/digitalinnovationone/dio-lab-open-source/issues/)

 Este é um projeto feito para a comunidade, então sinta-se livre para contribuir. Algumas formas de contribuição além do seu exemplo de Profile README, é inserir outros utilitários na pasta [`utils`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/utils), ou melhorar a página de pesquisa dos READMEs fazendo modificações nos arquivos da pasta [`docs`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/docs). <br>
 Além disso, você também pode contribuir:
 
⚠️ Resolvendo, respondendo ou indicando **issues**

⭐ Adicionando aos favoritos (**star**) 

##  Contribuindo no diretório "Community" 
 A contribuição no diretório "Community" é uma das formas de completar o Desafio do lab "**Contribuindo em um Projeto Open Source no GitHub**" da [Digital Innovation One](https://www.dio.me/). Você pode colaborar criando um Profile README contendo informações sobre você que deseje compartilhar com a comunidade. <br>
 Para isso, você pode inserir: badges indicando suas habilidades; cards com suas estatísticas no GitHub e projetos que criou, colaborou ou que deseje que outras pessoas colaborem. Além disso, você pode inserir também links para seus desafios de projeto e artigos na plataforma da [Digital Innovation One](https://www.dio.me/). <br>
 Inspire-se consultando os exemplos na pasta [`community`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/community), confira alguns utilitários na pasta [`utils`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/utils) e use sua criatividade para criar o seu 😊💙.

### 1) Faça um **Fork** deste Repositório
Acesse a página principal do repositório e clique no botão "Fork" no canto superior direito da página.
> [!NOTE]  
> Um "fork" no GitHub é uma cópia de um repositório que pode ser criada por qualquer usuário. <br>
> Para mais detalhes, reveja a aula ou acesse a documentação do GitHub: [Criar fork de um repositório](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo).

### 2) Clone localmente
Abra o seu Git Bash e digite o comando `git clone` seguido da URL do seu fork para clonar o seu repositório localmente. Por exemplo:
```bash
git clone https://github.com/SEU_USERNAME/dio-lab-open-source.git
```
Pressione enter, e uma cópia do seu fork no GitHub será criada localmente.

### 3) Crie uma nova **branch** 
Utilize o comando `git checkout -b` para criar e alternar para a nova branch e nomeie-a como `feat/community/SEU_USERNAME`
> Exemplo: `git checkout -b feat/community/falvojr`

### 4) Crie o seu Profile README
 Dentro da pasta [`community`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/community), crie um arquivo em Markdown (extensão `.md`) e nomeie com o mesmo nome do seu usuário no GitHub:

> Exemplo: `community/falvojr.md`

#### 4.1) Desenvolva o seu Profile README
Para isso, você pode se inspirar nos exemplos no diretório [`community`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/community) e adicionar alguns dos utilitários presentes na pasta [`utils`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/utils)

### 5) Adicione suas alterações à "staging area" 
Utilize o comando `git add community/SEU_USERNAME.md` para adicionar sua alteração (nesse caso o arquivo markdown criado)  à "staging area" no Git.

### 6) Crie um Commit
Crie um commit e adicione a mensagem indicando a adição do seu perfil:
```bash
git commit -m"feat: add SEU_USERNAME profile"
```
>[!IMPORTANT]
> Verifique a [`Convenção de Commits`](https://github.com/digitalinnovationone/dio-lab-open-source/blob/main/CONTRIBUTING.md#conven%C3%A7%C3%A3o-de-commits) para escrever a mensagem do seu commit de forma clara e padronizada.

### 7) Envie as Alterações para o seu Repositório Remoto
Envie as alterações realizadas no seu repositório local para a branch `feat/community/SEU_USERNAME` no seu repositório remoto com o comando:
```bash
git push origin feat/community/SEU_USERNAME
```
>[!WARNING]
> Caso você tenha criado seu arquivo diretamente no repositório remoto no GitHub, esse processo não será necessário.

### 8) Crie um **Pull Request**.

Atente-se para a seguir as orientações para a contribuição, principalmente:
- Seu PR deve modificar apenas o arquivo community/SEU_USERNAME.md (dê uma olhadinha na aba "Files changed");
- O nome desse arquivo deve ser exatamente igual ao nome de usuário no GitHub (nossa validação é case-sensitive).

>[!NOTE]
> Caso não saiba como criar uma solicitação de pull, reveja o lab ou acesse a documentação do GitHub: [Como criar uma solicitação de pull
](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
>
>
>
>Contribuir com um projeto open source no Linux pode ser uma experiência muito gratificante e uma excelente maneira de aprender mais sobre desenvolvimento de software. Aqui está um guia passo a passo para te ajudar a começar:

### 1. Encontre um Projeto

**1.1. Identifique seus interesses:**

- Escolha um projeto que esteja alinhado com seus interesses ou habilidades. Pode ser uma biblioteca que você usa frequentemente ou um projeto que você acha interessante.

**1.2. Pesquise:**

- Utilize plataformas como GitHub, GitLab, ou Bitbucket para encontrar projetos open source. Muitos projetos também têm sites dedicados e comunidades ativas.

### 2. Entenda o Projeto

**2.1. Leia a documentação:**

- Antes de começar a contribuir, familiarize-se com o projeto. Leia o README, a documentação e os arquivos CONTRIBUTING.md ou similares. Isso te dará uma visão geral do projeto e das diretrizes para contribuições.

**2.2. Explore o código:**

- Navegue pelo código-fonte para entender a estrutura do projeto. Verifique como o projeto é organizado e onde as funcionalidades estão localizadas.

### 3. Configure o Ambiente

**3.1. Clone o repositório:**

- Faça uma cópia do repositório para o seu ambiente local:
    
    ```bash
    bashCopiar código
    git clone https://github.com/usuario/repo.git
    cd repo
    
    ```
    

**3.2. Instale dependências:**

- Siga as instruções na documentação para instalar quaisquer dependências necessárias. Isso pode envolver a instalação de pacotes, ferramentas ou bibliotecas específicas.

**3.3. Configure o ambiente:**

- Certifique-se de que você tem todas as ferramentas e configurações necessárias para executar e testar o projeto.

### 4. Encontre uma Tarefa

**4.1. Procure por problemas:**

- Verifique a seção de issues do repositório para encontrar tarefas que precisam de ajuda. Muitos projetos têm etiquetas como "good first issue" ou "help wanted" que são ideais para novos contribuidores.

**4.2. Comunique-se:**

- Se não houver uma tarefa clara ou se você tiver uma ideia para uma melhoria, considere abrir uma nova issue para discutir com os mantenedores.

### 5. Faça Suas Alterações

**5.1. Crie uma branch:**

- Crie uma nova branch para suas alterações:
    
    ```bash
    bashCopiar código
    git checkout -b nome-da-sua-branch
    
    ```
    

**5.2. Faça suas alterações:**

- Implemente suas mudanças no código ou faça a correção necessária.

**5.3. Teste suas alterações:**

- Execute os testes para garantir que suas mudanças não quebrem o código existente. Adicione novos testes se necessário.

### 6. Submeta Sua Contribuição

**6.1. Commit e push:**

- Faça commit das suas mudanças e envie para o repositório remoto:
    
    ```bash
    bashCopiar código
    git add .
    git commit -m "Descrição das mudanças"
    git push origin nome-da-sua-branch
    
    ```
    

**6.2. Abra um pull request (PR):**

- No repositório do projeto, abra um pull request para que os mantenedores possam revisar suas alterações.

**6.3. Participe da revisão:**

- Esteja disponível para responder a comentários e feedback dos revisores. Pode ser necessário fazer alterações adicionais com base no feedback.

### 7. Mantenha-se Engajado

**7.1. Acompanhe o PR:**

- Após a fusão do seu PR, acompanhe o projeto para ver o impacto das suas mudanças e continue contribuindo conforme se sentir confortável.

**7.2. Continue aprendendo:**

- Contribuir para projetos open source é uma ótima maneira de aprender e melhorar suas habilidades. Continue explorando e participando da comunidade.

Contribuir para projetos open source pode parecer desafiador no início, mas é um processo muito enriquecedor. Boa sorte com suas contribuições!

Após criar o seu Pull Request, nossa automação irá validar a sua submissão. Caso esteja tudo certo, será retornada uma mensagem indicado que seu PR foi aprovado. Do contrário, leia atentamente as orientações e verifique os arquivos modificados para saber se atende as instruções para contribuição.
    
    
## Convenção de Commits 

| Tipo de Commit |Descrição                                                            | Exemplo
| ---------------|----------------------------------------------------------------------|-----------
| `feat`         | Adiciona uma nova funcionalidade ao projeto.                         | `feat: add USENAME.md profile`
| `fix`          | Corrige um bug ou problema no projeto.                               | `fix: fixed issue fix#IssueNumber`
| `docs`         | Altera a documentação do projeto.| `docs: update README.md`
| `style`        | Realiza mudanças na aparência, sem alterar a funcionalidade.         | `style: add EFFECTNAME to COMPONENT`
| `refactor`     | Realiza mudanças no código que não alteram a funcionalidade.         | `refactor: refactor at CLASSNAME`
| `test`         | Adiciona ou modifica testes no projeto.                              | `test: add unit test for UserService`


## Referências
- [ANGULAR. Contributing to Angular](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md)
- [CONVENTIONAL COMMITS. Summary](https://www.conventionalcommits.org/en/v1.0.0/)
- [GITHUB. Configurar diretrizes para os contribuidores do repositório](https://docs.github.com/pt/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)
