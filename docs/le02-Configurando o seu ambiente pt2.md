# 🛠️ Configurando o seu Ambiente de Desenvolvimento em 2025 - Parte 2  

## Tudo o que você precisa para começar a programar em Python - Sistema operacional e Python

Na parte 1 deste guia, debatemos sobre as principais características de hardware para um ambiente de programação em Python. Nessa segunda parte, vamos falar sobre sistemas operacionais, e sobre o próprio Python.  

### Escolhendo um Sistema Operacional  

Tudo começa com um sistema operacional (**OS**). Há dezenas de vídeos comparando diversos tipos de sistemas operacionais para programadores e suas vantagens e limitações, é quase uma briga de fanboys de tecnologia mas na real, a escolha é **totalmente subjetiva**. Você VAI codar em Python **no sistema que você escolher**, então vamos listar os prós e contras de cada um e, no final, vou falar sobre a minha escolha pessoal, que eu considero muito versátil pra você, meu querido dev.  

---

### **Windows**  

O **Windows** é o sistema operacional mais popular e familiar para a maioria das pessoas antes de entrar no mundo tech. Criado e distribuído pela Microsoft, ele oferece **suporte abrangente ao usuário** e é compatível com praticamente qualquer aplicativo (incluindo seus joguinhos da Steam). Sua interface intuitiva é bem conhecida mundialmente e é bem fácil de utilizar.

No entanto, o Windows **não é gratuito**, a menos que você opte por pirataria hahaha. Isso significa que será necessário pagar pela licença para ter acesso à versão mais recente. Além disso, **suas opções de personalização são limitadas**, pois a Microsoft controla muitas configurações (até mesmo por questões de segurança), o que pode frustrar usuários que querem um sistema altamente customizável.  

No geral, o Windows é um **sistema confiável e eficiente** para tarefas do dia a dia, trabalho e lazer. Ele tem **suporte para uma grande variedade de drivers**, garantindo compatibilidade com diversos hardwares sem complicações. A performance e o uso pode ser ainda mais otimizada com um **debloat**—um processo que remove aplicativos desnecessários instalados pela Microsoft.  

---

### **Linux**  

O **queridinho dos desenvolvedores, entusiastas de tecnologia e amantes do open-source**. O Linux não é um sistema operacional único, mas sim um **kernel** (como se fosse um núcleo) que serve de base para diferentes **distribuições** (**distros**), como **Ubuntu, Fedora, Arch Linux e Debian**.  

Diferente do Windows, o Linux é **totalmente gratuito e de código aberto**, permitindo que qualquer pessoa o utilize, modifique e distribua sem custos. Ele oferece um **altíssimo nível de personalização**, permitindo mudar desde a interface gráfica até os mínimos detalhes do sistema. As principais distribuições constumam ser bastante **seguras e estáveis** (por exemplo, o Ubuntu tem um suporte enorme da Canonical, empresa responsável pelo seu desenvolvimento) e por isso, as distros de Linux são amplamente utilizado em **servidores, supercomputadores e ambientes de desenvolvimento**.  

Muitas aplicações e ambientes de produção são baseados em Linux, tornando o conhecimento do sistema uma **habilidade essencial para programadores**. Além disso, o **terminal** do Linux é extremamente poderoso e se torna um grande diferencial para quem quer trabalhar profissionalmente na área de tecnologia.  

Por conta disso, o Linux tem uma **curva de aprendizado maior**, principalmente para quem vem do Windows, que é um sistema todo "clicávelzinho", pois, muitas tarefas exigem o uso do terminal.

O real "Downside" do Linux é que, embora a compatibilidade com drivers e softwares tenha melhorado bastante, **alguns programas e jogos ainda não possuem suporte nativo**, exigindo algumas gambiarras pra contornar esse tipo de limitação as vezes.  

Então, se você busca **liberdade, eficiência e controle total do sistema**, o Linux é uma excelente opção.

