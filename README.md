# Czech Standard for Open Banking issue tracker

**_COBS overview of changes_**

Version | Note
------- | ----
1.0 | Basic document v.1.0
**1.2** | Document version 1.2 - Correction of typing errors, new error codes, new chart visualizations, coupled payment type codes in response to initiation of payment (Chapter 4.24.2.1) and general element descriptions added / specified.
2.0_draft | Document v.2.0 -- An extension to initiate Instant Payment has been added to the standard. Any further processing of such initiated payment is done according to the rules of this scheme. Chapter 3.2.4, 4.24.1 and 4.25
2.0_draft | Added new request header parameters for original TPP identification
2.0_draft | Extended description of the use of certificates in chaper 1.4.8
GitHub | New overview of the request and response examples
</br>



On 16 November 2015, the European Banking Authority issued the Revised Payment Service Directive (hereinafter: PSD2). As of 13th January 2018, PSD2 will replace former Directive on Payment Services in the Internal Market. A need for this substation was caused by a rapid development of IT, by the birth of brand new types of payment services and by a number of overall changes. Thanks to PSD2 new subjects will be regulated in the field of electronic payments, subjects, which were not in the scope of the previous Directive. Among other things, new legislation opens banking for the so-called third parties.

PSD 2 should be accompanied by number of norms: on one hand certain regulatory technical standards (RTS) have to be adopted, on the other hand guidelines describing rules, which have to be followed in specific situations have to be issued by the EBA (European Banking Authority) too. Unfortunately, during preparation of these documents both the EBA and the European Commission caused some delays, therefore it was necessary to work only with drafts of these papers. Especially missing RTS on Strong Authentication and Secure Communication (RTS on SCA) caused troubles to all stakeholders.

The PSD 2 was implemented into the Czech legislation by the brand new No 370/2018 Coll., Act on Payment Systems, which will come into force on 13th January 2018. Suspended are only those paragraphs of that Act, which refer to the RTS on SCA.

In order to maintain equal competition between all stakeholders, the EBA seeks to maintain neutrality and defines basic rules of functioning in PSD2 at a general level. Despite the specification of open banking rules to third parties, the implementation across particular banks may vary. This versatility implies a more complex, and more expensive integration of third parties to become payment service providers keeping accounts. In order to support the European PSD2 directive and its proper implementation, the banks in the Czech market have decided to standardize their solutions.

The aim of the Czech Standard for Open Banking is to lay down rules for communication, mainly for services defined by the PSD2: Account Information Service Provider (AISP), Payment Initiation Service Provider (PISP), Card Issuing Service Provider (PISP)

The standard is designed and developed to maintain a high degree of versatility. The standard is voluntary, and it is up to each bank to consider joining the standard. With respect to the fact that systems and their operations differ across all payment service providers, standard participants may deviate from the standard at certain points, within the scope of their specific information systems. Since each payment service provider is obliged to document its solution according to PSD2, a large number of fields for optional information is defined in the Czech Open Banking Standard.

The main benefits of the Czech Standard are the easier integration of TPP into systems which banks are offering, including without any other intermediaries, ensuring a uniform interpretation of the PSD2 in the Czech market, compliance with the content of the transmitted data and security elements in communication with banks, support for the unified functioning of services for clients across banks, timely readiness for the implementation of PSD2.

## Actual version of Czech Standard for Open Banking 1.2

* **Czech Standard for Open Banking v.1.2** [[EN](versions/v.1.2/CzechOpenBankingStandard_EN_1.2.pdf)] [[CZ](versions/v.1.2/CzechOpenBankingStandard_CZ_1.2.pdf)]

  ### Previous version of Czech Standard for Open Banking 1.0

  * Czech Standard for Open Banking v.1.0 [[EN](versions/v.1.0/CzechOpenBankingStandard_EN_1.0.pdf)] [[CZ](versions/v.1.0/CzechOpenBankingStandard_CZ_1.0.pdf)]

  ### Future working version of Czech Standard for Open Banking 2.0

  * Czech Standard for Open Banking v.2.0 [[EN](versions/v.2.0/CzechOpenBankingStandard_CZ_2.0.pdf)]

## Examples 
Here you will find an overview of the requests and responses examples for each API resource contained in the standard

* [Examples of API Account Information](examples/JSON/AISP)
* [Examples of API Payment Initiation](examples/JSON/PISP)
* [Examples of API Balance Check](examples/JSON/PIISP)

## Parts

The Czech Standard for Open Banking consists of these parts:

* **Introduction and common features**
* **Technical description**
* **Security standard**
* **Definition of API Account Information**
* **Definition of API Payment Initiation**
* **Definition of API Balance Check**
* **Examples of requests and response of particular API resources in JSON format**

## Contributing & posting issues
You found a bug, have a question? For such cases, you can enter a problem or question in the issue tracker here. Here are some notes on how to proceed in this case.

* First of all, check with what version of the standard you are working on.
* Before you start typing a problem or query, make sure your question is no longer solved.
* To enter a problem or query, you need to know which areas of the standard it concerns. Areas described by the standard are listed above.
* Include all this information in a new issue on our [Issue Tracker](https://github.com/Czech-BA/COBS/issues)