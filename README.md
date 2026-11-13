# iXMercury Network Home

**In development / pre-release. The rebuilt iOS candidate is not yet compiled, device-tested or publicly available. No public download or release date is available.**

A home-network inventory and observation app for iPhone and iPad. The source candidate adds household device records organized by family member and room, user-assigned recognition labels, saved Bonjour observation comparisons, foreground device-interface traffic charts and optional HTTPS connectivity checks.

Inventory records do not prove online presence. Bonjour observations are incomplete and do not count all router clients. Traffic counters describe this device, not the entire router or individual family members. No person tracking, packet inspection or VPN is provided.

## Pre-release privacy additions

The new source candidate stores inventory and up to 30 saved Bonjour observations in a protected local file. Inventory may include user-entered names, rooms and device notes. iOS backups may include these files according to device settings. Manual inventory sharing includes those user-entered details; check the recipient before exporting. Inventory entries can be edited or deleted locally. No inventory is uploaded to a Mercury backend. The earlier build 18 policy below applies only to the earlier network-monitor implementation, which does not contain the new household workflow.

---

# Mercury Network — Support and Privacy

Updated 12 November 2026. This policy applies to Mercury Network iOS 1.0, build 18 and later. Build 18 replaces the former VPN implementation with a local network monitor. It has no VPN tunnel, VPN servers, account, advertising SDK or active subscription. Policies for earlier VPN builds remain available in this repository's version history.

## Support

Developer: Iulian Valentin Nedelcu (NEDELCU IULIAN VALENTIN PFA). Contact: valentin.nedelcu@icloud.com.

For help, provide the app build, iOS version, connection type and the exact error. Do not send router passwords, Wi-Fi passwords, private keys or sensitive network details. Diagnostic export is optional and goes only to the recipient you choose.

Mercury Network shows the connection path reported by iOS and foreground byte-counter changes on this device's physical network interfaces. Counters may include local traffic and other applications. They are not billable Internet usage, monthly history or router-wide usage. Observation pauses when the app is not active. Connected indicates an available iOS network path; it does not guarantee access past a captive portal.

Bonjour discovery starts only after an explicit action and requires iOS Local Network permission. It displays advertised service names and can be incomplete or contain multiple names for one device. It does not claim the exact number of Wi-Fi clients. The exact count must come from the router's management interface; automated integration depends on the router model. Use discovery only on networks you are authorized to administer. The app can open a user-entered private IPv4 router address in Safari over HTTPS; Mercury does not receive the router credentials.

## Privacy policy

### Local processing

Network state, interface addresses, observed byte counters and Bonjour results are processed in memory on your device. The app does not upload those measurements or nearby-device names to a Mercury server. It does not inspect packet contents, browsing history, Wi-Fi passwords or router passwords. It does not read an advertising identifier or use analytics or cross-app tracking. There is no Mercury data-collection backend or third-party analytics SDK.

### Optional network requests

If you tap the HTTPS test, the app sends a HEAD request to https://www.apple.com/library/test/success.html. Apple receives the source IP and normal HTTP/TLS connection metadata under its own privacy policy: https://www.apple.com/legal/privacy/. Local device lists and traffic-counter readings are not included. Mercury does not receive Apple's server logs. The timing includes DNS and TLS and is not an Internet throughput test. Bonjour requests stay on the local network and disclose the requested service types to local devices. No test or discovery is started automatically.

### Manual sharing and support

Diagnostics are shared only if you explicitly export them through the iOS share sheet. The generated report includes time, connection state/type, foreground traffic totals, HTTPS result and service-name count. It omits discovered-device names and local IP addresses. The destination you choose controls its copy. Support receives your email and any content you voluntarily send and uses it to answer your request. Request deletion of developer-held correspondence by email; an unresolved support request or a legal obligation may require retention. Support is optional and no account is required.

### Choices and retention

Metrics are held in memory and are not a permanent usage history. Reset the session to clear traffic samples. Stop discovery or deny/revoke Local Network permission in iOS Settings. Leaving the foreground stops monitoring. Closing the app clears in-memory measurements; exported copies must be removed from their chosen destinations separately. There is no developer account or remotely stored monitoring dataset to delete. Independent websites and router interfaces have their own privacy and security practices.

### Changes

This page will be updated if app functionality or data practices change. The app has no advertising, data sale or paid subscription. It is a general-purpose network utility. Contact support with privacy questions.

## Informații în română

Mercury Network, începând cu buildul 18, este un monitor de rețea fără VPN. Starea conexiunii, adresele locale, traficul observat și rezultatele Bonjour sunt prelucrate în memoria dispozitivului. Nu sunt încărcate pe un server Mercury. Nu inspectăm conținutul traficului, istoricul de navigare sau parolele. Descoperirea locală și testul HTTPS pornesc numai la cerere. Testul HTTPS contactează Apple, care vede IP-ul și metadatele conexiunii; nu primește lista dispozitivelor locale. Contoarele nu sunt consum facturat sau trafic total al routerului. Lista Bonjour este parțială și nu este un număr exact de clienți Wi-Fi. Exportul diagnosticului și suportul prin e-mail sunt opționale. Monitorizarea se oprește în fundal. Contact: valentin.nedelcu@icloud.com. Nu trimite parole sau date sensibile.
