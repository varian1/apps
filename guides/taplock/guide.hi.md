---
title: स्क्रीन लॉक करें: वन क्लिक लॉक
name: TapLock
tagline: एक टैप में फ़ोन लॉक करें। फ़िंगरप्रिंट और फ़ेस अनलॉक पहले की तरह चलते हैं।
project: LOCKAPPONLY
package: io.github.varian1.screenlock
version: 1.1.0
updated: 2026-11-17
privacy: https://varian1.github.io/LockAppOnlyWeb/privacy.html
---

## What it does

TapLock आपकी स्क्रीन पर एक बड़ा **Lock** बटन रखता है। उसे टैप करते ही फ़ोन तुरंत लॉक हो जाता है, ठीक पावर बटन दबाने की तरह। जब पावर बटन तक हाथ पहुँचाना मुश्किल हो, वह घिस गया हो या ख़राब हो, तब यह काम आता है।

- Accessibility lock के साथ आप फ़िंगरप्रिंट, फ़ेस, PIN या पैटर्न से पहले की तरह अनलॉक करते हैं।
- Device Admin lock लॉक करने का दूसरा तरीक़ा है, जो Accessibility के बिना भी चलता है।
- एक स्क्रीन, एक बटन। न अकाउंट, न साइन-इन।
- विज्ञापनों के साथ मुफ़्त।

## Get started

1. TapLock खोलें। पहली बार **Lock** बटन के नीचे लिखा होता है "One-time setup needed (about a minute)."
2. **Set up TapLock** पर टैप करें। **Lock setup** स्क्रीन खुलेगी।
3. लॉक करने के दो तरीक़ों में से एक चुनें:
   - **Accessibility lock** (सुझाया गया, Android 9 या नया): पावर बटन की तरह लॉक करता है, और फ़िंगरप्रिंट व फ़ेस अनलॉक चलते रहते हैं।
   - **Device Admin lock**: Accessibility के बिना चलता है। अगली बार अनलॉक करते समय Android आपसे PIN, पैटर्न या पासवर्ड माँगता है।
4. अपने चुने तरीक़े के लिए नीचे दिए चरण अपनाएँ।

होम स्क्रीन पर ऊपर दाईं ओर सेटिंग आइकन से आप **Lock setup** को कभी भी दोबारा खोल सकते हैं।

## Accessibility lock चालू करें

1. **Lock setup** में **Accessibility lock** कार्ड पर **Turn on Accessibility lock** टैप करें।
2. एक डायलॉग पूछता है **Allow TapLock to use Accessibility?** पढ़ें कि TapLock इसका उपयोग कैसे करता है।
3. आगे बढ़ने के लिए **Agree** टैप करें। **Decline** टैप करने पर कुछ नहीं बदलता और Accessibility lock बंद रहता है।
4. Android की Accessibility सेटिंग खुलती हैं। TapLock ढूँढें, यह अक्सर "Downloaded apps" में मिलता है।
5. "Use TapLock" चालू करें, **Allow** टैप करें, फिर TapLock पर लौट आएँ।
6. कार्ड पर अब **On** दिखता है और ऊपर **You're all set** आ जाता है। **Back to Lock** टैप करें।

![डायलॉग "Allow TapLock to use Accessibility?" जिसमें Decline और Agree बटन हैं](shots/04-accessibility-consent.png)

**TapLock Accessibility क्यों माँगता है।** TapLock, Accessibility Service API का उपयोग केवल तभी करता है जब आप **Lock** बटन टैप करते हैं, ताकि स्क्रीन लॉक हो, ठीक पावर बटन दबाने की तरह। इसीलिए फ़िंगरप्रिंट और फ़ेस अनलॉक चलते रहते हैं। TapLock न आपकी स्क्रीन पढ़ता है, न यह देखता है कि आप क्या टाइप करते हैं, और इस अनुमति से कोई निजी डेटा इकट्ठा, सेव या साझा नहीं करता। Android की सेटिंग खुलने से पहले आप **Agree** या **Decline** चुनते हैं, और इसे कभी भी फिर से बंद कर सकते हैं।

अगर कार्ड पर कुछ सेकंड से ज़्यादा देर तक **Starting** दिखे, तो Accessibility सेटिंग में TapLock को बंद करके फिर चालू करें। अगर Android की सेटिंग में स्विच धूसर (ग्रे) है, तो **Lock setup** में **Switch greyed out?** टैप करें और वहाँ दिया सुझाव अपनाएँ।

## इसके बजाय Device Admin lock इस्तेमाल करें

1. **Lock setup** में **Device Admin lock** कार्ड पर **Enable Device Admin** टैप करें।
2. Android आपसे पुष्टि माँगता है। TapLock इस अनुमति का उपयोग केवल तभी करता है जब आप **Lock** बटन टैप करके स्क्रीन लॉक करते हैं।
3. कार्ड पर अब **On** दिखता है।

![Lock setup स्क्रीन: Accessibility lock कार्ड पर On दिख रहा है, और Device Admin lock कार्ड में Enable Device Admin बटन है](shots/02-setup.png)

