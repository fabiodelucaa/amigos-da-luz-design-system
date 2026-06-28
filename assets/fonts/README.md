# Fontes

Esta pasta reúne os arquivos de fonte fornecidos para uso no design system da Amigos da Luz.

## Arquivos

- `mokoko.zip` — pacote da família Mokoko, fonte de display da marca.
- `roboto.zip` — pacote da família Roboto, fonte de corpo, UI e informações práticas.

## Uso no design system

- **Mokoko** deve ser usada em títulos, chamadas editoriais, nomes de espetáculos, cartazes e momentos de maior presença teatral.
- **Roboto** deve ser usada em texto corrido, legendas, botões, formulários, metadados e interfaces.

## Cuidados de licença

- Os arquivos foram adicionados como assets de referência para configuração do design system.
- Antes de redistribuir, publicar em produção ou incorporar em produtos finais, confirme se a licença de cada família permite o uso pretendido.
- Roboto inclui `NOTICE.txt` no pacote original.
- Mokoko não trouxe arquivo de licença separado dentro do zip recebido; manter atenção especial a esse ponto antes de redistribuição ampla.

## Observação técnica

Os arquivos estão preservados como `.zip` para manter os pacotes originais. Se uma aplicação web precisar carregar fontes diretamente, extraia apenas os formatos necessários, preferencialmente `woff2`, e declare `@font-face` no projeto consumidor.
