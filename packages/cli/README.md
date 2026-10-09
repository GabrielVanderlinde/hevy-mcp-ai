# Hevy CLI

Cliente de terminal para a API do Hevy, originário do projeto [chrisdoc/hevy-mcp](https://github.com/chrisdoc/hevy-mcp). Este pacote permite consultar dados de treinos e executar operações de criação e atualização compatíveis com a API.

## Requisitos

- Node.js 24 ou superior
- Conta Hevy PRO
- Chave de API do Hevy

## Instalação

```bash
npm install -g @chrisdoc/hevy-cli
export HEVY_API_KEY=sua_chave_de_api
hevy --help
```

O cliente lê a chave exclusivamente da variável de ambiente `HEVY_API_KEY`. Não passe a chave em argumentos, URLs ou arquivos versionados.

## Exemplos

Listar treinos:

```bash
hevy workouts list --page-size 10
```

Pesquisar exercícios:

```bash
hevy exercises search "bench press"
```

Listar rotinas em JSON:

```bash
hevy routines list --json
```

## Alteração de dados

Comandos de criação e atualização exigem os dados de entrada e confirmação explícita com as opções `--data` e `--yes`. Revise a ajuda do comando antes de executar operações que alteram seus dados.

**Exclusão de dados não é suportada pelo CLI.**

## Documentação e créditos

Este pacote faz parte do fork [GabrielVanderlinde/hevy-mcp-ai](https://github.com/GabrielVanderlinde/hevy-mcp-ai) e deriva do projeto original [chrisdoc/hevy-mcp](https://github.com/chrisdoc/hevy-mcp). Consulte o repositório de origem para detalhes completos e atualizados sobre comandos e compatibilidade.