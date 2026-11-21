---
title: Bloqueador de Apps com PIN
name: AppLock
tagline: Proteja qualquer app com PIN, padrão, senha ou digital. Funciona offline.
project: AppLock Without Dashboad
package: io.github.varian1.applock
version: 1.0
updated: 2026-11-10
privacy: https://varian1.github.io/privacy.html
---

## O que o app faz

O AppLock coloca uma tela de bloqueio na frente dos apps que você escolher. Quando alguém abre um app bloqueado, precisa digitar seu PIN, padrão ou senha, ou usar sua digital, antes de ver qualquer coisa. Dentro do app, o nome aparece escrito "App Lock".

- Sem conta. Seu PIN, a lista de apps bloqueados, o registro de segurança e as fotos de intrusos ficam no seu celular e nunca são enviados.
- Ele pode tirar uma foto de quem insiste em digitar o código errado.
- Um código de recuperação permite voltar a entrar se você esquecer o PIN.
- Grátis, com anúncios. Bloquear apps é sempre grátis. Uma compra única do Premium remove os anúncios e adiciona extras.

## Primeiros passos

1. Abra o AppLock e toque em **Get started**.
2. Em **How do you want to unlock?**, escolha **PIN**, **Pattern** ou **Password**.
3. Digite e depois digite de novo para confirmar. O PIN tem 6 dígitos. O padrão liga pelo menos 4 pontos. A senha tem pelo menos 4 caracteres. Para padrão ou senha, toque em **Continue** depois de cada entrada.
4. Em **Save your recovery code**, anote o código de 8 dígitos e guarde em um lugar seguro. Você o vê só uma vez, e ele é o único caminho de volta se esquecer o PIN, o padrão ou a senha.
5. Marque **I’ve saved this code somewhere safe** e toque em **Continue**.

Agora você está na tela inicial. Ela mostra **Protection off** até você conceder as permissões e bloquear seu primeiro app.

## Permitir as permissões

O AppLock só consegue bloquear um app se o Android deixar que ele perceba que o app foi aberto e desenhe a tela de bloqueio por cima. Isso exige duas permissões: **Accessibility** e **Display over other apps**. As outras permissões são opcionais.

1. Na tela inicial, toque em **Finish setup** ou **Permissions**.
2. Toque em **Accessibility**. Primeiro, o AppLock mostra uma página chamada **What Accessibility access does**. Leia com atenção.
3. Toque em **I understand — open settings**. Se não concordar, toque em **Not now**: nada é alterado e nenhuma configuração é aberta.
4. Na tela de configurações do Android que abrir, ative o serviço do AppLock e depois volte ao AppLock.
5. Toque em **Display over other apps** e permita na tela de configurações do Android.
6. Toque em qualquer outra linha que queira permitir. A linha mostra **Granted** quando estiver concluída.

![A página "What Accessibility access does", exibida antes de as configurações do Android abrirem](shots/05-accessibility-disclosure.png)

**Por que o AppLock pede Acessibilidade.** O AppLock usa o serviço de Acessibilidade do Android para um único fim: perceber qual app acabou de ir para a frente, para mostrar a tela de bloqueio sobre os apps que você escolheu proteger.

- O que ele faz: observa o nome do app que acabou de abrir, e nada mais. Quando um app bloqueado é desbloqueado ou um código errado é digitado, o nome desse app é salvo no **Security log** do seu celular para você consultar.
- O que ele nunca faz: nunca lê o conteúdo da tela, o que você digita, senhas, mensagens ou qualquer outro dado exibido, nem no AppLock nem em outros apps. Nada é enviado para fora do seu aparelho.
- Você pode desativar a qualquer momento nas Configurações do Android. Nesse caso, o AppLock simplesmente deixa de conseguir mostrar a tela de bloqueio.

**Para que servem as outras permissões.**

- **Display over other apps**: permite que a tela de bloqueio apareça por cima de um app bloqueado.
- **Usage access**: ajuda a confirmar que a proteção está funcionando bem.
- **Notifications**: avisa você sobre pedidos de bloqueio e tentativas de invasão.
- **Camera** (opcional): tira uma foto de quem falha ao desbloquear.
- **Notification access**: oculta o conteúdo das notificações dos apps bloqueados.
- **Ignore battery optimization**: mantém a proteção ativa em segundo plano.

Todas as permissões são usadas somente no seu celular.

![Tela de permissões: cada permissão com o motivo e uma etiqueta verde Granted](shots/03-permissions.png)

## Escolher os apps para bloquear

1. Na tela inicial, toque em **Lock apps**.
2. Encontre o app. Digite o nome em **Search apps** ou alterne entre as abas **User**, **System** e **Recent**. **Recent** mostra primeiro as instalações mais novas.
3. Ative o botão ao lado de cada app que quiser bloquear.
4. Volte. A tela inicial mostra **Protected** e o número de apps bloqueados.

![A lista Lock apps com campo de busca, abas e um botão para cada app](shots/06-lock-apps.png)

Para desbloquear um app de vez, abra **Lock apps** de novo e desative o botão dele.

![Tela inicial mostrando Protected, 6 apps locked, com Lock apps, Permissions, Security log, Intruder photos e Settings](shots/01-home.png)

