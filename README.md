# ORVION — publicação da landing

Site: https://orvion-landing.netlify.app/

Este repositório contém a exportação estática da landing institucional.
Código-fonte, testes e documentação: https://github.com/guiizao14/orvion
Commit de origem: 0d676ab

## Atualizar

1. No repositório `orvion`, execute `pnpm install --frozen-lockfile` e `pnpm build:landing`.
2. Execute a validação descrita em `landing/README.md` daquele repositório.
3. Sincronize o conteúdo de `dist/landing-site/` com a raiz deste repositório.
4. Faça commit e push para `main`. A conexão existente do Netlify publica os arquivos.

Configuração preservada: sem comando de build, diretório de publicação `.`.
Não é necessário domínio próprio nem serviço pago adicional.

## Arquivos

- `index.html`: landing compilada.
- `assets/`: CSS, JavaScript leve e fontes locais.
- `brand/`: versões vetoriais da identidade ORVION, símbolo animado e favicon.
- `logo.jpg`: referência histórica preservada; não é usada na nova página.

O dashboard e as integrações permanecem no repositório de origem, fora desta publicação.
WhatsApp oficial: https://wa.me/5527999408858
