# Alura Tracker

Projeto desenvolvido durante uma formação de Vue da Alura.

Este repositório faz parte da minha jornada de atualização, reciclagem de conhecimentos e aprendizado de novas tecnologias.

🔗 Certificado consolidado da Alura:

https://cursos.alura.com.br/user/juniorlatalisa/fullCertificate/a5efe6102aae667cfb7df33ca3c74d85

---

## Objetivo do Projeto

O Alura Tracker é uma aplicação utilizada para estudo dos principais conceitos do ecossistema Vue, incluindo:

- Componentização
- Propriedades (Props)
- Eventos
- Estado de componentes
- Reatividade
- TypeScript
- Boas práticas de desenvolvimento Front-end

---

## Tecnologias Utilizadas

- Vue.js
- TypeScript
- Vue CLI
- HTML5
- CSS3

---

## Ambiente de Desenvolvimento

### Instalação das dependências

```bash
npm install
```

### Compiles and hot-reloads for development

```bash
npm run serve
```

### Compiles and minifies for production

```bash
npm run build
```

### Lints and fixes files

```bash
npm run lint
```

### Customize configuration

Consulte a documentação oficial:

https://cli.vuejs.org/config/

---

## 📚 Anotações de Estudo

### Node.js 26 × Vue CLI

Durante a execução do projeto utilizando Node.js 26, foi encontrado o seguinte erro:

```text
ERR_OSSL_EVP_UNSUPPORTED
error:0308010C:digital envelope routines::unsupported
```

A causa está relacionada à compatibilidade entre versões recentes do Node.js/OpenSSL e dependências utilizadas pelo projeto do curso.

### Linux / macOS / Git Bash

```bash
export NODE_OPTIONS=--openssl-legacy-provider
```

### PowerShell

```powershell
$env:NODE_OPTIONS="--openssl-legacy-provider"
```

Após configurar a variável de ambiente:

```bash
npm run build
```

Essa observação foi registrada durante a realização da formação e poderá ser útil para outros estudantes utilizando versões recentes do Node.js.

---

## Autor

**Junior Latalisa**

☕ Java  
📱 Flutter  
🌐 Angular  
🏛️ Delphi  
📞 VoIP

Desenvolvedor desde 2000, em processo contínuo de atualização, reciclagem de conhecimentos e evolução técnica.