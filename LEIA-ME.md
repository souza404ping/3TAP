# Tritap — código-fonte

Site em português inspirado visualmente na Revolut, com a identidade e as imagens da Tritap.

## Executar

Requer Bun. Na pasta do projeto:

```sh
bun install
bun run dev
```

Para gerar a versão de produção: `bun run build`.
Para executar os testes: `bun run test`.

## Conteúdo

- Página: `src/routes/index.tsx`
- Estilos: `src/styles.css`
- Imagens: `src/assets/` (incluídas como arquivos locais, sem depender dos endereços de mídia da Lovable)
- Ícone: `public/favicon.png`

Os contatos levam ao Instagram oficial informado: https://www.instagram.com/somostritap/. Não há formulário de envio, WhatsApp não configurado ou botões de ações indisponíveis.

O projeto usa React, TanStack Start e Tailwind CSS. O pacote contém código-fonte e imagens, sem dependências instaladas ou arquivos compilados. Não é uma página HTML única. As dependências e a configuração original do projeto estão preservadas.
