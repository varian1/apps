---
title: Scanner OCR: Imagem em Texto
name: OCRScanner
tagline: Transforme papel em texto editável no celular. Pesquise, copie e envie em PDF.
project: OCRScanner
package: io.github.varian1.ocrscanner
version: 1.2.0
updated: 2026-11-21
privacy: https://varian1.github.io/ocrscanner/privacy.html
---

## O que o app faz

O OCRScanner fotografa uma página de papel, endireita a imagem e lê o texto no seu celular. Você pode editar e copiar o texto, pesquisar em todas as digitalizações que fez e compartilhar uma digitalização como PDF pesquisável, arquivo de texto ou imagem.

- O reconhecimento de texto roda no seu aparelho e funciona sem internet.
- Sem conta. Suas digitalizações ficam no seu celular e nunca são enviadas.
- Importe um PDF ou compartilhe imagens de outros apps no Android.
- Grátis com anúncios. Uma compra única do Premium remove os anúncios e adiciona mais idiomas.

## Primeiros passos

1. Abra o OCRScanner. A lista **Scans** está vazia na primeira vez.
2. Toque em **Scan** para usar a câmera ou em **Import** para escolher fotos que você já tem.
3. Permita o uso da câmera quando o Android perguntar. Importar não exige acesso a toda a sua galeria de fotos.

![A lista Scans com os botões Scan e Import](shots/01-home.png)

## Digitalizar uma página

1. Toque em **Scan** e aponte a câmera para a página. Toque no botão do obturador para tirar a foto.
2. Em **Review**, as bordas da página são encontradas para você. Arraste um canto azul se alguma borda estiver errada ou toque em **Full page** para manter a foto inteira.
3. Escolha um filtro para limpar a página: **Original**, **Magic**, **Gray** ou **B&W**.
4. Toque em **Rotate 90°** se a página estiver de lado ou em **Retake** para fotografar de novo.
5. Toque em **Recognize text**.

![Tela Review com os cantos da página, os filtros e o botão Recognize text](shots/02-review.png)

Para digitalizar várias páginas em um só documento, abra a digitalização depois, toque em **⋯** e escolha **Add pages**.

## Importar um PDF

O OCRScanner lê até 20 páginas de um PDF, ou 50 com o Premium. Cada página é lida como imagem, então o texto que já existe dentro do PDF não é usado.

1. Escolha um PDF no seletor de arquivos do celular. Não é preciso permissão de armazenamento.
2. Em **Review**, confira as páginas. Se o PDF for maior que o limite, a tela Review informa quantas páginas ficaram de fora.
3. Toque em **Recognize text**.

## Compartilhar imagens de outros apps

Isso funciona no Android.

1. Na galeria ou em outro app, selecione até 20 imagens e toque em compartilhar.
2. Escolha OCRScanner.
3. Desbloqueie o app se **App lock** estiver ativado. As imagens abrem em **Review** como uma nova digitalização.

Se houver páginas abertas que ainda não foram salvas, o app pergunta antes de substituí-las.

## Ler, editar e copiar o texto

1. Depois do reconhecimento, **Result** mostra a página em cima e o texto embaixo.
2. Toque em uma linha de texto para ver onde ela está na página. Toque em uma palavra na página para ir até a linha dela.
3. As linhas das quais o app não tem certeza ficam destacadas, assim você sabe o que conferir.
4. Toque em **Edit** para corrigir o texto, em **Copy** para copiá-lo ou em **Share** para enviá-lo.
5. Toque em **Save** para guardar a digitalização na sua lista.

![Tela Result: a página em cima, o texto reconhecido embaixo, com Edit, Copy, Share e Save](shots/03-result.png)

## Encontrar uma digitalização pelo texto

1. Em **Scans**, toque em **Search text in your scans**.
2. Digite uma palavra. Todas as digitalizações que a contêm aparecem na lista, com o trecho encontrado em negrito.
3. Toque em um resultado para abrir a digitalização naquele trecho.

