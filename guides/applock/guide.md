---
title: App Lock: Intruder Selfie
name: AppLock
tagline: Lock any app behind your PIN, pattern, password or fingerprint. Works offline.
project: AppLock Without Dashboad
package: io.github.varian1.applock
version: 1.3.3
updated: 2026-11-25
privacy: https://varian1.github.io/privacy.html
---

## What it does

AppLock puts a lock screen in front of the apps you choose. When someone opens a locked app, they must enter your PIN, pattern or password, or use your fingerprint, before they can see it. Inside the app the name is written "App Lock".

- No account. Your PIN, your list of locked apps, the security log and intruder photos stay on your phone and are never uploaded.
- It can take a photo of someone who keeps entering the wrong code.
- A recovery code gets you back in if you forget your PIN.
- Free with ads. Locking apps is always free. A one-time Premium purchase removes ads and adds extras.

## Get started

1. Open AppLock and tap **Get started**.
2. Under **How do you want to unlock?**, choose **PIN**, **Pattern** or **Password**.
3. Enter it, then enter it again to confirm. A PIN has 6 digits. A pattern connects at least 4 dots. A password has at least 4 characters. For a pattern or password, tap **Continue** after each entry.
4. On **Save your recovery code**, write down the 8-digit code and keep it somewhere safe. You only see it once, and it is the only way back in if you forget your PIN, pattern or password.
5. Tick **I’ve saved this code somewhere safe** and tap **Continue**.

You are now on the home screen. It shows **Protection off** until you allow the permissions and lock your first app.

The home screen also shows your last three events from the security log. If your phone is rooted, or AppLock was not installed from Google Play, the home screen shows a warning. Locking keeps working.

## Allow the permissions

AppLock can only lock an app if Android lets it notice that the app was opened and lets it draw the lock screen on top. That takes two permissions: **Accessibility** and **Display over other apps**. The other permissions are optional.

1. On the home screen, tap **Finish setup** or **Permissions**.
2. Tap **Accessibility**. AppLock first shows a page called **What Accessibility access does**. Read it.
3. Tap **I understand — open settings**. If you do not agree, tap **Not now**: nothing is changed and no settings are opened.
4. In the Android settings screen that opens, turn the service on for AppLock, then go back to AppLock.
5. Tap **Display over other apps** and allow it in the Android settings screen.
6. Tap any other row you want to allow. A row shows **Granted** when it is done.
7. Tap **?** under a row for help with that permission, including battery-saver steps for your phone brand.

![The page "What Accessibility access does", shown before Android settings open](shots/05-accessibility-disclosure.png)

**Why AppLock asks for Accessibility.** AppLock uses Android's Accessibility service for one purpose only: noticing which app just came to the front, so it can show the lock screen over the apps you chose to protect.

- What it does: it watches for the name of the app that just opened, and nothing else. When a locked app is unlocked or a wrong code is entered, that app's name is saved in the **Security log** on your phone so you can review it.
- What it never does: it never reads screen content, keystrokes, passwords, messages or any other on-screen data, in AppLock or in any other app. Nothing is sent off your device.
- You can turn it off at any time in Android Settings. AppLock then simply cannot show the lock screen any more.

**What the other permissions are for.**

- **Display over other apps**: lets the lock screen appear on top of a locked app.
- **Usage access**: helps confirm that protection is working reliably.
- **Notifications**: offers to lock apps you install, and warns you when locking is off.
- **Camera** (optional): takes a photo of whoever fails to unlock.
- **Notification access**: hides notification content for locked apps.
- **Ignore battery optimization**: keeps protection running in the background.

Every permission is used on your phone only.

![Permissions screen: each permission with its reason and a green Granted label](shots/03-permissions.png)

## Choose the apps to lock

1. On the home screen, tap **Lock apps**.
2. Find the app. Type its name in **Search apps**, or switch between the **User**, **System** and **Recent** tabs. **Recent** shows the newest installs first.
3. Turn on the switch next to each app you want to lock.
4. Go back. The home screen shows **Protected** and the number of locked apps.

![The Lock apps list with a search field, tabs and a switch for each app](shots/06-lock-apps.png)

To unlock an app for good, open **Lock apps** again and turn its switch off.

To work faster in **Lock apps**:

- At the top of the **User** tab, **Suggested to lock** lists apps on your phone that people often protect. Tap **Lock all** to lock them in one go.
- Tap the star on a row to pin that app to the top as a favorite.
- To lock several apps at once, touch and hold a row or tap **Select**. Pick the apps, or tap **Select all**, then tap the **Lock** button.

![Home screen showing Protected, 6 apps locked, with Lock apps, Permissions, Security log, Intruder photos and Settings](shots/01-home.png)

## Switch between profiles

A profile is a saved set of locked apps, such as Work or Home.

1. Lock the apps you want in the set.
2. Open profiles from the home screen and add a new profile. It saves the apps that are locked right now.
3. To switch, tap another profile on the home screen. AppLock locks that profile's apps straight away.
4. While a profile is active, changes you make in **Lock apps** are saved into it.
5. To change a profile's apps without switching to it, tap **Apps** on that profile, choose the apps and tap **Save**.

The free version includes 2 profiles. Premium removes the limit.

![Profiles screen with a Work and a Guest profile](shots/08-profiles.png)

## Open a locked app

