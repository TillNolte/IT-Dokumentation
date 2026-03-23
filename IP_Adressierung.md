# IP-Adressierung (IPv4 Grundlagen)

Die IPv4-Adressierung ist ein zentrales Konzept in Netzwerken und dient zur eindeutigen Identifikation von Geräten innerhalb eines IP-Netzwerks. Eine IPv4-Adresse besteht aus 32 Bit und wird üblicherweise in vier Oktette (je 8 Bit) unterteilt, die dezimal dargestellt werden (z. B. 192.168.1.1).

Eine IP-Adresse setzt sich aus einem Netzanteil und einem Hostanteil zusammen. Der Netzanteil identifiziert das Netzwerk, während der Hostanteil das einzelne Gerät innerhalb dieses Netzwerks beschreibt. Welche Bits zu welchem Teil gehören, wird durch die Subnetzmaske festgelegt.

Es gibt verschiedene Adressklassen (A, B, C), die ursprünglich zur Einteilung von Netzgrößen dienten, heute jedoch weitgehend durch CIDR (Classless Inter-Domain Routing) ersetzt wurden. Häufig verwendete private Adressbereiche sind z. B. 192.168.0.0/16 oder 10.0.0.0/8.

IPv4-Adressen können statisch (manuell konfiguriert) oder dynamisch (z. B. per DHCP) vergeben werden. Zusätzlich existieren spezielle Adressen wie die Loopback-Adresse (127.0.0.1) oder die Broadcast-Adresse.

Da der IPv4-Adressraum begrenzt ist (ca. 4,3 Milliarden Adressen), wird zunehmend IPv6 eingesetzt, das einen deutlich größeren Adressraum bietet.