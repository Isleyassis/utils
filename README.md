@isley/utils

[![npm version](https://img.shields.io/npm/v/@isley/utils.svg?style=flat-square)](https://www.npmjs.com/package/@isley/utils)
[![License](https://img.shields.io/npm/l/@isley/utils.svg?style=flat-square)](https://opensource.org/licenses/MIT)

Uma pequena biblioteca de utilitários JavaScript desenvolvida para facilitar operações comuns em projetos modernos.  
Atualmente, inclui funções básicas de manipulação de números, começando com a função `sum`.

---

## Instalação

Instale via npm:

```bash
npm install @isley/utils
```

## Funções disponíveis
Atualmente, esta biblioteca inclui apenas a função sum.

```bash
sum(a, b)
```

Retorna a soma de dois números.

Parâmetros:

**a** (**number**) — Primeiro número.

**b** (**number**) — Segundo número.

Retorno:
**number** — resultado da soma.

Exemplo de uso:
```bash
import { sum } from "@isley/utils";

const result = sum(5, 10);
console.log(result); // 15
```