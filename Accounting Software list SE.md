# Accounting Software list SE
For small companies in Sweden.

General features one might need:
* SIE4 import and export (Swedish standard for accounting data exchange) - if you ever want to make an accountant take over or help (or to change software within Sweden)
* Support for [BAS chart](https://en.wikipedia.org/wiki/BAS_(accounting)) the Swedish standard for account numbers


My frustration with Fortnox (horrendously overpriced crapy piece of software) made me create this list. In hopes of finding a good solution for small and tiny companies.

Learning: Good old simple locally run software still exists. Sometimes even with single payment for perpetual use.


## FOSS
* [Fribok by JFS Accounting (Java)](https://sourceforge.net/projects/jfsaccounting/) and [here](https://fribok.org): A company that stopped being profitable open sourced its code. Still used by people. Latest update: End of 2021. Not bad.

## Free core but payed additions
* [Hansa World Standard Accounts (Mac only)](http://books.hansaworld.com/eng/accounts/overview): Additional modules cost 10 EUR each

## Perpetual license (some offer support agreement)
* [Stelvio (Mac only)]([http://www.ct.se/index.html]): Many (too many?) editions with different levels of functionality. Starts at 295 SEK. They have demo editions for each edition. Every version has full SIE4 support for read and write.
* [Adaro (Mac only)](https://adaro.se/produkter/adaro-bokforing/): Looks good, in AppStore, Demo available, 690 SEK. Might be with free updates as it is in the AppStore. Not sure.

## SaaS or Licence
* [Agera e Affärssystem (Mac/Windows)](https://www.montania.se/produkter/agera-e-affarssystem/): Based on FileMaker - Abstraction doesn't work, don't have much hope. No prices online.

## SaaS
* [WREBIT](https://wrebit.se/wrebitplus/): Accounting in an app - seems weird enough to have a look at
* [Kapitas](https://www.kapitas.se/funktioner/bokforing): Cheaper than others but still subscription
* [iOrdning (Mac only)](https://www.aderstedtsoftware.com/iordning/): 499 SEK per year. Without a active subscription there is a limit of 10 verifications.
* [Bokis (Windows only)](https://www.bokis.info/index.html): 300...800 SEK per year. Includes some support.
* [AbRedo (Windows only)](https://www.abredo.se/page1.html): 1020 SEK per year. Ugliest website I've seen in a long time.
* [Unicell (Windows and Mac)](https://www.unicell.se/bokforingsprogram_faktureringsprogram.php): 1600 SEK plus 100 SEK per month minimum. Unclear if service agreement is a requirement for product (UNI_ONE).


# Plaintext accounting
[plaintextaccounting.org](https://plaintextaccounting.org) lists software, cookbooks, docs etc. regarding accounting software based on plain text files.

Examples of such programs:
* Ledger (C++)
* Beancount (python, from version 3 C++ plus python)
* hledger (haskell)

Advantages:
* File format is open and quite standard (one can switch software)
* There is a lot of code for importing data from different sources (such as Banks)
* Very programmer friendly, easy to write some code which automates something

There is a [vscode extension](https://marketplace.visualstudio.com/items?itemName=mariosangiorgio.ledger) to check syntax live (so one doesn't get error messages when parsing the file).


# Other tools
* [invoice2data](https://github.com/invoice-x/invoice2data): Extracts data from pdf invoices. command line tool and python library. Currently 1.6k Github stars.