## Abrir um app bloqueado

1. Abra um app que você bloqueou. A tela de bloqueio o cobre na hora.
2. Digite seu PIN, padrão ou senha. Se você ativou **Unlock with biometrics**, pode usar sua digital.
3. Depois de uma entrada errada, você pode tentar de novo. Depois de muitas entradas erradas, é preciso esperar um pouco.

O próprio AppLock é bloqueado do mesmo jeito, então ninguém consegue mudar suas configurações.

![Tela de bloqueio com "Enter your PIN" e o teclado numérico](shots/02-lock-screen.png)

## Mudar o funcionamento do bloqueio

1. Na tela inicial, toque em **Settings**.
2. Em **Appearance**, escolha **System**, **Light** ou **Dark**.
3. Em **Re-lock**, escolha quando um app desbloqueado volta a ser bloqueado: **Immediately** ao sair dele, **On screen off** ou **After 5 min**.
4. Em **Security**, ative **Unlock with biometrics**. Primeiro você confirma seu PIN, padrão ou senha. É preciso já ter uma digital ou um rosto cadastrado no celular.
5. Em **Protection**, ative **Scramble the PIN pad** para embaralhar as teclas numéricas, assim ninguém adivinha seu PIN pelo lugar onde você toca.
6. Ative **Hide notification content for locked apps** para manter privadas as mensagens dos apps bloqueados. Isso exige **Notification access** em **Permissions**.
7. Em **Disguise**, ative **Hide from Recents** para tirar o AppLock da lista de apps recentes.

![Settings: o cartão Premium, Appearance, Re-lock e Security](shots/04-settings.png)

## Ver quem tentou entrar

1. Abra **Settings** e ative **Intruder photo after failed attempts**.
2. Abra **Permissions** e permita **Camera**.
3. A partir daí, depois de três entradas erradas seguidas na tela de bloqueio, a câmera frontal tira uma foto.
4. Na tela inicial, toque em **Intruder photos** para ver as fotos, cada uma com o app que foi aberto.
5. Toque em **Security log** para ver desbloqueios, tentativas fracassadas e mudanças de configuração.

![Tela Intruder photos com fotos tiradas após tentativas de desbloqueio fracassadas](shots/07-intruder-photos.png)

## Voltar a entrar se esqueceu o PIN

1. Abra o AppLock. Na tela de desbloqueio, toque em **Can’t get in?**
2. Digite o código de recuperação de 8 dígitos que você salvou e toque em **Continue**.
3. Defina um novo PIN, padrão ou senha. Você recebe então um novo código de recuperação; o antigo deixa de funcionar.

Para obter um novo código de recuperação enquanto ainda sabe seu PIN, abra **Settings** e toque em **Replace recovery code**.

## Premium

O Premium é um pagamento único, não uma assinatura. Abra **Settings** e toque em **Unlock Premium**. Bloquear apps continua grátis sem ele. O Premium oferece:

- Sem anúncios.
- **Fake crash screen (long-press to unlock)**: um app bloqueado parece ter travado, em vez de mostrar a tela de bloqueio.
- Ícones de disfarce: troque o ícone e o nome do AppLock na tela inicial do celular por **Calculator**, **Notes** ou **Weather**. Com **Calculator**, você pode ativar **Open a real calculator instead** e definir um **Secret code**: digite o código e pressione = para abrir o AppLock. Seu PIN também sempre funciona.
- O histórico completo de fotos de intrusos. A versão grátis mostra as 5 mais recentes.
- **Export backup**: uma cópia criptografada das suas configurações e da lista de bloqueio, protegida por uma senha que você escolhe. **Restore backup** é grátis.

Se você já comprou o Premium, toque em **Restore purchases** em **Settings**.

## Perguntas

**Por que o AppLock precisa da permissão de Acessibilidade?**
Apenas para perceber qual app acabou de ser aberto, para mostrar a tela de bloqueio sobre os apps que você bloqueou. Ele nunca lê o que está na sua tela nem o que você digita. Veja "Permitir as permissões" acima.

**A tela inicial diz "Protection off". O que há de errado?**
Ou **Accessibility** ou **Display over other apps** não está permitido, ou ainda não há nenhum app bloqueado. Toque em **Finish setup** para abrir a lista de permissões e depois confira **Lock apps**.

**Posso esconder o AppLock por completo?**
Não. O Android sempre mantém um ícone para um app instalado. Com o Premium, você pode trocar o ícone e o nome por um disfarce.

**Esqueci o PIN e perdi o código de recuperação. Vocês podem redefinir?**
Não. O AppLock funciona offline e sem conta, então não existe redefinição por e-mail. O código de recuperação é o único caminho de volta. Guarde-o em um lugar seguro.

**O backup contém meu PIN ou as fotos de intrusos?**
Não. Depois de restaurar um backup, o app pede que você defina primeiro um novo PIN, padrão ou senha.

## Privacidade

Seu PIN, seus apps bloqueados, o registro de segurança e as fotos de intrusos ficam no seu aparelho e nunca são enviados. A versão grátis mostra anúncios do Google AdMob. Leia a [política de privacidade](https://varian1.github.io/privacy.html) completa.
