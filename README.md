# Estudos de TypeScript

Repositório com meus estudos de TypeScript. Cada assunto fica em uma pasta própria.

## Assuntos

| Pasta | Assunto |
| --- | --- |
| [01-arrays-e-tuplas](01-arrays-e-tuplas/) | Tipando arrays e tuplas |

## Como adicionar um novo assunto

1. Crie uma pasta na raiz seguindo a numeração: `02-nome-do-assunto/`
2. Coloque os arquivos `.ts` dentro dela (ex.: `02-nome-do-assunto/main.ts`)
3. Adicione uma linha na tabela acima

Não é preciso criar `package.json` ou `tsconfig.json` nas pastas: a configuração da raiz vale para todas.

## Comandos

```bash
npm install      # instala o TypeScript (só na primeira vez)
npm run build    # compila tudo para a pasta dist/
npm run watch    # recompila automaticamente ao salvar
```

O resultado do build espelha as pastas: `01-arrays-e-tuplas/main.ts` vira `dist/01-arrays-e-tuplas/main.js`.
