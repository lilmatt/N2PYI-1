N2PYI-1
=======

###An [APRS][1] digipeater and igate, located at my house in Etna, NY.

--------------------------------------------------------------------------

###Hardware:
- Linksys [WRT54GL][2] wireless router
    - Two serial ports added using Compsys [ST232A][3] TTL to RS232 level shifters
- Kenwood [TR-7950][4] 45w 2m mobile transceiver
- Kantronics [KAM Plus][5] TNC (v8.2) in KISS mode
- Samlex [SEC-1223][6] 23A 12VDC switching power supply
- Hustler 2m 1/4 wave ground plane antenna

###Software:
- [OpenWRT][8]: Linux for embedded devices such as wireless routers
- [aprx][9]: Extremely efficient digipeater and igate daemon




[1]: http://aprs.org "Automatic Packet Reporting System"
[2]: http://en.wikipedia.org/wiki/Linksys_WRT54G_series#WRT54GL
[3]: http://www.compsys1.com/workbench/On_top_of_the_Bench/Max233_Adapter/max233_adapter.html
[4]: http://www.universal-radio.com/catalog/fm_txvrs/tr7930.html
[5]: http://www.rigpix.com/packetsstvdata/kantronics_kamplus.htm
[6]: http://www.samlexamerica.com/products/ProductDetail.aspx?pid=62
[8]: https://openwrt.org/
[9]: http://wiki.ham.fi/Aprx.en

--------------------------------------------------------------------------

Actual in use configuration files, and items changed from default are stored in this repository.
