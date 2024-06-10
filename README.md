### Santander
# Treinamento Back-End Santander Coders 2024 

## 1.  Módulo de Git e Versionamento 
Verificar se git este intalado: git --version 
No VS Code baixar o gitLens/git --global user.name "FilipeMangue"/git --global user.email filipeemanuelmangue@gmail.com

# Repositórios do Git
cd caminho-pasta para aceder a pasta e depois para clonar o projecto/repositório git usar o comando git clone caminho-do-repositorio 
git init para iniciar um repositório atraves de uma pasta simples.

# Comando git PUSH
Utilizado para permitir que as alterações no repositório local sejam guardadas remotamente.
Sintaxe: git push origin main

# Comando git PULL
Utilizado para permitir que as alterações no repositório remoto sejam guardadas localmente.
Sintaxe: git pull origin main

# Comando git FETCH
Utilizado para verificar as alterações no repositório remoto e local antes de sejam guardadas.
Sintaxe: git fetch + git diff origin main/master

## 2. Módulo de Redes e Sistemas

O que são redes? R: Um conjunto de dois ou mais dispositivos electrónicos ligados entre si que trocam informações utilizando uma linguagem pré-estabelecida designada por protocolo.

Isto acontece de duas formas: 
Fisicamente - através de cabos de pares entrelaçados. 
Sem fios/wireless - através de radiofrequência, bluetooth ou infravermelhos.

Origens: DARPA e ARPANET

## Estrutura de Redes e o Principais Equipamentos

A placa de rede (NIC - Network Interface Card), como é mais conhecida, é o dispositivo responsável por permitir a ligação do computador com um cabo ethernet ou por receber ondas de radiofrequência para ligações sem fios.

Ela possui dois endereços. Físico e Lógico
* Hub - é uma peça de hardware que permite a ligação de dispositivos através de cabos de par trançado. 

* Switch - responsável pela comutação de quadros entre dispositivos, podemos definir comutação como troca ou encaminhamento de informações.

* Router - responsável por encontrar as melhores rotas na Internet para entregar os pacotes do remetente ao destinatário no menor tempo possível.

* Modem - responsável pela modulação e desmodulação do sinal de Internet.

## Cabeamento Estruturado

Padrões estabelecidos que definem a forma como os cabos e os seus periféricos serão organizados, permitindo uma melhor organização e desempenho da rede.

Normas: NBR 14.565, ANSI/TIA 568, ANSI/TIA 569

* Cabos trançados - são divididos em categorias que determinam a velocidade de transmissão de dados e o alcance em metros que o cabo pode suportar sem perda de pacotes.

* Coaxial - composto por fios de cobre, com um fio central responsável pela condução do impulso eléctrico, uma malha metálica que proporciona isolamento e uma blindagem plástica contra interferências externas.

* Fibra óptica - tecnologia guiada por cabos que oferece as maiores velocidades de transmissão de dados, atingindo velocidades na faixa de Gbps. A fibra é composta por pedaços de vidro que permitem a propagação de raios luminosos que são convertidos por conversores nas extremidades das fibras.