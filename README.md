# Estudos em TypeScript

Repositório focado em estudos sobre TypeScript. Este projeto será atualizado com novos tópicos e exemplos conforme o progresso dos estudos.

## Índice

- [Descrição do Projeto](#descrição-do-projeto)
- [Configuração do TypeScript](#configuração-do-typescript)
- [Comandos Úteis](#comandos-úteis)
- [Próximos Tópicos](#próximos-tópicos)
- [Contribuição](#contribuição)

## Descrição do Projeto

Este repositório contém exemplos e práticas de programação utilizando TypeScript, visando facilitar o aprendizado e a compreensão das funcionalidades da linguagem.

## Configuração do TypeScript

Siga os passos abaixo para configurar um projeto TypeScript:

1. **Inicializar um projeto Node.js**:
   ```bash
   npm init -y
   ```

2. **Instalar o TypeScript**:
   - Instalação global:
     ```bash
     npm install -g typescript
     ```
   - Instalação local (recomendado para projetos):
     ```bash
     npm install typescript --save-dev
     ```

3. **Configurar o TypeScript**:
   - Para criar um arquivo de configuração `tsconfig.json`:
     ```bash
     npx tsc --init
     ```

4. **Transpilar o código TypeScript para JavaScript**:
   - Para compilar todos os arquivos `.ts` no diretório atual:
     ```bash
     npx tsc
     ```
   - Para transpilar um arquivo específico e acompanhar as mudanças:
     ```bash
     npx tsc nome-do-arquivo.ts --watch
     ```

## Comandos Úteis

Aqui estão alguns comandos adicionais que podem ser úteis durante o desenvolvimento:


- **Compilar e assistir mudanças em um diretório específico**:
  ```bash
  npx tsc -p ./caminho/do/diretorio --watch
  ```
  

- **Verificar erros de tipo sem compilar**:
  ```bash
  npx tsc --noEmit
  ```


- **Executar o código JavaScript gerado** (supondo que você tenha um arquivo `index.js`):
  ```bash
  node index.js
  ```


## Próximos Tópicos

Fique atento para novos tópicos e exemplos que serão adicionados a este repositório!


## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.
