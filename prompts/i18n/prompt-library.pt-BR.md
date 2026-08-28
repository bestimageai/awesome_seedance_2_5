# Seedance 2.5: seis receitas de prompts em português do Brasil

[Todos os idiomas](README.md) · [Índice com 120 cenas](../README.md) · [Início](../../README.md)

Mantidas pela **equipe bestimage.ai**. Estas seis receitas localizadas correspondem às cenas 04, 31, 37, 43, 46 e 52 do catálogo principal. São traduções e adaptações dos mesmos cenários, não seis prompts únicos adicionais. Não constituem uma tradução integral do catálogo chinês para português. As propostas criativas não foram testadas; geometria exata, texto, fala e física devem ser conferidos nos resultados reais.

Para um único quadro inicial, use [Seedance 2.5 de imagem para vídeo](https://bestimage.ai/models/bytedance/seedance-2-5-image-to-video/). Para vários materiais de referência, o modo [de referências para vídeo](https://bestimage.ai/models/bytedance/seedance-2-5-reference-to-video/) também exige um vídeo de referência: defina explicitamente sua função. A [API GPT Image 2](https://bestimage.ai/models/openai/gpt-image-2/) é um fluxo separado de geração de imagens para preparar quadros de roteiro visual, não um ponto de acesso de vídeo. Leia o [guia de integração](../../docs/bestimage-ai-api-guide.md). As páginas de produto vinculadas estão em inglês.

## I18N-01. Coador de café de cerâmica: um despejo controlado

Cena do catálogo: **04** · Modo: imagem para vídeo · Duração: **20 segundos** · Formato: **16:9**

```text
Use Image 1 como quadro inicial: um coador de cerâmica azul-cobalto com seis nervuras externas, um filtro de papel branco com café moído seco e uma jarra transparente sobre calcário claro. Mantenha a quantidade de nervuras, a silhueta sem alça, as dobras do filtro, o contorno da jarra e a luz matinal vinda da esquerda. O produto não tem marca.

00:00–00:04: mantenha um enquadramento próximo do café moído seco; um bico de chaleira de pescoço de ganso em aço inoxidável entra pelo canto superior direito sem esconder o coador.
00:04–00:11: um único fio fino e contínuo de água desenha um pequeno círculo dentro do filtro. O café se expande suavemente; o líquido fica abaixo da borda do papel e goteja na jarra.
00:11–00:16: o fluxo para e o bico se retira. Afaste um pouco a câmera para revelar a jarra enchendo gradualmente; não gire o coador nem altere suas proporções.
00:16–00:20: mantenha o produto em uma vista limpa de três quartos, com espaço vazio à direita para inserir texto depois.

Áudio: água sendo despejada suavemente, gotas esparsas e som ambiente discreto; sem fala nem música. Preserve a continuidade do volume de líquido e o contato entre superfícies sólidas. Sem café flutuante, recipientes extras, texto legível, logotipos, nuvens de vapor ou marca-d'água. Altere a cor da cerâmica somente ao fornecer um novo quadro inicial correspondente.
```

## I18N-02. Sobrecamisa reversível: teste de vento e tecido

Cena do catálogo: **31** · Modo: referências para vídeo · Duração: **20 segundos** · Formato: **9:16**

```text
Image 1 define a identidade da pessoa adulta com autorização de uso de imagem. Image 2 define uma sobrecamisa sem marca, cor de ferrugem, com forro marfim, dois bolsos aplicados e cinco botões frontais. Video 1 fornece somente o giro lento de um quarto de volta e o fluxo de ar da esquerda para a direita; não copie a pessoa nem a roupa desse vídeo. Comece com a sobrecamisa aberta e a pessoa em pé na posição marcada do estúdio.

00:00–00:05: plano americano fixo; a pessoa levanta a barra esquerda aberta apenas o suficiente para mostrar o forro, com a mão segurando visivelmente o tecido.
00:05–00:12: a pessoa solta a barra e gira um quarto de volta em direção à esquerda do enquadramento. Um ventilador suave move a barra solta e o cabelo de forma consistente para a direita do enquadramento; ombros e costuras dos bolsos permanecem estáveis.
00:12–00:16: o fluxo de ar diminui. O tecido se acomoda com peso, sem voltar bruscamente à posição.
00:16–00:20: mantenha uma pose lateral relaxada, com a mesma altura de câmera e a mesma lente.

Áudio: ventilador discreto e movimento do tecido; sem diálogo. Sem inverter a roupa no corpo, trocar o figurino instantaneamente, acrescentar botões, retocar a pele, remodelar o corpo, inserir texto, logotipos ou marca-d'água. A cena ilustra o movimento do tecido, não um teste certificado de resistência ao vento.
```

## I18N-03. Aplicativo de leitura: salvar um trecho destacado

Cena do catálogo: **37** · Modo: referências para vídeo · Duração: **18 segundos** · Formato: **16:9**

```text
Image 1 é a tela de leitura aprovada, Image 2 é a mesma tela com um trecho selecionado e Image 3 é o estado aprovado da anotação salva. Todo o texto visível já foi fornecido em inglês. Video 1 controla apenas o trajeto do cursor e o momento dos cliques. Preserve a moldura do dispositivo, a tipografia, as quebras de linha, a posição de leitura e o sentido de leitura da interface; nunca invente o texto do artigo.

00:00–00:04: vista frontal fixa do dispositivo sobre uma mesa neutra; o ponteiro pausa ao lado do trecho mostrado em Image 2.
00:04–00:09: o ponteiro seleciona esse trecho uma única vez, seguindo Video 1. Reproduza exatamente o destaque aprovado sem deslocar as outras linhas.
00:09–00:14: clique uma vez no controle de salvar existente e passe para Image 3. Não acrescente notificação temporária, contador, avaliação nem menu ausente das referências.
00:14–00:18: mantenha o estado da anotação salva para inspeção. Sem movimento de câmera nem reflexos da tela sobre o texto.

Áudio: um clique discreto por clique visível; sem fala, digitação nem música. Rejeite letras alteradas, controles espelhados, destaques que se deslocam, ponteiros duplicados, logotipos ou marca-d'água. Para localizar a interface, forneça as três telas aprovadas no idioma de destino; não peça ao modelo de vídeo para traduzir a tela.
```

## I18N-04. Degelo: escoamento superficial e infiltração

Cena do catálogo: **43** · Modo: referências para vídeo · Duração: **24 segundos** · Formato: **16:9**

```text
Image 1 é um corte transversal aprovado por um educador, com um leito de solo inclinado, uma fina camada de neve e uma bandeja transparente de coleta na borda inferior. Image 2 fornece a sobreposição aprovada de setas, sem palavras nem números. Video 1 fornece apenas o ritmo da demonstração com câmera fixa. Mantenha constantes os limites das camadas e as dimensões da bandeja; esta é uma ilustração didática simplificada, não uma evidência experimental medida.

00:00–00:06: apresente todo o corte transversal com a câmera fixa. Mostre uma pequena quantidade de água de degelo se formando na divisa entre neve e solo.
00:06–00:13: deixe parte da água descer pela superfície em direção à bandeja; siga as setas superficiais de Image 2 sem aumentar a massa de neve.
00:13–00:19: mostre outra parte entrando nos poros da camada superior do solo, seguindo as setas descendentes aprovadas. Não a faça atravessar instantaneamente todas as camadas nem sugira que todos os solos se comportam da mesma maneira.
00:19–00:24: mantenha os dois trajetos juntos na mesma vista; as setas param de se mover antes do final.

Áudio: água suave e som ambiente discreto; sem narração nem música. Sem medições inventadas, inundações, solo desaparecendo, direções de fluxo contraditórias, rótulos, logotipos ou marca-d'água. Acrescente legendas explicativas revisadas na pós-produção.
```

## I18N-05. Casa com pátio: mostrar o trajeto real

Cena do catálogo: **46** · Modo: referências para vídeo · Duração: **24 segundos** · Formato: **16:9**

```text
Image 1 fornece a planta aprovada do térreo de uma casa estreita com pátio. Image 2 e Image 3 estabelecem o cômodo de entrada e o pátio exatamente como estão mobiliados. Video 1 é um passeio autorizado que controla o trajeto e a altura da câmera. Trate a planta como uma restrição espacial, não como uma imagem a exibir. Não invente vistas do andar superior.

00:00–00:06: comece logo após a entrada, na altura normal dos olhos de uma pessoa adulta e com perspectiva natural; mostre juntos o banco existente e a passagem para o pátio.
00:06–00:14: caminhe lentamente pelo trajeto de Video 1, mantendo a passagem à vista. Pare antes da soleira; a câmera não pode atravessar paredes, móveis nem vidros fechados.
00:14–00:20: entre no pátio pela abertura real e faça uma panorâmica suave em direção ao canteiro original.
00:20–00:24: pare e olhe para trás para que o público compreenda a ligação com o cômodo de entrada.

Áudio: passos mudam do piso interno para o pavimento do pátio, com ambiente externo tranquilo; sem narração. Preserve larguras das portas, níveis do piso, quantidade de móveis, direção da luz solar e distância percorrida. Sem distorção de lente ultragrande-angular, cômodos adicionados, melhorias de luxo, afirmações sobre a localização, placas legíveis ou marca-d'água.
```

## I18N-06. Caixa de transporte para gatos: uma primeira visita voluntária

Cena do catálogo: **52** · Modo: referências para vídeo · Duração: **18 segundos** · Formato: **9:16**

```text
Image 1 define um único gato adulto cinza e tigrado, cuja imagem tem uso autorizado. Image 2 define uma caixa de transporte flexível aberta, com parte externa azul-marinho, painel lateral de tela e porta frontal dobrada para baixo. Video 1 fornece apenas os movimentos tranquilos de aproximação e entrada. Mantenha consistentes as marcas da pelagem, o tamanho do corpo, as costuras da caixa, a abertura da porta e o padrão da tela.

00:00–00:05: câmera baixa e fixa na entrada da caixa. O gato se aproxima da caixa vazia e aberta, para e cheira a borda; ninguém o empurra nem o segura à força.
00:05–00:11: o gato entra voluntariamente, primeiro com as patas dianteiras e depois com as traseiras, mantendo contato visível com o chão. A caixa não se expande nem absorve o gato pela parede lateral.
00:11–00:15: o gato se vira uma vez dentro do espaço disponível e se acomoda de frente para a entrada aberta.
00:15–00:18: mantenha a pose relaxada. Deixe a porta totalmente aberta.

Áudio: contato suave das patas, movimento do tecido e som ambiente discreto; sem ronronar acrescentado nem sons de aflição. Sem sedação, manejo forçado, anatomia impossível, animal duplicado, certificação de segurança, texto, logotipos ou marca-d'água. Se o gato da referência não entrar por vontade própria, escolha outro vídeo autorizado em vez de roteirizar o uso de força.
```
