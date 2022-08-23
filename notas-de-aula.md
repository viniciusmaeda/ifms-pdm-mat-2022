# Notas de aula

## Principais comandos utilizados no terminal do Windows

Navegar entre as pastas

> cd

Limpar a tela

> cls
> clear

Listar o conteúdo de uma pasta

> dir

Criar uma pasta em branco

> mkdir **nome-da-nova-pasta**

Remover uma pasta

> rmdir **nome-da-pasta**

Abrir o VS Code na pasta do projeto

> code .

## Ferramentas para desenvolver em React Native

1. Android Studio -> SDK e AVD
2. NodeJS
3. Visual Studio Code / Atom -> editores de código
4. Expo (framework) -> instalado no computador. Executar o comando abaixo uma única vez para instar o Expo.
   > npm install --global expo-cli
5. Expo Go (visualizador no celular) -> instalar no celular

## Comandos para abrir uma AVD fora do Android Studio

Listar as AVDs (Android Virtual Device)

> emulator -list-avds

Abrir um AVD

> emulator -avd **nome-da-avd**

## Comandos utilizados para criar um projeto

Criar um projeto React Native (Expo)

> expo init **nome-do-projeto**

Rodar o projeto React Native no AVD

> expo start --android
