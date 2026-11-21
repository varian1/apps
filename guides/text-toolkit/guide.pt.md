---
title: Contador de Palavras e Texto
name: Text Toolkit
tagline: Conte palavras, mude maiúsculas, limpe, ordene e compare textos offline.
project: text-toolkit
package: io.github.varian1.texttoolkit
version: 1.0
updated: 2026-11-18
privacy: https://varian1.github.io/text-toolkit/privacy.html
---

## O que ele faz

O Text Toolkit tem uma única tela com nove ferramentas de texto. Digite ou cole o texto na caixa do topo, escolha uma ferramenta e copie ou compartilhe o resultado. Ele conta palavras, muda maiúsculas e minúsculas, limpa espaços, ordena linhas, localiza e substitui, inverte, codifica, formata JSON e compara dois textos.

- Todas as ferramentas funcionam no seu aparelho, sem internet.
- Sem conta. Seu texto nunca é enviado, e o app não usa câmera, fotos, contatos nem localização.
- Seu texto não é salvo. Ele some quando você fecha o app.
- Grátis. Um anúncio em banner pode aparecer na parte de baixo da tela.

## Primeiros passos

1. Abra o Text Toolkit. A caixa **YOUR TEXT** traz um texto de exemplo para você testar cada ferramenta.
2. Toque em **Clear** e digite seu próprio texto, ou toque em **Paste** para trocar o texto pelo que você copiou em outro app. **Sample** traz o texto de exemplo de volta.
3. Escolha uma ferramenta na linha abaixo da caixa: **Counter**, **Case**, **Clean**, **Lines**, **Replace**, **Reverse**, **Encode**, **Format** ou **Diff**. Deslize a linha para o lado para ver todas.

![Tela principal: a caixa YOUR TEXT com Paste, Sample e Clear, a linha de ferramentas e os números do Counter](shots/01-home.png)

O app usa o idioma do seu celular. Está disponível em 11 idiomas: inglês, espanhol, português, alemão, francês, hindi, indonésio, árabe, italiano, russo e turco.

## Contar palavras e caracteres

1. Toque em **Counter**.
2. Veja os números: **Characters**, **No spaces**, **Words**, **Sentences**, **Paragraphs**, **Lines** e **Reading time**.
3. Olhe **TOP WORDS** logo abaixo para ver as palavras que você mais usou, até oito, cada uma com sua contagem.

Os números mudam enquanto você digita. O tempo de leitura é calculado com 200 palavras por minuto.

## Mudar maiúsculas e minúsculas

1. Toque em **Case**.
2. Role pelos cartões. Cada um mostra seu texto em outro estilo: **UPPERCASE**, **lowercase**, **Title Case**, **Sentence case**, **Capitalized Case**, **aLtErNaTiNg**, **iNVERSE**, **camelCase**, **PascalCase**, **snake_case**, **kebab-case**, **CONSTANT_CASE** e **URL slug**.
3. Toque em **Copy** no cartão que você quiser.

![Ferramenta Case: cartões UPPERCASE, lowercase e Title Case, cada um com Use input, Share e Copy](shots/02-case.png)

## Limpar o texto

1. Toque em **Clean**.
2. Toque em uma ação:
   - **Clean all**: remove tabulações, espaços repetidos, espaços no fim das linhas, linhas vazias e linhas repetidas de uma só vez.
   - **Extra spaces**, **Trim lines**, **No empty lines**, **No duplicates** ou **Remove tabs**: faz apenas essa tarefa.
   - A ação de quebras de linha: remove as quebras de linha do texto.
3. Veja o resultado em **CLEANED RESULT**. O texto que você digitou na caixa continua como estava.

![Ferramenta Clean: os botões de limpeza e o cartão CLEANED RESULT](shots/03-clean.png)

## Ordenar ou inverter

1. Toque em **Lines** para trabalhar com linhas inteiras: **A to Z**, **Z to A**, **Reverse lines**, **Shortest first**, **No duplicates** ou **Reverse characters**. A ordenação ignora maiúsculas e espaços no início da linha.
2. Toque em **Reverse** para virar o texto do avesso: **Entire text**, **Each word**, **Word order**, **Line order** ou **Characters per line**.
3. O resultado aparece no cartão abaixo dos botões.

## Localizar e substituir

1. Toque em **Replace**.
2. Digite o texto a procurar em **Find** e o novo texto em **Replace with**.
3. Toque nas opções para ativar ou desativar: **Replace all** (desativada, troca só a primeira ocorrência), **Case sensitive** e **Whole word**.
4. Confira o número de substituições e o **REPLACEMENT PREVIEW**. Os dois se atualizam enquanto você digita.

![Ferramenta Replace: os campos Find e Replace with, os três botões de opção, a contagem de substituições e a prévia](shots/04-replace.png)

A busca procura exatamente o que você digita. Ela não usa padrões nem curingas.

## Codificar, decodificar e formatar

1. Toque em **Encode**, escolha **URL**, **Base64** ou **HTML Entities** e toque em **Encode** ou **Decode**.
2. Toque em **Format** e escolha **Format JSON** para indentar o JSON com dois espaços, **Minify JSON** para deixá-lo em uma só linha, ou **Strip Markdown** para transformar Markdown em texto simples.
3. Se o JSON tiver um erro, uma linha perto do topo da tela começa com "Invalid JSON" e diz o que está errado.

## Comparar dois textos

1. Coloque a primeira versão em **YOUR TEXT** e toque em **Diff**.
2. Digite ou cole a segunda versão em **COMPARE WITH**.
3. Leia **DIFF COMPARISON**. Linhas só da segunda versão ficam verdes, com **+**. Linhas só da primeira versão ficam vermelhas, com **-**. Linhas iguais não têm marca.
4. Toque em **Copy Diff** para copiar a comparação com as marcas + e -.

![Ferramenta Diff: a caixa COMPARE WITH e o cartão DIFF COMPARISON com uma linha verde adicionada e uma linha vermelha removida](shots/05-diff.png)

## Copiar, compartilhar ou continuar trabalhando

1. Toque em **Copy** em um cartão de resultado para levá-lo à área de transferência.
2. Toque em **Share** para enviá-lo a outro app.
3. Toque em **Use input** para mover o resultado para **YOUR TEXT** e usar outra ferramenta nele.

## Premium

Todas as ferramentas são grátis. Uma compra opcional, feita uma única vez, remove os anúncios. Você paga uma vez só; não é assinatura.

## Perguntas

**Funciona offline?**
Sim. As nove ferramentas funcionam no seu celular. Só os anúncios e a compra para removê-los usam conexão com a internet.

**Meu texto é salvo?**
Não. O app guarda seu texto apenas enquanto está aberto. Copie ou compartilhe o resultado que quiser guardar.

**Por que o resultado ficou vazio depois de trocar de ferramenta?**
Clean, Lines, Reverse, Encode e Format usam o mesmo cartão de resultado, que é limpo quando você troca de ferramenta. Toque na ação de novo. Faça o mesmo depois de editar o texto. Counter, Case, Replace e Diff se atualizam sozinhos.

**Ele segue o modo escuro?**
Sim. O app usa o tema claro ou escuro definido no seu celular.

**Onde ficam as licenças?**
Role até o final e toque em **Open-source licenses**. **Privacy policy** fica ao lado.

## Privacidade

Seu texto é processado no seu celular e nunca é enviado nem salvo. O app pode mostrar anúncios do Google AdMob; quando a lei exige, primeiro você é consultado sobre sua escolha e pode alterá-la em **Ad privacy choices** na tela principal. Leia a [política de privacidade](https://varian1.github.io/text-toolkit/privacy.html) completa.
