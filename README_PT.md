# Configuração do Fastfetch – Tema Gengar 👻

Bem-vindo à minha configuração do Fastfetch, inspirada no Gengar do Pokémon! Esta configuração combina tons escuros e vibrantes de roxo para criar uma estética fantasmagórica, mantendo todas as funcionalidades do terminal.

Personalizei o Fastfetch para exibir todas as informações importantes do sistema de forma organizada, com cores nos títulos e separadores para melhor visualização.

## 🌈 Tema & Logo

Logo: /etc/fastfetch/abc.png

Cores:

Principal: 38;2;138;43;226 (roxo Gengar)

Secundária: 38;2;75;0;130 (roxo escuro)

O logo aparece no topo, adicionando um toque personalizado inspirado na paleta do Gengar.

## ⚡ Configurações de Exibição

Separador: " "

Quebras adicionadas entre seções para maior clareza.

## 🖥️ Módulos & Configuração
### Informações do Sistema

OS – Sistema operacional (38;2;186;85;211)

KERNEL – Versão do kernel (38;2;186;85;211)

VERSION – Versão do Fastfetch (38;2;186;85;211)

UPTIME – Tempo de atividade (38;2;186;85;211)

PKGS – Pacotes instalados (38;2;186;85;211)

### Informações de Hardware

CPU – Processador (38;2;199;125;255)

GPU – Placa de vídeo (38;2;199;125;255)

RAM – Uso de memória (38;2;199;125;255)

DISK – Uso do disco (38;2;199;125;255)

SWAP – Uso do swap (38;2;199;125;255)

### Informações do Ambiente

WM – Gerenciador de janelas (38;2;160;32;240)

TERM – Emulador de terminal (38;2;160;32;240)

SHELL – Shell (38;2;160;32;240)

## Rede & Localidade

DATE – Data atual (38;2;138;43;226)

LOCAL IP – Endereço IP local (38;2;138;43;226)

PUBLIC IP – Endereço IP público (38;2;138;43;226)

LOCALE – Localidade do sistema (38;2;199;125;255)

Mídia

MUSIC – Status do player de música (38;2;199;125;255)

## 🎨 Cores

A configuração utiliza gradientes de roxo e índigo para combinar com a paleta do Gengar:

Roxo principal: 38;2;138;43;226

## 📌 Como usar o Fastfetch (configuração)

Verifique onde está o diretório de configuração

Rode o comando:

which fastfetch

Isso ajuda a confirmar se o Fastfetch está instalado corretamente.

Crie o diretório global (caso não exista)

Se não houver um diretório de configuração, crie um global com:

sudo mkdir -p /etc/fastfetch

Crie/edite o arquivo de configuração

Abra o arquivo para edição:

sudo nano /etc/fastfetch/config.jsonc

Cole a configuração

Depois disso, é só colar o conteúdo do arquivo de configuração dentro do config.jsonc.

Salve e saia

No nano:

CTRL + O → salvar
ENTER → confirmar
CTRL + X → sair

Execute o Fastfetch

Agora é só rodar:

fastfetch
