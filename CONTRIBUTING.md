# Como contribuir

## Rodar o projeto

Requer Node 24 ou mais recente. No repositório `biocoleta`:

```bash
npm install
npm run dev
```

Antes de enviar uma mudança:

```bash
npm run lint
npm run typecheck
npm run test
npm run e2e
```

## Fluxo de trabalho

1. Abra uma issue com o modelo de especificação, ou o de bug.
2. Crie uma branch a partir da `main`.
3. Faça commits pequenos, em inglês, no padrão Conventional Commits, citando a issue: `feat(map): add district filter (#42)`.
4. Abra o pull request e peça a revisão de ao menos um integrante.

Um push na `main` publica o site depois que todas as verificações passam.

## Idioma

Textos da interface, issues e pull requests em português. Código e commits em inglês.

## Definição de pronto

- Critérios de aceite atendidos e demonstráveis
- Testes das regras e componentes novos
- Lint, tipos, testes e build passando
- Telas funcionando nos temas claro e escuro, em computador e celular
- Revisão de ao menos um integrante
