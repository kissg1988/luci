# LuCI-BSD - FreeBSD Embedded Configuration Interface

## Description

WARNING: this is a WiP meaning it's not yet functional! There's lots of work to do, yet...

This is a port of OpenWrt's LuCI interface created to provide a basic administration interface for embedded systems running FreeBSD. The project has been renamed to "LuCI-BSD - FreeBSD Embedded Configuration Interface" to provide a clear distinction from the parent project. There are plenty of differences between OpenWrt and FreeBSD, therefore any added or modified code in this project is strictly FreeBSD-specific and should not be merged back to the parent project at any point of time.

The project aims to provide a basic administration interface to configure FreeBSD built for embedded systems. Initial features include the most basic areas of configuration with a possibility to extend capabilities using modules.

Supported features are:

* System: hostname, timezone and NTP configuration
* Administration: change password for root, configure remote access settings (dropbear)
* Startup: manage system services
* Scheduled tasks: configure cronjobs
* Reboot: reboot the system
* Interface: configure network interfaces (VLANs, ethernet interfaces, bridges)
* Wireless: set channel, TX power, SSID & password, list associated stations. Supports access point mode only with WPA2-PSK. Other options might be added later.
* DHCP and DNS: configure dnsmasq options
* Hostnames: configure static host->IP associations in /etc/hosts
* Static routes: configure static IPv4 routes (IPv6 support might be added later)
* Firewall: turn on/off firewall, configure ipfw & NAT rules

## API Reference

You can browse the generated API documentation [directly on Github](http://htmlpreview.github.io/?http://raw.githubusercontent.com/openwrt/luci/master/documentation/api/index.html).

## License

See [LICENSE](LICENSE) file.
