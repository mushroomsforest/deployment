## Mushrooms Finance Security Procedures

This document outlines the Security procedures for Mushrooms Finance, including vulnerability reporting and our [Security Bounty program](#security-bounty-program). 

To submit a reporting, please check the details at [Submit Reporting](#submit-reporting).

## Responsible Disclosure Standard

There is an incredible community-driven effort on security disclosure [standard](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#the-standard) for responsible reporting in cryptocurrency and blockchain-related engineering. 

TL;DR

-   [Initial Contact](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#initial-contact): How to establish initial contact with Mushrooms core dev team.
-   [Giving Details](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#giving-details): What details to include with your vulnerability reporting after having received a reply from Mushrooms core dev to your initial contact.
-   [Setting Dates](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#setting-dates): How to agree on timelines for releasing updates and making details of the issue public available.

## Submit Reporting

Mushrooms Finance is fully committed to co-working with white-hat developers who find and submit security vulnerability notifications to us, to resolve those issues on an appropriate timeline, and to perform a coordinated release, giving credit/reward to the reporter they deserve.

Please submit issues to **ALL** of the following main points of contact for security related issues according to the
[initial contact](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#initial-contact)
& [giving details](https://github.com/RD-Crypto-Spec/Responsible-Disclosure#giving-details)
guidelines.

Also please ensure all related email communication being PGP encrypted or reach out over [keybase encrypted chat](https://keybase.io)

| Main Security Contact  | Public key                                                                                                   | Email                             | Keybase                                                |
| ---------------------- | ------------------------------------------------------------------------------------------------------------ | --------------------------------- | -------------------------------------------------------|
| Mushrooms core dev     | [PGP](https://github.com/mushroomsforest/deployment/blob/main/publickey.earningpool.asc)                     | earningpool at protonmail.com     | [@Mushrooms_Fin](https://keybase.io/Mushrooms_Fin/chat)|


## Reporting Sharing

In the case where we become aware of security issues affecting other projects which howerver has never affected Mushrooms Finance, we might inform those projects of security issues on a best effort basis.

In the case where we fix a security issue in Mushrooms Finance that also affects other partner/well-known projects, our intention is to engage in responsible reporting with them as described in above mentioned security [standard](https://github.com/RD-Crypto-Spec/Responsible-Disclosure).


## Security Bounty Program

Mushrooms Finance has a Bug Bounty program to encourage security white-hat hacker/developer to spend time studying our code in order to uncover vulnerabilities. 
We believe they should get fairly awarded for their time and effort and acknowledged for the remarkable contributions to entire community.

### Rules

1. Bug has **NOT** been publicly disclosed.
2. Vulnerabilities that have been previously submitted by other contributors or already known by the Mushrooms Finance team are not eligible for rewards.
3. The size of the bounty payout depends on the assessment of the severity of the exploit. Please refer to the rewards [section](#rewards) below for additional details.
4. Bugs must be reproducible in order to verify the vulnerability locally in testnet or in some rare case on Ethereum mainnet.
5. Rewards and the validity of bugs are determined by Mushrooms Finance team and any payouts are made at their sole discretion.
6. Terms and conditions of the Bug Bounty program can be changed at any time at the discretion of Mushrooms Finance team.
7. Details of any valid bugs may be shared with complementary protocols utilized in the Mushrooms Finance for the overal benefits of broader community.

### Classifications

-   **Severe:** Highly likely to have a substantial impact on availability/integrity and loss of funds.
-   **High:** Likely to have impact on availability/integrity and loss of funds.
-   **Medium:** Possible to have an impact on availability/integrity.
-   **Low:** Unlikely to have a meaningful impact on availability/integrity.

### Rewards

-   **Severe:** 4000-10000 USDC
-   **High:** 800-4000 USDC
-   **Medium:** 200-800 USDC
-   **Low:** 50-200 USDC

Actual reward payouts are determined by classifying the vulnerability based on its impact and likelihood to be exploited successfully, as well as the process working with the reporting security developer. 
The rewards represent the _maximum_ that will be paid out for a security bug reporting.

Rewards are paid out in [USDC](https://etherscan.io/token/0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48).

### Scope

The scope of the Bug Bounty program spans 1) smart contracts and 2) frontend code utilized in the Mushrooms Finance ecosystem deployed in Ethereum mainnet and the [website](https://mushrooms.finance)

For other artifacts outside of those mentioned above, please do reach out to the Mushrooms Finance core dev team for clarification on a case by case base.

## Credits

Inspired by security practice and guideline from [Yearn](https://github.com/iearn-finance/yearn-protocol/blob/develop/SECURITY.md). Really appreciate
