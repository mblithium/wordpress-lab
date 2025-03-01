# Meu ambiente de testes

Um ambiente de testes criado com base no wp-env.

## Requisitos

- NodeJS
- Docker

## Instalação

```bash
npm install
```

## Comandos

### Executar ambiente de testes:

```bash
npm start
```

### Encerrar ambiente e testes:

```bash
npm stop
```

### Resetar a instalação do WordPress:
(Apaga todos os posts, páginas, arquivos, entre outras coisas)

```bash
npm reset
```

### Recomeçar toda a instalação do WordPress:
(Joga uma bomba na instalação do ~/.wp-env e recomeça)

```bash
npm nuke
```

### Executar o WP-CLI

```bash
npm wp-cli ["comando do wp-cli aqui"]
```

**Exemplo:**

```bash
npm wp-cli plugin list
```
