<!-- SPDX-License-Identifier: CC-BY-4.0 OR GPL-3.0-or-later -->
<!-- This file is part of Network Pro -->

<!--
Network Pro Strategies (Network Pro)
Copyright © 2024-2025 Scott Lopez

---

I. Creative Commons Attribution 4.0 International

Network Engineering Pro (the "Licensed Material") is licensed under Creative Commons Attribution 4.0 International ("CC BY 4.0"). To view a copy of this license, visit https://creativecommons.org/licenses/by/4.0/.

Per the terms of the License, you are free to distribute, remix, adapt, and build upon the Licensed Material for any purpose, even commercially. You must give appropriate credit, provide a link to the License, and indicate if changes were made.

The Licensor offers the Licensed Material as-is and as-available, and makes no representations or warranties of any kind concerning the Licensed Material, whether express, implied, statutory, or other. This includes, without limitation, warranties of title, merchantability, fitness for a particular purpose, non-infringement, absence of latent or other defects, accuracy, or the presence or absence of errors, whether or not known or discoverable.

Permissions beyond the scope of this License—or instead of those permitted by this License—may be available as further defined within this document.

  SPDX Reference: https://spdx.org/licenses/CC-BY-4.0.html
  Canonical URL: https://creativecommons.org/licenses/by/4.0/

---

II. GNU General Public License

Network Engineering Pro is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License ("GNU GPL") as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This material is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

See the GNU General Public License for more details.

  SPDX Reference: https://spdx.org/licenses/GPL-3.0-or-later.html
  Canonical URL: https://www.gnu.org/licenses/gpl-3.0.html

---

Author: Scott Lopez
Email: <contact@neteng.pro>
Web: <https://bio.neteng.pro>
-->

