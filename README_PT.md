# Seedance 2.5: biblioteca de prompts da bestimage.ai

[English](README.md) · [简体中文](README_ZH.md) · [日本語](README_JA.md) · [Español](README_ES.md) · [Todos os 15 idiomas](prompts/i18n/README.md)

![Capa conceitual da biblioteca Seedance 2.5](assets/seedance-2-5-cover.png)

Mantida pela **equipe bestimage.ai**, esta coleção reúne **120 cenários únicos**: os 100 cenários da base foram reescritos e outros 20 foram acrescentados. A organização é de **60 cenas principais em chinês, 40 cenas principais em inglês e 20 cenas novas em chinês e inglês**. As duas versões das 20 cenas novas representam os mesmos cenários, não 40 cenas diferentes.

O suporte a 15 idiomas consiste em **seis exemplos compartilhados por idioma**. O português do Brasil tem seis receitas completas; não é uma tradução integral das 120 cenas. As imagens são ilustrações conceituais, não resultados gerados pelo Seedance. Confira os vídeos gerados antes de usar ou publicar.

## Comece por aqui

- Copie os [6 prompts completos em português do Brasil](prompts/i18n/prompt-library.pt-BR.md).
- Encontre um cenário no [índice com 120 cenas](prompts/README.md).
- Explore os 20 novos fluxos de produção em [inglês](prompts/production-workflows.en.md) ou [chinês](prompts/production-workflows.zh.md).
- Use o [guia avançado de prompts](docs/prompting-guide.md) para câmera, ritmo, áudio e consistência.
- Consulte o [guia de integração com a bestimage.ai](docs/bestimage-ai-api-guide.md).

## Escolha o fluxo adequado

| Necessidade | Entrada na bestimage.ai | Função |
| --- | --- | --- |
| Criar vídeo a partir de uma descrição | [Seedance 2.5 de texto para vídeo — página em inglês](https://bestimage.ai/models/bytedance/seedance-2-5-text-to-video/) | Começar com o texto da cena. |
| Animar um quadro inicial | [Seedance 2.5 de imagem para vídeo — página em inglês](https://bestimage.ai/models/bytedance/seedance-2-5-image-to-video/) | Usar uma imagem como primeiro quadro. |
| Orientar o vídeo com materiais de referência | [Seedance 2.5 de referências para vídeo — página em inglês](https://bestimage.ai/models/bytedance/seedance-2-5-reference-to-video/) | Definir a função de cada referência; este modo exige pelo menos um vídeo de referência. |
| Preparar imagens estáticas e quadros de roteiro visual | [API GPT Image 2 — página em inglês](https://bestimage.ai/models/openai/gpt-image-2/) | Gerar imagens em um fluxo separado; não é uma API de vídeo. |

> Parâmetros, preços, requisitos de entrada e esquemas de API podem mudar. Confira as páginas atuais e o guia de integração antes de enviar solicitações. As durações dos roteiros são orientações criativas, não uma garantia de suporte da API.

## Estrutura recomendada

```text
[Objetivo] público, canal, duração e proporção
[Referências] uma função clara para cada imagem ou vídeo
[Invariáveis] identidade, produto, cenário e luz que não podem mudar
[Linha do tempo] abertura → ação → virada → quadro final
[Câmera] enquadramento, altura, trajeto, velocidade, foco e parada
[Áudio] fala, ambiente, efeitos, música e pontos de sincronização
[Evitar] deriva, duplicação, anatomia, texto falso, logotipos e marca-d'água
```

Antes do uso comercial, revise autorizações de imagem, licenças, música, marcas, locais, alegações e regras da plataforma. Geometria, texto, fala e física precisam ser verificados no vídeo real.

## Contribuições

Consulte as [orientações de contribuição](CONTRIBUTING.md) e compartilhe um prompt original com configurações, entradas, estado de teste e, quando disponível, o resultado real. Não apresente uma proposta não testada como caso validado. Contribuições aprovadas podem ser publicadas com atribuição após revisão.

## Sobre a bestimage.ai

A equipe da [bestimage.ai](https://bestimage.ai/) seleciona e mantém esta biblioteca de prompts, conectando fluxos criativos a APIs de modelos de imagem e vídeo.

## Ganhe com o programa de afiliados da bestimage.ai

Você publica tutoriais, prompts ou integrações de API? Participe do [programa de afiliados da bestimage.ai](https://bestimage.ai/affiliate-program/) e receba comissões ao recomendar a bestimage.ai ao seu público.

- **20%** sobre o primeiro pedido pago válido de um usuário indicado.
- **10%** sobre os pedidos pagos válidos seguintes desse usuário, feitos nos **60 dias após o cadastro**.

A elegibilidade dos pedidos e os pagamentos seguem o [contrato de afiliados vigente](https://bestimage.ai/affiliate-agreement/).

## Licença

[MIT](LICENSE).
