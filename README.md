# XSS in Subrion 4.2.1 (/panel/configuration/financial/)

**Software link**: Subrion CMS 4.2.1 [https://subrion.org/download/]

**@author**: Alejandro Amorín

**Description**: Cross-site scripting (XSS) vulnerability in /panel/configuration/financial/ of Subrion v4.2.1 allow attackers to execute arbitrary web scripts or HTML via a crafted payload injected into several fields: 'Minimum deposit', 'Maximum deposit' and/or 'Maximum balance'. The vulnerability is triggered when accesing to /profile/funds/ in the main webpage.

## POC
