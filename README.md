# VPN Mercury — Support and Privacy

Updated: 12 November 2026. Applies to VPN Mercury iOS 1.0, including OpenVPN/VPN Gate and manual IKEv2.

## Support

Developer: Iulian Valentin Nedelcu (NEDELCU IULIAN VALENTIN PFA).

Contact: [valentin.nedelcu@icloud.com](mailto:valentin.nedelcu@icloud.com).

For help, provide the app build, iOS version, server hostname, Wi-Fi/mobile data and exact error. Never send passwords, private keys or personal traffic. Diagnostic export is optional and goes only to the recipient you choose.

Open VPN gratuit, read the operator disclosure, refresh the VPN Gate list, select a relay, accept the logging policy and tap Salvează și conectează. Approve the iOS VPN configuration. Connected means iOS reports an active tunnel; Disconnected means it is inactive. An HTTPS response or server list does not prove VPN authentication. Volunteer relays may be unavailable; try another relay or network. Manual IKEv2 needs credentials and certificate identity for the exact server. Never disable certificate validation.

Mercury operates no gateways and promises no particular country, uptime, speed, anonymity or leak protection. There is no active Mercury subscription or charge in this version.

## Privacy policy

### On-device information

Server settings, usernames and preferences stay on the device. VPN passwords are stored in Apple Keychain. Imported configurations and certificates configure the iOS tunnel. This version has no advertising or analytics SDK, advertising identifier, Mercury account or developer-operated data-collection backend.

### VPN operators and logging

Refreshing the directory sends your public IP and required network metadata to VPN Gate. Connecting sends traffic through the selected relay. The operator sees your source IP, connection metadata and traffic destinations. Visibility of content depends on the encryption used by the originating apps.

VPN Gate records connection dates, source/server IPs and hostnames, client/protocol details, packet/byte counts, errors and destination hostnames/IPs/ports. Central connection logs are retained at least three months; volunteer relays retain packet-header logs at least two weeks. Operators may disclose logs through their legal processes. Mercury cannot access, delete or control those logs.

Read the [official VPN Gate logging policy](https://www.vpngate.net/en/about_abuse.aspx) before connecting. Mercury is not affiliated with VPN Gate. Manual IKEv2 operators, including VPN Jantit presets, have independent policies that you must review before supplying credentials. Servers can be in other countries; choose an operator and jurisdiction you trust.

### Diagnostics, support and purposes

The optional HTTPS check sends a HEAD request to the configured domain only when requested, exposing IP and HTTP/TLS metadata to that destination. It is not a tunnel or DNS-leak test. Diagnostics stay local unless exported. Support receives your email and the material you voluntarily send, for resolving your request. Request deletion by email; correspondence may be retained for an unresolved issue or legal obligation. Do not send sensitive material.

Network information is used for connectivity, directory access, diagnosis, security and abuse prevention. Mercury does not sell user data or use it for advertising or cross-app tracking. Independent operators control their processing; Apple and websites have their own policies.

### Choices, deletion and changes

Do not connect if you reject the operator's policy. Disconnect to stop routing. Remove profiles in iOS Settings > General > VPN & Device Management; use the app deletion action for the manual profile/password. Remove saved configurations and uninstall when no longer needed. Contact support about developer-held correspondence; operator-log requests go to the operator and retention may be mandatory. No zero-logging or absolute-anonymity claim is made.

This is a general-purpose networking utility, not a children's service. Its content rating is not a privacy guarantee. This page will be updated when practices change.

## Informații în română

Suport: valentin.nedelcu@icloud.com. Nu trimite parole sau chei private. Configurarea rămâne pe dispozitiv, iar parolele în Keychain. Actualizarea listei transmite IP-ul către VPN Gate. Operatorul VPN vede datele conexiunii și destinațiile traficului. VPN Gate păstrează jurnale de conexiune minimum trei luni și antete de pachete minimum două săptămâni. Mercury nu controlează aceste jurnale și nu garantează anonimat absolut. Consultă politica operatorului înainte de conectare. Exportul diagnosticului și suportul sunt opționale; nu există reclame sau abonament Mercury activ.

## Third-party notices

TunnelKit is used under GPLv3 with its additional App Store permission; dependencies retain their own licenses. Corresponding source and license notices must accompany distributed builds. Contact support for a specific build's source if not listed in this repository. VPN Gate permits clients to use its official CSV directory: [official directory](https://www.vpngate.net/en/). No affiliation or exclusive rights are claimed.