![A busca pela palavra "lighting" encontra a digitalização que a contém](shots/04-search.png)

Para ver só as digitalizações com uma etiqueta, toque nela abaixo do campo de busca. A busca passa a olhar apenas dentro dessas digitalizações. Toque na etiqueta de novo para ver todas.

## Compartilhar ou exportar

1. Abra uma digitalização e toque no botão de compartilhar.
2. Escolha um formato:
   - **PDF**: as imagens das páginas com o texto pesquisável por trás.
   - **Text file**: texto simples (.txt).
   - **Page image**: salve na galeria ou envie.
3. Escolha o app para o qual quer enviar.

![Folha de compartilhar ou exportar com PDF, Text file e Page image](shots/05-share.png)

## Renomear, etiquetar e excluir

1. Abra uma digitalização e toque em **⋯**.
2. Escolha **Rename** para mudar o título ou **Edit tags** para adicionar etiquetas separadas por vírgulas.
3. Escolha **Recognize text again** para ler as páginas de novo em outro idioma de texto. Qualquer texto que você tenha editado será substituído.
4. Escolha **Delete scan** para remover a digitalização do seu celular.

## Fazer backup e restaurar suas digitalizações

1. Em **Scans**, toque no ícone de configurações no canto superior direito.
2. Em **Storage**, toque em **Back up scans**. Todas as suas digitalizações são reunidas em um único arquivo.
3. Escolha onde salvar ou para onde enviar o arquivo. Ele não é criptografado, então guarde-o em um lugar seguro.
4. Em um celular novo, toque em **Restore from backup** e escolha o arquivo. O app pergunta antes de substituir todas as digitalizações do celular pelas que estão no backup.

## Bloquear o app e mudar as configurações

1. Em **Scans**, toque no ícone de configurações no canto superior direito.
2. Ative **App lock** para exigir sua impressão digital, seu rosto ou o bloqueio de tela antes de abrir as digitalizações.
3. Em **Text language (OCR)**, escolha a escrita dos seus documentos. **Latin** cobre português, inglês, espanhol, francês, alemão, indonésio e mais. O app sugere a que o idioma do seu celular usa.
4. Toque em **App language** para usar o app em um idioma diferente do celular.
5. Escolha a **Image quality** (Balanced ou Full) e o **Theme** (System, Light ou Dark).

![Configurações: Premium, App lock, Text language (OCR) e Image quality](shots/06-settings.png)

## Premium

O Premium é um pagamento único, não uma assinatura. Abra **Settings** e toque em **See Premium**. Ele oferece:

- Sem anúncios.
- Texto em chinês, japonês e coreano, além de hindi e outros textos em devanágari no Android.
- Reunir várias digitalizações em um só PDF ou arquivo de texto.
- Importação de PDFs maiores: até 50 páginas em vez de 20.

Se você já comprou o Premium, toque em **Restore purchase** na tela do Premium.

## Perguntas

**Funciona offline?**
Sim. Digitalização, reconhecimento de texto, busca e exportação rodam no seu celular.

**Onde ficam as minhas digitalizações?**
Somente no seu aparelho. Se você desinstalar o app, as digitalizações são removidas junto. Por isso, toque antes em **Back up scans** em Settings para guardá-las.

**O texto veio com erros. O que posso fazer?**
Tire a foto de novo com boa luz e a página bem plana, teste o filtro **Magic** ou **B&W** e confira se **Text language (OCR)** corresponde ao documento. Você também pode corrigir palavras soltas com **Edit**.

**Ele lê letra de mão?**
Ele foi feito para texto impresso. A letra de mão costuma ser lida errado.

## Privacidade

Seus documentos nunca são enviados. A versão gratuita mostra anúncios do Google AdMob. Leia a [política de privacidade](https://varian1.github.io/ocrscanner/privacy.html) completa.
