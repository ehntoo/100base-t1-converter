# 100base-t1-converter

This project provides a media converter for connecting 100Base-TX ethernet to
100Base-T1 (Automotive Ethernet) networks, using an NXP TJA1101 PHY. This part
doesn't have a whole lot of officially-available documentation, but is
significantly cheaper than the previous-generation TJA1100. Sufficient
information to use the chip in a design was assembled from various NXP (and
other) schematics online, such as the NXP schematics for the S32K148-T-BOX EVK.

Additional information for debugging was sourced from the Linux TJA11xx PHY
drivers.

The 100Base-TX PHY used is a CoreChips SR8201F (Realtek RTL8201F compatible),
sourceable from LCSC for ~$0.25 in reasonable quantities.
