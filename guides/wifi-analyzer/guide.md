---
title: Wi-Fi Tools: Analyzer, Speed
name: Wi-Fi Tools
tagline: See nearby Wi-Fi channels, test your speed and find devices on your network
project: wifi-analyzer
package: io.github.varian1.wifitools
version: 1.0
updated: 2026-11-25
privacy: https://varian1.github.io/wifitools/privacy.html
---

## What it does

Wi-Fi Tools shows you what is happening on your Wi-Fi. It scans the networks around you, shows which channel is least crowded, tests your speed and finds the devices on your network.

- Channel graph and channel rating for 2.4 GHz, 5 GHz and 6 GHz (on phones that support 6 GHz)
- Internet speed test and Wi-Fi (LAN) speed test
- Heat map of your signal on your own floor plan
- Network tools: LAN scanner, ping, traceroute, DNS, WHOIS, SSL check and port scanner

## Get started

1. Open Wi-Fi Tools.
2. Allow the location permission when Android asks. Android needs it to scan for Wi-Fi networks.
3. Make sure Wi-Fi and location are turned on.
4. Open the analyzer to see the networks around you.

## Find the best channel

1. Open the analyzer and choose the graph view.
2. Look at the networks on 2.4 GHz, 5 GHz or 6 GHz and see which channels are crowded.
3. Switch to the rating view.
4. Read the best channel for a new router or for your own network.

The app shows a note when a channel is not allowed in your country.

![Channel graph of nearby networks](shots/01-graph.png)

## Check a network

1. Open the analyzer and choose the list view.
2. Sort the list by signal, name, channel or interference.
3. Tap a network to see its details: channel width, security, Wi-Fi standard, router maker and the networks on the same channel.
4. Open the history view to see the signal over time, with a live signal for the network you are connected to.

## Test your speed

1. Open the speed tests.
2. Choose the internet speed test to measure ping, download and upload.
3. Read the notice before your first test, then start the test.
4. To test the speed between your phone and your router, choose the Wi-Fi (LAN) speed test and open it from a computer on the same Wi-Fi.

![Internet speed test result](shots/02-speed-test.png)

## Make a heat map

1. Open the heat map.
2. Import a photo of your floor plan, or take one with the camera.
3. Go to a spot in your home and tap where you stand on the plan to record the signal.
4. Repeat in other spots and watch the coverage fill in.
5. Save the result, or share it as an image.

![Heat map on a floor plan](shots/03-heat-map.png)

## Use the network tools

1. Open the tools.
2. Run the LAN scanner to find the devices on your network and see their names.
3. Open network info to see your IP, gateway and DNS. Ask for your public IP if you need it.
4. Use ping to check jitter and packet loss, or traceroute to see the path to a host.
5. Use DNS lookup, WHOIS, the SSL certificate check or the mail security check (SPF, DKIM, DMARC) for a domain.
6. Use the port scanner to check ports on a host and see their service names.

## Premium

The free version shows ads. A one-time purchase in Settings removes all ads. There is no subscription.

## Questions

**Why does the graph not refresh all the time?**
Android allows only a few Wi-Fi scans every two minutes, so the graph refreshes at that pace. The app tells you when this happens and how to turn the limit off in developer options.

**Why does the app need my location?**
Android needs the location permission to scan for Wi-Fi networks. The app does not read your position, and the scan results stay on your phone.

**Why can't I see 6 GHz networks?**
The 6 GHz band only shows on phones that support it.

**Do I need an account?**
No. There is no login, and all features work without an account.

**Can I change the theme or language?**
Yes. You can pick a dark or light theme in Settings. The app comes in 14 languages, and on Android 13 and newer you can choose its language on its own.

## Privacy

Wi-Fi scan results, LAN scan results and heat maps stay on your phone. Internet speed test results, including your IP address, are published by Measurement Lab, and the free version shows ads from Google AdMob. Read the [privacy policy](https://varian1.github.io/wifitools/privacy.html).