इस तरीक़े से लॉक करने पर, अगली बार अनलॉक करते समय Android फ़िंगरप्रिंट या फ़ेस की जगह आपसे PIN, पैटर्न या पासवर्ड माँगता है। अगर दोनों तरीक़े चालू हैं, तो TapLock Accessibility lock का उपयोग करता है।

## अपनी स्क्रीन लॉक करें

1. TapLock खोलें। बटन के नीचे की पंक्ति "Ready." से शुरू होती है।
2. **Lock** टैप करें। स्क्रीन तुरंत लॉक हो जाती है।
3. अपना फ़ोन हमेशा की तरह अनलॉक करें।

![होम स्क्रीन, जिसमें गोल Lock बटन और पंक्ति "Ready. Fingerprint and face unlock stay on." दिख रही है](shots/01-home.png)

## डार्क मोड इस्तेमाल करें

1. अपने फ़ोन की Android सेटिंग में डार्क थीम चालू करें।
2. TapLock खोलें। यह आपके फ़ोन के अनुसार अपने-आप डार्क हो जाता है। ऐप में इसकी अलग सेटिंग नहीं है।

![डार्क मोड में TapLock की होम स्क्रीन](shots/03-dark-mode.png)

## भाषा बदलें

1. होम स्क्रीन पर सेटिंग आइकन टैप करके **Lock setup** खोलें।
2. भाषा चुनने वाली सूची खोलें।
3. 31 भाषाओं में से कोई एक चुनें, या सिस्टम डिफ़ॉल्ट रखें ताकि TapLock आपके फ़ोन की भाषा के अनुसार चले।

![भाषाओं की सूची के साथ भाषा चुनने की स्क्रीन](shots/06-language.png)

अरबी, उर्दू और हिब्रू दाएँ से बाएँ दिखाई जाती हैं। Android 13 या नए वर्शन पर आप Android की ऐप भाषा सेटिंग से भी TapLock की भाषा बदल सकते हैं।

## लॉक का तरीक़ा बंद करें या ऐप अनइंस्टॉल करें

1. होम स्क्रीन पर सेटिंग आइकन टैप करके **Lock setup** खोलें।
2. Accessibility lock बंद करने के लिए **Manage in Accessibility settings** टैप करें और वहाँ TapLock को बंद करें।
3. Device Admin lock बंद करने के लिए **Turn off Device Admin** टैप करें।
4. TapLock अनइंस्टॉल करने से पहले Device Admin बंद करें। जब तक कोई ऐप सक्रिय डिवाइस एडमिन है, Android उसे अनइंस्टॉल नहीं करने देता।

![Lock setup में "You're all set" कार्ड और Device Admin बंद करने का बटन](shots/05-device-admin-on.png)

## Questions

**TapLock को Accessibility की अनुमति क्यों चाहिए?**
केवल तब स्क्रीन लॉक करने के लिए जब आप **Lock** टैप करते हैं, ठीक पावर बटन दबाने की तरह। यह न आपकी स्क्रीन पढ़ता है, न यह देखता है कि आप क्या टाइप करते हैं। अगर आप यह अनुमति नहीं देना चाहते, तो Device Admin lock इस्तेमाल करें।

**TapLock से लॉक करने के बाद मेरा फ़िंगरप्रिंट काम नहीं करता। क्यों?**
आप Device Admin lock इस्तेमाल कर रहे हैं, जिसमें Android एक बार PIN, पैटर्न या पासवर्ड माँगता है। फ़िंगरप्रिंट और फ़ेस अनलॉक चालू रखने के लिए Accessibility lock चालू करें।

**मैं TapLock अनइंस्टॉल नहीं कर पा रहा/रही हूँ। क्या करूँ?**
**Lock setup** खोलें, **Turn off Device Admin** टैप करें, फिर अनइंस्टॉल करें।

**मुझे कौन-सा Android वर्शन चाहिए?**
Accessibility lock के लिए Android 9 या नया चाहिए। पुराने वर्शन पर Device Admin lock इस्तेमाल करें।

**क्या मैं TapLock अपनी भाषा में इस्तेमाल कर सकता/सकती हूँ?**
हाँ। TapLock 31 भाषाओं में उपलब्ध है। **Lock setup** में अपनी भाषा चुनें, या सिस्टम डिफ़ॉल्ट रखें।

## Privacy

TapLock, Accessibility और Device Admin अनुमतियों का उपयोग केवल आपकी स्क्रीन लॉक करने के लिए करता है, और इनसे कोई निजी डेटा इकट्ठा नहीं करता। ऐप में Google AdMob के विज्ञापन दिखते हैं; जहाँ ज़रूरी हो, वहाँ आप **Lock setup** में **Privacy settings** से अपनी विज्ञापन पसंद बदल सकते हैं। पूरी [निजता नीति](https://varian1.github.io/LockAppOnlyWeb/privacy.html) पढ़ें।
