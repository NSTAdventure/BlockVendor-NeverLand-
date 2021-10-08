# BlockTelemetryAndroid
Hosts file to block Android Telemetry and make privacy free.


## How To Use?
Just add host file or link in any blocker that
You like or on Pi-Hole Or Router

# Warning!

1. Pi-Hole / Router Installation
This will affect all devices that are connected
To same WiFi or internet provider

2. You might can't visit the official website of that vendor
3. You might can't use any or vendor services
(THIS IS INCLUDED CLOUD STORAGE AND OTA UPDATE)

# FAQ
1. Why user must use host list to block annoyance?
Blocking website or domain only work via host list

For example:

127.0.0.1 www.example.com

Or

0.0.0.0 www.example.com

Note: Host file doesn't support of blocking SubDomains,
Eg. If you block example.com then thr SubDomains of the website will not be blocked such as www.example.com or blog.example.com

2. Why must block telemetry? Something wrong with it?.

Telemetry is designed to track you 

We block them to prevent telemetry collect and send your
Data to the company 

We also want to make vendor devices bloatware free

3. Do this blocklist can working on both non root
And rooted devices?

First this just a blocklist not a app,
so you can Use this list
on any your favourite blocking apps
Rooting or not? Depending on the app itself
if using VPN mode then no root required

Alternative way is using firewall and
Block all system app and OTA Update
