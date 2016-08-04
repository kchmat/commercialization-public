---
author: joshbax-msft
title: WiFi Direct Proximity Tests - MultiMachine EndToEnd Host PreAP5
description: WiFi Direct Proximity Tests - MultiMachine EndToEnd Host PreAP5
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: c02c6627-de0e-4d20-9dbf-76fd14485cc6
---

# WiFi Direct Proximity Tests - MultiMachine EndToEnd Host PreAP5


This test verifies a basic end-to-end scenario by using the PeerFinder APIs over Wi-Fi Direct. A connection between three machines is established and a small amount of data is exchanged between the host and clients. The device under test (DUT) connects to a 5 GHz access point (AP) before the test begins.

## Test details


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Associated requirements</strong></p></td>
<td><p>Device.Network.WLAN.CSBWiFiDirect.SupportAtLeast2WiFiDirectPortsConcurrently Device.Network.WLAN.CSBWiFiDirect.SupportAtLeast4Clients Device.Network.WLAN.WiFiDirect.SupportAtLeast2WiFiDirectPortsConcurrently Device.Network.WLAN.WiFiDirect.SupportAtLeast4Clients</p>
<p>[See the device hardware requirements.](http://go.microsoft.com/fwlink/p/?linkid=254483)</p></td>
</tr>
<tr class="even">
<td><p><strong>Platforms</strong></p></td>
<td><p>Windows RT 8.1 Windows 8.1 x64 Windows 8.1 x86</p></td>
</tr>
<tr class="odd">
<td><p><strong>Expected run time</strong></p></td>
<td><p>~6 minutes</p></td>
</tr>
<tr class="even">
<td><p><strong>Categories</strong></p></td>
<td><p>Certification Functional</p></td>
</tr>
<tr class="odd">
<td><p><strong>Type</strong></p></td>
<td><p>Automated</p></td>
</tr>
</tbody>
</table>

 

## Running the test


Before you run the test, complete the test setup as described in the test requirements: [Wireless LAN (802.11) Testing Prerequisites](wireless-lan--80211--testing-prerequisites.md).

This test requires three computers and two DD-WRT-capable access points.

## Troubleshooting


For troubleshooting information, see [Troubleshooting Wireless LAN (802.11) Tests](troubleshooting-wireless-lan--80211--tests.md).

## More information


### Command syntax

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Parameter</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>AP1IPAddress</strong></p></td>
<td><p>IP Address of the first AP that connects to the system.</p></td>
</tr>
<tr class="even">
<td><p><strong>AP2IPAddress</strong></p></td>
<td><p>IP Address of the second AP that connects to the system.</p></td>
</tr>
<tr class="odd">
<td><p><strong>AP1Password</strong></p></td>
<td><p>Root password for the first AP that connects to the system.</p></td>
</tr>
<tr class="even">
<td><p><strong>AP2Password</strong></p></td>
<td><p>Root password for the second AP that connects to the system.</p></td>
</tr>
</tbody>
</table>

 

## Related topics


[WiFi Direct Proximity Tests](wifi-direct-proximity-tests.md)

 

 






