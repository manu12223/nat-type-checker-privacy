# Privacy Policy — NAT Type Checker

_Last updated: 23 July 2026_

NAT Type Checker ("the app") is a utility that determines your network's NAT
type. This policy explains what the app accesses, why, and what happens to it.
The short version: the app does the minimum needed to run the test, keeps
nothing, and shares nothing with third parties.

## What the app accesses

- **Your public IP address.** To classify your NAT, the app sends small UDP
  messages to its check server. As with any internet connection, the server
  sees the public IP address and port your traffic comes from — that mapping
  is exactly what the test measures. Your public IP is shown to you on the
  results screen.
- **Local network information (on your device).** The app reads your device's
  local network interface addresses and the active connection type (Wi‑Fi,
  mobile data, VPN, Ethernet) to detect your NAT type and whether you are
  behind carrier‑grade NAT (CGNAT). This information is read on your device
  and displayed to you; it is not transmitted.

## How it is used

Everything above is used solely to perform the NAT test you requested and to
show you the results (NAT type, local and public IP, ports, mapping/filtering
behavior, and response times). There is no other use.

## Storage and retention

- **On your device:** the app does not save your results or any personal data.
  Nothing persists after you close the app.
- **On the server:** the check server processes your IP transiently to reply to
  your request and does **not** store it. The server keeps only aggregate,
  anonymous counters (e.g. how many checks ran), which contain no IP addresses
  or other identifying information.

## Sharing

The app does not share any data with third parties. It contains no advertising,
no analytics or tracking SDKs, and no third‑party services. The only network
destination is the app's own check server.

## Permissions

- `INTERNET` — to send the UDP test packets.
- `ACCESS_NETWORK_STATE` — to read the active connection type for NAT/CGNAT
  detection.

## Children

The app is a general‑purpose network utility, collects no personal profiles,
and is suitable for all ages.

## Changes to this policy

If this policy changes, the "Last updated" date above will change accordingly.

## Contact

Questions about this policy can be sent to: studio2446dev@gmail.com
