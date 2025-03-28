---
autogenerated: true
title: BaslerAce
redirect_from: 
  - /BaslerAce
  - /BaslerCameras
  - /wiki/BaslerAce
  - /wiki/BaslerCameras

layout: page
---

## Basler Ace USB camera

<table>
<tr>
<td markdown="1">

**Summary:**

</td>
<td markdown="1">

Interfaces Basler Ace line of USB cameras

</td>
</tr>
<tr>
<td markdown="1">

**Author:**

</td>
<td markdown="1">

Henry Pinkard

</td>
</tr>
<tr>
<td markdown="1">

**License:**

</td>
<td markdown="1">

BSD

</td>
</tr>
<tr>
<td markdown="1">

**Platforms:**

</td>
<td markdown="1">

Windows

</td>
</tr>
<tr>
<td markdown="1">

**Devices:**

</td>
<td markdown="1">

Tested on Basler Ace acA2440-75um USB3 Mono. Should work with other
monochrome USB versions and could be adapted to RGB cameras as well

</td>
</tr>
</table>

Download and install **version 7.1** of the Basler Pylon software and verify that it works
prior to setting up in Micro-Manager. The device adapter is know not to work with version 7.2.

<https://www.baslerweb.com/en/sales-support/downloads/software-downloads/#type=pylonsoftware;series=baslerace>


\- If several cameras are connected the first accessible camera per
instance will be addressed.

\- Issues like lost frames may arise due to insufficient hardware
capacity. Please reduce "DeviceLinkThroughputLimit" (GigE: increase
"InterPacketDelay") in this case.

--[Henry Pinkard](/users/Henry_Pinkard), 20th March 2018 (PDT)
--[Henry Pinkard](/users/Henry_Pinkard), Updated 23rd February 2023 (PDT)

