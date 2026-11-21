---
title: Bloquear Tela com Um Toque
name: TapLock
tagline: Bloqueie o celular com um toque. Digital e rosto continuam funcionando.
project: LOCKAPPONLY
package: io.github.varian1.screenlock
version: 1.1.0
updated: 2026-11-17
privacy: https://varian1.github.io/LockAppOnlyWeb/privacy.html
---

## O que ele faz

O TapLock coloca um botão grande **Lock** na tela. Toque nele e o celular bloqueia na hora, como se você apertasse o botão de ligar. É útil quando o botão de ligar é difícil de alcançar, está gasto ou quebrou.

- Com o bloqueio por Acessibilidade, você desbloqueia como sempre: com digital, rosto, PIN ou padrão.
- O bloqueio por Administrador do dispositivo é uma segunda opção, que funciona sem a Acessibilidade.
- Uma tela, um botão. Sem conta e sem login.
- Grátis, com anúncios.

## Primeiros passos

1. Abra o TapLock. Na primeira vez, a linha abaixo do botão **Lock** diz "One-time setup needed (about a minute)."
2. Toque em **Set up TapLock**. A tela **Lock setup** abre.
3. Escolha uma das duas formas de bloquear:
   - **Accessibility lock** (recomendado, Android 9 ou mais novo): bloqueia como o botão de ligar, e o desbloqueio por digital e rosto continua funcionando.
   - **Device Admin lock**: funciona sem a Acessibilidade. O Android pede seu PIN, padrão ou senha na próxima vez que você desbloquear.
4. Siga os passos da sua escolha abaixo.

Você pode abrir **Lock setup** de novo a qualquer momento pelo ícone de configurações, no canto superior direito da tela inicial.

## Ativar o bloqueio por Acessibilidade

1. Em **Lock setup**, no cartão **Accessibility lock**, toque em **Turn on Accessibility lock**.
2. Uma janela pergunta **Allow TapLock to use Accessibility?** Leia como o TapLock usa essa permissão.
3. Toque em **Agree** para continuar. Se você tocar em **Decline**, nada muda e o bloqueio por Acessibilidade continua desativado.
4. As configurações de Acessibilidade do Android abrem. Procure o TapLock, em geral em "Apps baixados".
5. Ative "Use TapLock", toque em **Allow** e volte ao TapLock.
6. O cartão passa a mostrar **On**, e **You're all set** aparece no topo. Toque em **Back to Lock**.

![A janela "Allow TapLock to use Accessibility?" com os botões Decline e Agree](shots/04-accessibility-consent.png)

**Por que o TapLock pede Acessibilidade.** O TapLock usa a API do Serviço de Acessibilidade apenas para bloquear a tela quando você toca no botão **Lock**, o mesmo que apertar o botão de ligar. Por isso o desbloqueio por digital e rosto continua funcionando. O TapLock não lê a sua tela, não vê o que você digita e não coleta, guarda nem compartilha dados pessoais por meio dessa permissão. Você escolhe **Agree** ou **Decline** antes de as configurações do Android abrirem, e pode desativá-la de novo a qualquer momento.

Se o cartão mostrar **Starting** por mais de alguns segundos, desligue e ligue o TapLock de novo nas configurações de Acessibilidade. Se o botão nas configurações do Android estiver esmaecido, toque em **Switch greyed out?** em **Lock setup** e siga a dica que aparece.

## Usar o bloqueio por Administrador do dispositivo

1. Em **Lock setup**, no cartão **Device Admin lock**, toque em **Enable Device Admin**.
2. O Android pede que você confirme. O TapLock usa essa permissão apenas para bloquear a tela quando você toca no botão **Lock**.
3. O cartão passa a mostrar **On**.

![Tela Lock setup: o cartão Accessibility lock mostra On, e o cartão Device Admin lock tem o botão Enable Device Admin](shots/02-setup.png)

Com essa forma de bloqueio, o Android pede seu PIN, padrão ou senha na próxima vez que você desbloquear, em vez de digital ou rosto. Se as duas formas estiverem ativas, o TapLock usa o bloqueio por Acessibilidade.

## Bloquear a tela

1. Abra o TapLock. A linha abaixo do botão começa com "Ready."
2. Toque em **Lock**. A tela bloqueia na hora.
3. Desbloqueie o celular como sempre faz.

![Tela inicial com o botão redondo Lock e a linha "Ready. Fingerprint and face unlock stay on."](shots/01-home.png)

## Usar o modo escuro

1. Ative o tema escuro nas configurações do Android do seu celular.
2. Abra o TapLock. Ele acompanha o celular e muda para o escuro sozinho. O app não tem uma configuração separada para isso.

![A tela inicial do TapLock no modo escuro](shots/03-dark-mode.png)

## Mudar o idioma

1. Na tela inicial, toque no ícone de configurações para abrir **Lock setup**.
2. Abra o seletor de idioma.
3. Escolha um dos 31 idiomas, ou mantenha o padrão do sistema para o TapLock seguir o idioma do celular.

![O seletor de idioma com a lista de idiomas](shots/06-language.png)

Árabe, urdu e hebraico aparecem da direita para a esquerda. No Android 13 ou mais novo, você também pode mudar o idioma do TapLock nas configurações de idioma do app no Android.

## Desativar um método de bloqueio ou desinstalar

1. Na tela inicial, toque no ícone de configurações para abrir **Lock setup**.
2. Para desativar o bloqueio por Acessibilidade, toque em **Manage in Accessibility settings** e desligue o TapLock lá.
3. Para desativar o bloqueio por Administrador do dispositivo, toque em **Turn off Device Admin**.
4. Desative o Administrador do dispositivo antes de desinstalar o TapLock. O Android não permite desinstalar um app enquanto ele é administrador ativo do dispositivo.

![Lock setup com o cartão "You're all set" e o botão para desativar o Device Admin](shots/05-device-admin-on.png)

## Dúvidas

**Por que o TapLock precisa da permissão de Acessibilidade?**
Apenas para bloquear a tela quando você toca em **Lock**, o mesmo que apertar o botão de ligar. Ele não lê a sua tela nem vê o que você digita. Se preferir não permitir, use o bloqueio por Administrador do dispositivo.

**Minha digital não funciona depois de bloquear com o TapLock. Por quê?**
Você está usando o Device Admin lock, que faz o Android pedir seu PIN, padrão ou senha uma vez. Ative o Accessibility lock para manter o desbloqueio por digital e rosto funcionando.

**Não consigo desinstalar o TapLock. O que fazer?**
Abra **Lock setup**, toque em **Turn off Device Admin** e depois desinstale.

**Qual versão do Android eu preciso?**
O Accessibility lock exige Android 9 ou mais novo. Em versões mais antigas, use o Device Admin lock.

**Posso usar o TapLock no meu idioma?**
Sim. O TapLock está disponível em 31 idiomas. Escolha o seu em **Lock setup** ou mantenha o padrão do sistema.

## Privacidade

O TapLock usa as permissões de Acessibilidade e de Administrador do dispositivo apenas para bloquear a tela e não coleta dados pessoais por meio delas. O app mostra anúncios do Google AdMob; onde for exigido, você pode mudar suas escolhas de anúncios em **Privacy settings** na tela **Lock setup**. Leia a [política de privacidade](https://varian1.github.io/LockAppOnlyWeb/privacy.html) completa.