1. Open an app you have locked. The lock screen covers it straight away.
2. Enter your PIN, pattern or password. If you turned on **Unlock with biometrics**, you can use your fingerprint instead.
3. After a wrong entry you can try again. After too many wrong entries you have to wait a moment.

AppLock itself is locked in the same way, so nobody else can change your settings.

![Lock screen with "Enter your PIN" and the number pad](shots/02-lock-screen.png)

## Change how locking works

1. On the home screen, tap **Settings**.
2. Under **Appearance**, choose **System**, **Light** or **Dark**.
3. Under **Appearance**, tap **Language** to choose one of 38 languages. **System default** follows your phone.
4. On Android 12 or newer, turn on **Dynamic color** to use colors from your wallpaper.
5. Under **Re-lock**, choose when an app you unlocked is locked again: **Immediately** when you leave it, **On screen off**, or after 1, 5, 15 or 30 minutes.
6. Under **App Lock itself locks again**, choose when AppLock asks for your code again after you leave it.
7. Under **Security**, turn on **Unlock with biometrics**. You confirm your PIN, pattern or password first. This needs a fingerprint or face already set up on your phone.
8. If you use a PIN, choose a 4-digit or 6-digit PIN under **Security**. You enter your current PIN, then the new one. Your recovery code stays the same.
9. Under **Protection**, turn on **Scramble the PIN pad** to mix up the number keys, so nobody can guess your PIN from where you tap.
10. Turn on **Hide notification content for locked apps** to keep messages from locked apps private. They show as "New notification". This needs **Notification access** in **Permissions**.
11. Tap **Choose apps** to pick which locked apps have their notifications hidden. All locked apps are hidden at first. Switch an app off to keep its full notifications.
12. Turn on **Extra step before uninstall** if you want one more step before AppLock can be removed. AppLock explains it first, then Android asks you. It adds a step; it does not stop anyone removing the app.
13. Under **Disguise**, turn on **Hide from Recents** to keep AppLock out of the recent apps list.

![Settings: the Premium card, Appearance, Re-lock and Security](shots/04-settings.png)

## See who tried to get in

1. Open **Settings** and turn on **Intruder photo after failed attempts**.
2. Choose after how many wrong entries in a row the photo is taken: 2 to 5.
3. Open **Permissions** and allow **Camera**. If **Camera** is not allowed, **Settings** shows a warning with a link to fix it.
4. From now on, after that many wrong entries in a row on the lock screen, the front camera takes a photo.
5. On the home screen, tap **Intruder photos** to see the photos, each with the app that was opened.
6. Tap **Security log** to see unlocks, failed attempts and settings changes.
7. To save the log as a file, export it from the **Security log** and pick where to send it. AppLock first warns you that the file is not encrypted.
8. In **Settings**, choose how long the log is kept: 30 days, 90 days, 1 year or forever. Intruder photos older than that are deleted too.

![Intruder photos screen with photos taken after failed unlock attempts](shots/07-intruder-photos.png)

## Get back in if you forgot your PIN

1. Open AppLock. On the unlock screen, tap **Can’t get in?**
2. Enter the 8-digit recovery code you saved and tap **Continue**.
3. Set a new PIN, pattern or password. You then get a new recovery code; the old one stops working.

To get a new recovery code while you still know your PIN, open **Settings** and tap **Replace recovery code**.

## Premium

Premium is one payment, not a subscription. Open **Settings** and tap **Unlock Premium**, or tap any Premium badge. One screen shows what Premium adds, its price, and how to buy or restore it. Locking apps stays free without it. Premium gives you:

- No ads. AppLock then only goes online when you start a purchase or restore.
- **Fake crash screen (long-press to unlock)**: a locked app looks as if it has crashed, with the app's name, instead of showing the lock screen. Touch and hold **OK** for 3 seconds to reach the real lock screen.
- Disguise icons: change AppLock's icon and name on your home screen to **Calculator**, **Notes** or **Weather**. With **Calculator** you can turn on **Open a real calculator instead** and set a **Secret code**: type the code and press = to open AppLock. Your PIN always works too.
- The full history of intruder photos. The free version shows the newest 5.
- More than 2 profiles.
- **Export backup**: an encrypted copy of your settings and lock list, protected by a password you choose. **Restore backup** is free.

If you bought Premium before, open the Premium screen and restore your purchase.

## Questions

**Why does AppLock need the Accessibility permission?**
Only to notice which app was just opened, so it can show the lock screen over the apps you locked. It never reads what is on your screen or what you type. See "Allow the permissions" above.

**The home screen says "Protection off". What is wrong?**
Either **Accessibility** or **Display over other apps** is not allowed, or no app is locked yet. Tap **Finish setup** to open the permissions list, then check **Lock apps**.

**Can I hide AppLock completely?**
No. Android always keeps an icon for an installed app. With Premium you can swap the icon and name for a disguise instead.

**I forgot my PIN and lost the recovery code. Can you reset it?**
No. AppLock works offline with no account, so there is no email reset. The recovery code is the only way back in. Keep it somewhere safe.

**Does a backup contain my PIN or the intruder photos?**
No. After you restore a backup, the app asks you to set a new PIN, pattern or password first.

## Privacy

Your PIN, your locked apps, the security log and intruder photos stay on your device and are never uploaded. The free version shows ads from Google AdMob; with Premium, AppLock only goes online for a purchase or restore you start. Read the full [privacy policy](https://varian1.github.io/privacy.html).
