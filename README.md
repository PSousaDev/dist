## Descrição

Plugin do SPY TLD responsável por apresentar métricas do cenário de SOC, capturadas através de uma API integrada ao Tenable Nessus.

## Dependências da aplicação

- Node 16 LTS;
- Yarn (Opcional).

## Instalando dependências do projeto

```bash
$ npm install
# ou
$ yarn
```

## Compilando Aplicação

```bash
$ npm run watch
# ou
$ yarn watch
```

## Iniciando Aplicação

Para visualizar a aplicação, é necessário adicioná-la a uma instância do SPY TLD no caminho $SPY_FOLDER/data/plugins

Após adicionar, é necessário reiniciar a instância do SPY TLD, para que o plugin seja identificado.
