# Hevy MCP Server

Servidor do Model Context Protocol (MCP) para integrar dados de treinos do Hevy a clientes compatíveis, como assistentes de programação e outras aplicações que suportam MCP. Este código deriva do projeto original [chrisdoc/hevy-mcp](https://github.com/chrisdoc/hevy-mcp).

## Recursos

Conforme as ferramentas disponíveis na versão utilizada, o servidor permite consultar informações do Hevy e executar operações compatíveis com a API, como trabalhar com treinos, rotinas, exercícios e outros recursos relacionados.

O conjunto exato de ferramentas, parâmetros, modos de transporte e opções de hospedagem pode mudar entre versões. Consulte o código e a documentação do projeto original para obter a referência completa.

## Requisitos

- Node.js 20 ou superior
- Chave de API do Hevy
- Cliente compatível com MCP

## Configuração

Mantenha a chave de API em uma variável de ambiente, normalmente chamada `HEVY_API_KEY`, de acordo com a configuração exigida pela versão. Nunca inclua chaves reais em commits, logs públicos ou documentação.

## Desenvolvimento

A partir da raiz do monorepositório, instale as dependências conforme as instruções do projeto e utilize os scripts definidos em `package.json`. Entre os comandos disponíveis no workspace estão:

```bash
npm test
npm run build
```

Alguns testes e fluxos de desenvolvimento podem exigir ferramentas adicionais ou variáveis de ambiente. Consulte os scripts e os arquivos de configuração antes de executar.

## Projeto de origem e créditos

Este repositório é um fork de [chrisdoc/hevy-mcp](https://github.com/chrisdoc/hevy-mcp). A implementação original, seu histórico e os créditos pertencem ao projeto de origem e seus colaboradores. Preserve os avisos de licença e autoria presentes no código.

- Repositório original: https://github.com/chrisdoc/hevy-mcp
- Licença: MIT (consulte o arquivo `LICENSE`)

Para instruções detalhadas de instalação, ferramentas disponíveis, configuração de transporte, observabilidade e hospedagem, consulte a documentação do projeto upstream.