
<div style="text-align: center;">
<img src="assets/images/logo.jpg" alt="Logo squad PE" width="250" />


<h1>Repositório para prática de trabalho em equipe</h1>
</div>



## Descrição
Por meio deste repositório você poderá praticar o trabalho colaborativo e conhecimentos de versionamento de código com o Git e GitHub.


## Requisitos

* Ter perfil no GitHub
* Ter o Git instalado - caso não tenha, baixe por meio do link a seguir: [Baixar Git](https://git-scm.com/downloads)
* Ter uma IDE para edição de código, como o Visual Studio Code: [Baixar VS Code](https://code.visualstudio.com/download)


## Orientações

### Git

#### Configuração inicial (Git)
> Essa é a primeira coisa que você deve fazer ao instalar o git: Configurar o nome de usuário e e-mail. 
> Este procedimento só precisa ser realizado **uma vez**

```bash
git config --global user.name "Seu nome Aqui"
```

```bash
config --global user.email seuemail@exemplo.br
```

### Clonando o repositório (GitHub)

1. Na sua máquina, crie uma pasta para salvar o projeto;

2. Copie o link do repositório para cloná-lo (siga os passos abaixo);

<img src="assets/images/screenshots/clone_github.jpg" alt="endereço link clone"  />

3. Clique com o **botão direito** do mouse na pasta que você criou no passo 1, e escolha a opção **abrir no terminal** OU **Git Bash Here**;

4. Com o **terminal aberto**, digite o código:
```bash 
git clone linKCopiado-No-Passo-2
```

<img src="assets/images/screenshots/clone_github2.jpg" alt="Repositório github clonado"  />


**!ATENÇÃO**: Caso você esteja realizando esse procedimento pela primeira vez, será necessário realizar o login no GitHub. **Durante o processo de clonagem aparecerá a opção para você realizar o login**, escolha a opção de **logar pelo navegador**. Será aberta uma janela como mostra na imagem abaixo: Preencha as informações para concluir o processo.
> Este procedimento só precisa ser realizado **uma vez**

<img src="assets/images/screenshots/login-github.jpg" alt="Login github"  />

5. Pronto! Agora **verifique se o repositório já encontra-se na pasta que você configurou para salvá-lo e já pode começar a mexer no projeto**.



### Comandos essenciais (Git)
> **OBS_1**: Todo comando inicia com a palavra git.


**OBS_2**: Quando trabalhamos em equipe é muito importante atualizarmos o nosso repositório local SEMPRE antes de iniciar novos trabalhos, para tanto utilize o comando abaixo **SEMPRE** antes de começar a mexer no código. Isso manterá o projeto atualizado na sua máquina.

```bash
git pull
```


**Sempre que você alterar um arquivo e quiser subí-lo para o GitHub, você deverá ser os comandos abaixo**:

1. Indica em **vermelho** - quais arquivos foram editados - e, em **verde** - os arquivos adicionados para serem comitados:

```bash
git status
```

2. Adiciona **UM** arquivo ou **TODOS** os arquivos editados, para serem comitados, respectivamente.

```bash
git add nomeArquivo.extensão
```

```bash
git add .
```

3. Adiciona mensagem ao(s) arquivo(s) editados. Ex.: Desenvolvimento de formulário, correção de bug 'x'...
```bash
git commit -m "mensagem"
```

4. Envia os arquivo da **sua** máquina para o **GitHub**

```bash
git push origin main
```

