## App CallKeep 📱

---

## 📝Sumário

- [Descrição](#📖Descrição)
- [Instalação](#📦Instalação)
- [Configurações](#⚙Configurações)
- [Uso](#✅Uso)

##

## 📖Descrição

Esse aplicativo é construído em **_React Native_**, utilizando uma biblioteca fantástica (_[React Native CallKeep](https://github.com/react-native-webrtc/react-native-callkeep)_) para manipular as chamadas nativas do celular atráves do aplicativo, criando inifinas possibilidades de uso, como serviços VOIP, IoT e muito mais. Esse aplicação funciona juntamente com (_[Backend App Callkeep](https://github.com/thompsons3/backend-app-callkeep.git)_) para realizar uma "chamada" remota.

##

## 📦Instalação

Siga os comandos abaixo para instalar essa aplicação em sua máquina.

```bash
# Clonando o repositório da aplicação.

git clone https://github.com/thompsons3/app-callkeep.git
```

```bash
# Entrando na pasta da aplicação.

cd app-callkeep/
```

```bash
# Comando para instalar os pacotes necessários da aplicação.

npm i
```

##

## ⚙Configurações

> 1º Passo

Você precisar ter uma conta no google e criar um projeto no firebase. Você pode está criando aqui: _[Firebase Console](https://console.firebase.google.com/)_.

> 2º Passo

Depois de ter criado o seu projeto, clique em _Visão geral do projeto -> Configurações do projeto -> Geral._

Em _Seus aplicativos_ e clique em _📥 google-services.json_ (Download).

> 3º Passo

Feito o download desse arquivo, mova o arquivo para dentro de _android/app_. *O nome do arquivo deve permanecer o mesmo (google-services.json)*

##

## ✅Uso

```bash
# Comando para instalar o aplicativo no seu celular ou emulador.

npm run install-android
```

```bash
# Comando para rodar a aplicação.

npm start
```
