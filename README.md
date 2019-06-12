OWASP Juice Shop is probably the most modern and sophisticated insecure
web application! It can be used in security trainings, awareness demos,
CTFs and as a guinea pig for security tools! Juice Shop encompasses
vulnerabilities from the entire
[OWASP Top Ten](https://www.owasp.org/index.php/OWASP_Top_Ten) along
with many other security flaws found in real-world applications!

For a detailed introduction, full list of features and architecture
overview please visit the official project page:
<http://owasp-juice.shop>

## Setup

### Docker Container

`docker run --rm -p 3000:3000 -dit -e NODE_ENV=ctf fonske/juice-shop:latest`


### From Sources
`git clone https://github.com/jmeys`
`cd juice-shop`
`yarn` or `npm i`
`npm start`


### Deploy on Heroku (free ($0/month) dyno)

1. [Sign up to Heroku](https://signup.heroku.com/) and
   [log in to your account](https://id.heroku.com/login)
2. Click the button below and follow the instructions

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

> This is the quickest way to get a running instance of Juice Shop! If
> you have forked this repository, the deploy button will automatically
> pick up your fork for deployment! As long as you do not perform any
> DDoS attacks you are free to use any tools or scripts to hack your
> Juice Shop instance on Heroku!

## Donations

### PayPal [![PayPal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=paypal%40owasp%2eorg&lc=BM&item_name=OWASP%20Juice%20Shop%20Project&item_number=OWASP%20Foundation&no_note=0&currency_code=USD&bn=PP%2dDonationsBF)

PayPal donations via above button go to the OWASP Foundations and are
earmarked for "Juice Shop". This is the preferred and most convenient
way to support the project.

### Credit Card (through RegOnline)

OWASP hosts a
[donation form on RegOnline](https://www.regonline.com/Register/Checkin.aspx?EventID=1044369).
Refer to the
[Credit card donation step-by-step](https://bkimminich.gitbooks.io/pwning-owasp-juice-shop/content/part3/donations.html#credit-card-donation-step-by-step)
guide for help with filling out the donation form correctly.

## Contributors

The OWASP Juice Shop core project team are:

- [Björn Kimminich](https://github.com/bkimminich) aka `bkimminich`
  ([Project Leader](https://www.owasp.org/index.php/Projects/Project_Leader_Responsibilities))
- [Jannik Hollenbach](https://github.com/J12934) aka `J12934`
- [Timo Pagel](https://github.com/wurstbrot) aka `wurstbrot`

For a list of all contributors to the OWASP Juice Shop please visit our
[HALL_OF_FAME.md](HALL_OF_FAME.md).

## Licensing [![license](https://img.shields.io/github/license/bkimminich/juice-shop.svg)](LICENSE)

This program is free software: you can redistribute it and/or modify it
under the terms of the [MIT license](LICENSE). OWASP Juice Shop and any
contributions are Copyright © by Bjoern Kimminich 2014-2019.

![Juice Shop Logo](https://raw.githubusercontent.com/bkimminich/juice-shop/develop/frontend/src/assets/public/images/JuiceShop_Logo_400px.png)