Você **vai** enfrentar problemas na instalação de **drivers de placa de vídeo, câmeras e microfones HAHAHAHA**, mas fora isso, tudo funciona bem e é uma delícia.  

💡 **Dica:** Se quiser aprender mais sobre Linux, com mais detalhes sobre a instalação, diferentes distros, uso profissional, recomendo o canal **Diolinux** no YouTube!  
🔗 [https://www.youtube.com/channel/UCEf5U1dB5a2e2S-XUlnhxSA](https://www.youtube.com/channel/UCEf5U1dB5a2e2S-XUlnhxSA)  

---

### **macOS**  

Costumo brincar que **macOS é basicamente um Linux de grife**. Desenvolvido pela Apple, ele é **estável, seguro e altamente otimizado** para o hardware dos Macs. Sua **interface é um capricho à parte**, e a **integração perfeita com o ecossistema Apple**, faz com que seja um sistema muito utilizado por **desenvolvedores, designers e editores de vídeo**.  

Chamo de "Linux de grife" pois é baseado no **Unix** (assim como as distros de linux). Por conta disso, o macOS herda muitas características do sistema open-source, como **segurança, estabilidade e um terminal poderoso**. Muitos desenvolvedores amam o Mac justamente por conta dessa semelhança com o Linux, aliada com o fator premium dos produtos da Apple, tornando-o uma das opções mais amadas da programação.  

O grande **ponto negativo** do macOS é o custo. Ele **só pode ser instalado oficialmente em computadores da Apple**, que costumam ser **ABSURDOS de caro** quando comparados a outras opções no mercado.

Se você já tem um Mac, **aproveite**, pois o sistema tem uma experiência de uso excelente. Você usuário de Mac, está em boas mãos!!

---

### **Minha Escolha**  

Eu uso **Windows**. Sim, Windows. Uso programas no meu dia a dia que eu simplemente não consigo abrir mão para usar Linux. **Mas**, para desenvolvimento, eu utilizo o **WSL2 (Windows Subsystem for Linux)**, que basicamente permite rodar um ambiente Linux dentro do Windows. Sem uma interface gráfica para o OS Linux, você pode acessá-lo pelo terminal e a partir disso, utilizar o sistema Linux para suas tarefas de programação sem precisar abrir mão do Windows do dia a dia

O WSL2 permite que você tenha o **melhor dos dois mundos**: **o  Windows - com todo o seu suporte e infraestrutura - para suas tarefas do dia dia, e o poder do Linux no terminal para codar**. A única desvantagem é que, como ele roda dentro do Windows, a **performance é um pouco inferior** a um sistema Linux puro. Ainda assim, uma alternativa super interessante que melhora ainda mais a experiência de programação no Windows.

🔗 Quer aprender a instalar e configurar o WSL2? Confira este vídeo:  
[https://www.youtube.com/watch?v=O813vtoaXmc](https://www.youtube.com/watch?v=O813vtoaXmc)  

---

### **E finalmente, o Python  🐍**  

Agora, com o sistema definido, finalmente vamos instalar o Python!

O **Python** é uma linguagem interpretada, ou seja, o código-fonte é traduzido linha por linha durante a sua execução por um interpretador, que o converte em um formato compreensível para o computador (sequências de 0s e 1s). As vantagens e limitações do Python ser uma linguagem interpretada podem ser assuntos interessantes para outro post. Todavia, o objetivo dessa introdução é destacar que o Python precisa de um interpretador para que as instruções escritas em código possam ser executadas pelo computador.

Na maioria dos casos, o Python **não vem instalado por padrão**:  

- No **Windows**, é necessário instalar manualmente.  
- No **Linux**, o Python geralmente já está instalado.  
- No **macOS**, ele costumava vir pré-instalado, mas desde a versão 12.3, **precisa ser instalado manualmente**.  

Para verificar se o Python já está instalado, abra o terminal e digite:  

```bash
python --version
```

E a resposta que você vai obter será mais ou menos assim:

``` bash
python --version # comando
Python 3.10.12 # aqui está a versão do python instalado
```

Caso você ainda não tenha Python instalado, você não terá essa resposta. Então, instale o Python:

### 🖥️ No Windows

- **Passo 1:** Baixar o instalador
  - Acesse o site oficial do Python: 🔗 <https://www.python.org/downloads/windows/>
  - Clique no botão "Download Python 3.x.x" (versão mais recente).
- **Passo 2:** Executar o instalador
  - Abra o arquivo .exe baixado.
  - Marque a opção ✅ "Add Python to PATH" (muito importante para rodar Python no terminal).
  - Clique em "Install Now" e aguarde a instalação.

Após a instalação, abra o Prompt de Comando (CMD) e digite o comando ``
python --version ``, se a resposta for algo como ```Python 3.x.x```, a instalação foi concluída com sucesso!

---  

### 🍏No Mac

**Opção 1:** Instalação pelo site oficial

- Acesse o site oficial do Python: 🔗 <https://www.python.org/downloads/mac-osx/>
- Baixe o arquivo .pkg correspondente à versão mais recente.
- Execute o instalador e siga as instruções (semelhante ao Windows).

**Opção 2:** Instalação pelo Homebrew (recomendado para desenvolvedores)

Se você já tem o Homebrew instalado, a maneira mais simples de instalar o Python é rodando:

```bash
brew install python
```

Após a instalação, verifique a versão:

```bash
python3 --version
```

Se aparecer ```Python 3.x.x```, já sabe, comemora!

---

### 🐧 No Linux

A maioria das distribuições Linux **já vem com o Python instalado**.

Caso precise atualizar ou instalar manualmente, use o comando abaixo no terminal. O comando varia de acordo com a distribuição (que pode ter diferentes gerenciadores de pacote). Para distribuições baseadas em Debian (Ubuntu, Pop! OS, Linux Mint, etc.) é mais ou menos assim:

```bash
sudo apt update && sudo apt install python3 python3-pip
```

Após a instalação, verifique a versão:

```bash
python3 --version
```

E se obtiver uma resposta parecida com ```Python 3.x.x``` , deu certo.

---

### Por fim, configurando o Python após a instalação

- Verifique se o pip está instalado
  
O pip (gerenciador de pacotes do Python) geralmente já vem instalado, ele serve para baixar os pacotes (que são como blocos de construção) que você instala para adicionar no seu código e ter funcionalidades que extrapolam o poder do Python raíz. Por exemplo, você quer criar a imagem de um gráfico e o Python por si só não consegue fazer isso. E é por isso que a extensa comunidade Python open-source lança diversos desses pacotes na internet que complementam o processo de desenvolvimento de uma aplicação, com implementações de funções diversas que facilitam o desenvolvimento a partir da condensação de códigos super complexos nesses pacotes. Confirme digitando:

```bash
pip --version
```

Se o comando não funcionar, instale o pip manualmente:

```
python -m ensurepip --default-pip
```

- Verifique se o Python está no PATH

Se o terminal não reconhecer o comando python, você pode precisar adicioná-lo ao PATH manualmente.

#### Windows

1. Pressione Win + R e digite sysdm.cpl, depois vá em Avançado → Variáveis de Ambiente.
2. Encontre Path e adicione o caminho da instalação do Python (geralmente C:\Python3x\).
  
#### Linux/macOS

Adicione esta linha ao final do arquivo ~/.bashrc ou ~/.zshrc:

```bash
export PATH=$HOME/.local/bin:$PATH
```

Depois, recarregue o terminal:

```bash
source ~/.bashrc  # Ou source ~/.zshrc no macOS
```

---

#### E com isso senhores, parabéns, o Python está oficialmente instalado no seu sistema

Eu recomendo que você siga logo de cara a dica que vou passar aqui logo em seqûencia, vai te ajudar demaisss no longo prazo:

O ``uv`` é uma ferramenta moderna e otimizada para gerenciamento de pacotes e ambientes virtuais em Python. Um ambiente virtual é basicamente uma coletânea de pacotes em que você consegue controlar especificamente as versões desejadas para cada componente (inclusive para o Python), e assim, organizar o seu projeto da maneira mais correta possível.

Há outras alternativas de instalador de pacotes, algumas até mesmo mais famosas como o ``conda`` e o ``virtualenv`` mas o ``uv`` tem sido a minha escolha pois ele é **simplesmente absurdo** na velocidade de instalar pacotes e na simplicidade que esse processo tem.

Então, sem mais delongas, vamos instalar o ``uv``:

#### 1. No terminal com Python e pip instalados, digite

```bash
pip install uv
```

Isso instalará o uv globalmente no seu sistema.

---

#### 2. O segundo passo é criar o seu primeiro ambiente

No terminal digite:

```bash
uv venv meu_ambiente
```

Isso criará uma pasta chamada meu_ambiente, contendo todos os arquivos do ambiente virtual.

---

#### 3. Após criar o ambiente, é necessário ativá-lo

**No Windows (PowerShell):****

```powershell
meu_ambiente\Scripts\activate
```

**Já para o Linux/macOS:**

```bash
source meu_ambiente/bin/activate
```

Agora, qualquer pacote instalado será isolado neste ambiente da maneira correta. Você muito provavelmente vai criar ambientes diferentes para aplicações diferentes e por isso é tão interessante ter os pacotes isolados corretamente. Isso faz com que você consiga evitar erros de incompatibilidade entre pacotes e organize melhor o seu projeto. É legal também fazer um mega ambiente com tudo que você mais usa e ir atualizando ele constantemente de acordo com as suas necessidades, usando esse mega ambiente para projetos mais gerais e rápidos.

---

#### 4. Por fim, baixando os pacotes com o uv

para baixar um pacote da maneira mais tradicional, o comando com pip seria: ``pip install nome_do_pacote``, com uv, é quase a mesma coisa, basta apenas adicionar o ``uv`` antes: ``uv pip install nome_do_pacote``.

Exemplo de instalação real do pandas (pacote mais famoso para análise de dados):

```bash
uv pip install pandas
```

---

#### 5. Por fim, para sair do ambiente virtual, basta rodar

```bash
deactivate 
```

E para deletar um ambiente virtual,

**Linux/Mac:**

```bash
rm -rf meu_ambiente
```

**Windows:**

```bash
Remove-Item -Recurse -Force meu_ambiente
```

***OBS: Para mais funcionalidades do ``uv``, digite ``uv --help`` no terminal, você terá uma lista dos principais comandos do ``uv`` como resposta.***

No geral, é isso por hoje pessoal! Sei que esse guia ficou bem extenso, e ainda teremos a parte 3, explicando sobre os outros softwares que importam na vida de um desenvolvedor, como a IDE (que é a interface onde você vai escrever e digitar seu código), o git e o github além de outros softwares interessantes para a sua jornada de dev. Até lá meu guerreiro!!

---

***⚠️ Aviso: Caso tenha qualquer dúvida, sinta-se à vontade para entrar em contato por e-mail:*** <contacttpyj@gmail.com> ***. Além disso, você pode utilizar sua ferramenta de IA favorita para esclarecer tópicos que possam ter ficado abstratos, incompletos ou vagos. O conhecimento está sempre em expansão, e há muito mais para explorar na internet!***

***⚠️ Aviso 2: Caso encontre algum erro, ou tenha alguma sugestão para esse texto, entre em contato comigo em:*** <contacttpyj@gmail.com> ***e sugira suas mudanças! Contribua com o projeto, você e sua opinião são muito bem vindos por aqui!***