[SPDX-License-Identifier](https://spdx.dev/learn/handling-license-info/): `CC-BY-4.0 OR GPL-3.0-or-later`

# <a id="top">Hardening-Brave-Browser</a>

1. **Download Brave Browser** from [Brave](https://www.brave.com) or GitHub:  
   ✅ [brave/brave-browser](https://github.com/brave/brave-browser)

> _For managing privacy-centric browser installations and updates, we highly
> recommend **FFUpdater**:_
>
> - F-Droid: [FFUpdater](https://f-droid.org/packages/de.marmaro.krt.ffupdater/)
> - GitHub: [Tobi823/ffupdater](https://github.com/Tobi823/ffupdater)

---

<!-- markdownlint-disable MD029 -->

2. **Off Telemetry** ✅  
   ![Picsart_22-12-08_12-45-24-332](https://user-images.githubusercontent.com/104879897/206441617-bd616617-cdb4-4039-92d6-a6e1c355dcd5.jpg)

<sub>[Top](#top)</sub>

---

3. **Block Trackers & Ads (Aggressive)** ✅  
   ![Picsart_22-12-08_12-50-59-319](https://user-images.githubusercontent.com/104879897/206441632-1412567b-0fc5-462a-8ba2-c6573a333b3e.jpg)

<sub>[Top](#top)</sub>

---

4. **Block JavaScript** ✅  
   _Enable JavaScript for that site only when needed for trusted sites_  
   ![Picsart_22-12-08_13-02-34-388](https://user-images.githubusercontent.com/104879897/206441690-4a5dba7e-7d6d-4652-8e23-c9bb360edd86.jpg)

<sub>[Top](#top)</sub>

---

5. **Block All Cookies** ✅  
   _Enable cross-site cookies for only that site when needed_
   ![Picsart_22-12-08_13-05-20-628](https://user-images.githubusercontent.com/104879897/206441699-0c69dcc6-e4b2-490d-9f1c-a77c68f73de6.jpg)

<sub>[Top](#top)</sub>

---

6. **Enable Strict Fingerprinting Mode** ✅  
   _Strict fingerprinting protection is now a hidden feature_

   - Navigate to `brave://flags` and search for
     `brave-show-strict-fingerprinting-mode`
   - Toggle the setting to `Enabled` and select the `Relaunch` button

   ![Enable Strict Fingerprinting Mode](https://raw.githubusercontent.com/NetEng-Pro/Hardening-Brave-Browser/refs/heads/master/assets/fingerprinting.png "Enable Strict Fingerprinting")

&nbsp;

7. **Block Fingerprinting (Strict)** ✅  
   _Change to '**Fingerprinting blocked (Standard)**' for only that site when
   needed for trusted sites_  
   ![Picsart_22-12-08_14-54-12-532](https://user-images.githubusercontent.com/104879897/206441701-8853f5e1-b948-49f2-9e27-d95bc394300f.jpg)

<sub>[Top](#top)</sub>

---

8. **Off Social Media & other privacy settings** ✅  
   ![Picsart_22-12-08_15-03-11-858](https://user-images.githubusercontent.com/104879897/206441705-0085cdbd-e965-489e-9f5a-79e1b13bf3ad.jpg)

<sub>[Top](#top)</sub>

---

9. **Off Usage Ping** ✅  
   ![Picsart_22-12-08_15-07-12-723](https://user-images.githubusercontent.com/104879897/206441711-5fcb658e-9250-4bcf-8fc5-f6e2e77604f3.jpg)

<sub>[Top](#top)</sub>

---

10. **Off Web3 Notifications** ✅  
    ![Picsart_22-12-08_15-09-15-170](https://user-images.githubusercontent.com/104879897/206441716-aa9e879d-ab48-47f6-86b0-44f78ec0d4b9.jpg)

<sub>[Top](#top)</sub>

---

11. **Change Search Engine** ✅  
    ![Picsart_22-12-08_15-10-39-560](https://user-images.githubusercontent.com/104879897/206441720-daedc536-d771-48e6-b0f4-4c618285f8e0.jpg)

<!-- markdownlint-enable MD029 -->

> [Brave Search](https://search.bravesearch.brave.com) or a self-hosted
> [SearXNG](https://docs.searxng.org) instance is preferable. Avoid Google and
> Bing at all costs!

> Other options, in order of privacy reputation:
>
> - [SearXNG](https://docs.searxng.org)
> - [Mojeek](https://www.mojeek.com)
> - [Startpage](https://www.startpage.com)
> - [Kagi](https://kagi.com)<sup>1</sup>
> - [DuckDuckGo](https://www.duckduckgo.com)<sup>2</sup>

> Ecosia is also supposedly a very good, privacy-centric search engine. We're
> not as familiar with Ecosia, so we can't recommend it, but it deserves
> mention.

> <sup>1</sup> <sub>Kagi is a paid service. However, anecdotally we've heard the
> service is well worth the price.</sub>  
> <sup>2</sup><sub> DDG's privacy reputation has taken a hit of late. Based on
> available sources, it seems DDG utilizes Bing [Google?] results on the back
> end.

<sub>[Top](#top)</sub>

---

12. **Off Save Passwords & Auto Sign-in** ✅  
    ![Picsart_22-12-08_15-12-47-025](https://user-images.githubusercontent.com/104879897/206441725-873fa3ac-d077-43c1-9654-9501149da467.jpg)

> It is a best practice to utilize a password manager rather than the built-in
> browser password management.

> Recommended password managers:
>
> - [Proton Pass](https:/www.proton.me/pass)
>   ([Proton AG](https://www.proton.me))
> - [Bitwarden](https://www.bitwarden.com)

<sub>[Top](#top)</sub>

---

13. **Change Appearance** ✅  
    ![Picsart_22-12-08_15-15-22-649](https://user-images.githubusercontent.com/104879897/206441728-12393aef-3354-428d-8441-74268f9ec5b2.jpg)

<sub>[Top](#top)</sub>

---

Special thanks to the original publisher of this material,
**[@finalboss@mas.to](https://mas.to/@finalboss).**  
Forked from
[piyushkumar-prog/Hardening-Brave-Browser](https://github.com/piyushkumar-prog/Hardening-Brave-Browser).

&nbsp;

<style type="text/css">
.bg  {border-collapse:collapse;border-spacing:0;margin:0px auto;}
.bg td {border-color:transparent;border-width:1px;font-family:Arial, Helvetica, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.bg th {border-color:transparent;border-width:1px;font-family:Arial, Helvetica, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.bg .bg-cell {text-align:center;vertical-align:top}
@media screen and (max-width: 767px) {.tg {width: auto !important;}.tg col {width: auto !important;}.tg-wrap {overflow-x: auto;-webkit-overflow-scrolling: touch;margin: auto 0px;}}</style>
<div class="bg-wrap"><table class="bg"><tbody>
  <tr>
    <td class="bg-cell"><a rel="noopener noreferrer" href="https://creativecommons.org/licenses/by/4.0/"><img src="https://forthebadge.com/images/badges/cc-by.png" alt="CC BY 4.0"></a></td>
    <td class="bg-cell"><a rel="noopener noreferrer" href="https://www.gnu.org/licenses/gpl-3.0.html"><img src="https://img.shields.io/badge/LICENSE-GPLv3-red?style=for-the-badge&labelColor=9b9b9b&color=d0021b" alt="GPL v3 or later"></a></td>
    <td class="bg-cell"><a rel="noopener noreferrer" href="https://my.fsf.org/join?referrer=6725885"><img src="https://netwk.pro/img/fsf-member.png" alt="Free Software Foundation">
    </td>
  </tr>
</tbody>
</table></div>

&nbsp;

[Terms and Conditions](https://github.com/NetEng-Pro/neteng-pro.github.io/blob/master/legal/TERMS.md) &nbsp; | &nbsp; [Copyright and Licensing](https://github.com/NetEng-Pro/neteng-pro.github.io/blob/master/LICENSE.md) &nbsp; | &nbsp; [Privacy Policy](https://github.com/NetEng-Pro/neteng-pro.github.io/blob/master/legal/PRIVACY.md)

&nbsp;

**[Network Pro Strategies](https://netwk.pro/) (Network Pro)**  
Copyright &copy; 2024-2025 **[Scott Lopez](https://bio.neteng.pro)**

Licensed under **[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)** and the **[GNU GPL](https://spdx.org/licenses/GPL-3.0-or-later.html)**, as published by the Free Software Foundation,  
either version 3 of the License, or (at your option) any later version.
