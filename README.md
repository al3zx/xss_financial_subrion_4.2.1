# XSS in Subrion 4.2.1 (/panel/configuration/financial/)

**Software link**: Subrion CMS 4.2.1 [https://subrion.org/download/]

**@author**: Alejandro Amorín

**Description**: Cross-site scripting (XSS) vulnerability in /panel/configuration/financial/ of Subrion v4.2.1 allow attackers to execute arbitrary web scripts or HTML via a crafted payload injected into several fields: 'Minimum deposit', 'Maximum deposit' and/or 'Maximum balance'. The vulnerability is triggered when accesing to /profile/funds/ in the main webpage.

## POC

### Minimum deposit

1. Enter to Financial section in the webpage and in 'Minimum deposit' set the payload:

![xss1](https://github.com/al3zx/xss_financial_subrion_4.2.1/assets/20266218/3af862f2-1c46-4bbe-ac33-3c2a7132d757)

2. Go to main page to /profile/funds:

![xss2](https://github.com/al3zx/xss_financial_subrion_4.2.1/assets/20266218/03b0cc4d-0540-4cf9-b965-202f989a32de)

### Maximum deposit

1. Enter to Financial section in the webpage and in 'Maximum deposit' set the payload:
   
![xss3](https://github.com/al3zx/xss_financial_subrion_4.2.1/assets/20266218/27d8b533-24cc-490d-8c8a-537d7439dada)

2. Go to main page to /profile/funds:

![xss4](https://github.com/al3zx/xss_financial_subrion_4.2.1/assets/20266218/ae838672-949c-4336-9643-37d9698fe6d8)

### Maximum balance

1. Enter to Financial section in the webpage and in 'Maximum balance' set the payload:

![xss5](https://github.com/al3zx/xss_financial_subrion_4.2.1/assets/20266218/2df63a31-95c3-4763-99f4-935c88c83d01)

2. Go to main page to /profile/funds:

![xss6](https://github.com/al3zx/xss_financial_subrion_4.2.1/assets/20266218/22b3b3d9-de8d-4bf7-bb45-260bdf306806)
