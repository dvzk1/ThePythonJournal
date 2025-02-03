# 🛠️ Configurando o seu Ambiente de Desenvolvimento em 2025 - Parte 1

### Tudo o que você precisa para começar a programar em Python - Introdução e Hardware

Para iniciarmos nesta jornada, é essencial configurar o seu ambiente de desenvolvimento e ajustá-lo da forma que faz mais sentido para você, dev. Este guia tem como objetivo te ajudar a preparar um ambiente adequado para rodar seus códigos de forma eficiente.  

### ⚠️ Importante: Este guia é voltado para programadores de **DADOS**

Grande parte do conteúdo deste repositório será focado no fluxo de trabalho que envolve **Inteligência Artificial (IA), Machine Learning (ML) e pipelines de coleta e processamento de dados**. Todavia, isso não impede que você que quer aprender Python para fazer apps, automações e outros tipos de atividade não tire proveito dos conhecimentos daqui.

Essas tarefas costumam ser **computacionalmente intensivas**, ou seja, rodar o código localmente pode não fazer muito sentido (principalmente se o seu computador for daqueles que esquenta até mesmo jogando um Subway Surfers hahaha).  

Felizmente, iremos superar essa barreira computacional mais adiante no guia com o uso de **computação em nuvem** e **APIs** que processarão os dados por nós e são a forma que as empresas fazem para processar grandes volumes de dados em ambientes reais de trabalho.  

Para dar os primeiros passos, você NÃO precisa do computador mais potente que o dinheiro possa comprar. Afinal, existem ambientes de desenvolvimento online como:  

- **Google Colaboratory** ([Google Colab](https://colab.research.google.com))  
- **Kaggle Notebooks** ([Kaggle](https://www.kaggle.com))  

Esses serviços rodam na nuvem, e possuem um poder computacional decente, são gratuitos (mas você pode optar por pagar um plano premium se quiser mais poder computacional), e não tem necessidade de uma extensa configuração (já que já vêm com quase tudo instalado - Python, bibliotecas, interface para fazer os códigos...). Basta acessar, escrever seu código e rodar. **Simples assim.**  

### Sobre o lado bom e o lado ruim dos ambientes online

#### ✅ **Vantagens do Google Colab e Kaggle**  

- ✔️ Fácil de usar
- ✔️ Não precisa instalar (quase) nada - existem alguns pacotes muito específicos que as vezes precisamos intalar, mas resolvemos isso com uma linha de código.
- ✔️ Acesso gratuito a GPUs e TPUs  
- ✔️ Perfeito para testar e explorar código  

#### ❌ **Desvantagens**  

- ❌ Limitado para projetos maiores e produção  
- ❌ Depende da conexão com a internet  
- ❌ Sem controle total sobre o ambiente  
- ❌ O formato `.ipynb` (Jupyter Notebook) não é o mais adequado para projetos robustos.

### 🔧 Mas então, Davi? Como você configuraria o seu setup de desenvolvimento?

Eu não vou mentir,  no início do meu aprendizado, utilizar plataformas online foi extremamente cômodo e simples. Como mencionei, quase não há necessidade de configuração, e é muito fácil começar. No entanto, à medida que fui evoluindo como programador, tendo mais contato com ambientes de trabalho e aprendendo mais sobre desenvolvimento — inclusive em outras linguagens —, percebi que fazia cada vez menos sentido depender apenas dos notebooks.

Óbvio, os notebooks ainda são essenciais para mim em vários projetos e vocês verão isso na prática. No entanto, acredito que o ideal seja iniciar com Python da mesma forma que outros desenvolvedores começam com suas respectivas linguagens: baixando a linguagem, configurando uma IDE (uma interface para desenvolver código), trabalhando com repositórios, gerenciando pacotes, aprendendo a criar e administrar ambientes virtuais (environments) onde instalaremos nossas ferramentas de desenvolvimento, entre outras boas práticas de desenvolvimento que ajudarão você a se tornar um dev independente e que vai conseguir abstrair mais facilmente as coisas que aprende para outras tarefas de computação.

Então, eu sinceramente **recomendo que você tenha o seu próprio computador**. Como disse, ter um computador não é essencial para aprender - você não só pode, como **DEVE** sim iniciar pelas interfaces da web se não conseguir acesso a um computador de imediato.

### 💻 Dito isso, o seu computador não precisa ser o mais top do mundo, um bom computador para desenvolver seria

- Um processadorzinho maneiro: **Ryzen 5 5600X**, **Intel i5-12600K** ou superior (pra evitar travamentos chatinhos)
- **16GB de memória RAM** (ou mais, especialmente para quem trabalha com dados e IA).
- **SSD de pelo menos 512GB**, para garantir espaço suficiente para seus projetos e arquivos.
- **Sistema operacional de sua preferência** (Windows, Linux ou macOS).
- **Placa de vídeo dedicada** (opcional, mas recomendável): Uma **RTX 3050** já ajuda bastante, ou uma opção mais acessível, como a **GTX 1660 Super**, pode ser uma boa escolha para quem pretende trabalhar com Machine Learning e IA.

Eu definitivamente não sou o mais "sabido" da montagem de computadores mas eu acredito que essa seja uma configuração BEM legal para inciar o seu desenvolvimento. Eu sei que é "carinho" mas um notebook é um investimento que todo programador uma hora ou outra vai ter que fazer, mas um **bom notebook ou desktop** é uma ferramenta essencial para qualquer programador. No final das contas, vale a pena investir em um equipamento que não te deixe na mão.

A título de curiosidade, aqui está o meu setup atual:

- **Processador: Intel Core i7-11800H**
- **Memória RAM: 16GB** (eu sei, preciso fazer um upgrade hahaha)
- **Armazenamento: 1TB SSD**
- **Placa de vídeo: RTX 3070** (versão para notebook)
- **OS: Windows 11 com WSL2** (Windows Linux Subsystem) - vou entrar em mais detalhes sobre o sistema operacional na parte 2 desse guia.

Enfim, sobre computadores é isso, vale dar uma olhada em vídeos no youtube também e em outras fontes confiáveis.

Com essa introdução sobre hardware, encerramos a Parte 1 um do nosso guia sobre a configuração que eu recomendo para desenvolver em Python em 2025. Na Parte 2, entraremos em mais detalhes sobre, sitema operacional, softwares e o ambiente em si. Te vejo lá meu guerreiro!! 
