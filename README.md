# Networker
#### Roblox networking module

Simple - no bloat, close to roblox API<br>
Easy - provides api to easily optimise

Typechecking - made with --!strict from the beginning

Efficient - faster api calls, less data
(Measuring 50 calls, code in testing game)
- Networker: 60μs call, 2.4KB, 53ms ping
- BridgeNet2: 70μs call, 2.9 KB, 54ms ping
- Roblox default: 200μs call, 5 KB, 53ms ping
- FastNet: 20μs call, 6 KB, 170ms ping

Secure - makes remote spy exploit outputs less readable, and server modules are not exposed to the client
