# Alura Tracker

Projeto desenvolvido durante a formação **Vue.js 3** da Alura.

Este repositório faz parte da minha jornada de atualização, reciclagem de conhecimentos e aprendizado de novas tecnologias, documentada em:

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

## 📝 Notas de Compatibilidade

Este projeto utiliza a versão do ecossistema Vue adotada pelo curso no momento de sua publicação.

Ao utilizar versões mais recentes do Node.js (22+), pode ocorrer o erro:

```text
ERR_OSSL_EVP_UNSUPPORTED
error:0308010C:digital envelope routines::unsupported
```

Caso isso aconteça, execute:

### Linux / macOS / Git Bash

```bash
export NODE_OPTIONS=--openssl-legacy-provider
```

### PowerShell

```powershell
$env:NODE_OPTIONS="--openssl-legacy-provider"
```

Após configurar a variável de ambiente, execute novamente:

```bash
npm run build
```