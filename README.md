Welcome to the Hydro Community Development Program!
Overview
The HCDP is a core program to Project Hydro. It is a collection of paid developer bounties run by the Hydro Community to advance the ecosystem or its products. Any community member can post and create a task for others to fulfill. These tasks could be for an SDK or library, dApps (Solidity), tutorials, enhancements and more. Tasks get assigned a bounty total and are paid upon fulfilling the requirements.

Participation & Process
Anyone can participate. Tasks get posted by the community and other community developers apply by filling out a form and commenting on the Github task. We review all applicants and their qualifications. An assignment is made with another Hydro Labs DA and project work begins. Milestones are set and checkins take place. Once a deliverable has been made, it is reviewed by the team or a 3rd party audit is preformed. There may be edits needed to code based on feedback. Once a code review is complete, code is buttoned up with a descriptive readme file and looks great, payment is made to the developer. Read more here.

To view a list of open tasks that can be applied for, visit our active HCDP bounties page.

List of Completed Hydro Tasks:
The following is a list of tasks successfully completed as part of the HCDP by our growing developer community to advance the Hydro ecosystem. Developers can utilize these plugins, smart contracts and code in their development to jump start their project or leverage advanced functionality without re-inventing the wheel.

Hydro Smart Contracts:
Hydro Marketplace Coupons: This project is essentially a chain of Ethereum smart contracts built on top of the Hydro Snowflake protocol, aiming to provide a marketplace platform for sellers to launch their own stores and sell to users. Coupons are also featured, allowing users to use globally defined coupons guaranteed to expire within a certain time period, or assigning coupons per Snowflake EIN, manageable via multiple addresses. The marketplace itself is a Snowflake Resolver contract, which interacts with a Snowflake Via contract to handle the transaction (and thus coupon discount) logic.

Task Reference: Issue #255
Developer Bounty: 3,000,000 Hydro (txn)
Author: @Luiserebii
Deliverable: Solidity Smart Contract
Hydro Lottery: An Ethereum smart contract uses Hydro Snowflake Ids (EINs) for creating unique lotteries with rewards setup in HYDRO tokens instead of ETH. It's made of an HydroEscrow contract that holds HYDRO for each unique lottery, a Randomizer contract that generates random numbers with Oracles for creating unique, secure randomized numbers for selecting winners and a HydroLottery contract that takes care of the main logic.

Task Reference: Issue #256
Developer Bounty: 4,000,000 Hydro (txn)
Author: @merlox
Deliverable: Solidity Smart Contract
Hydro Interest: An Ethereum smart contract on top of Hydro Snowflake that allows a certain percentage of interest on a defined principal amount, in HYDRO, to accrue and be charged (or paid) to a wallet tied to a SnowflakeID, and then for that balance to automatically be withdrawn (or paid). The smart contract will guarantee that the money is in the account by enforcing an escrow of the accruing payment within the wallet, thus eliminating payment default, or fraud from institutions. This utility smart contract will power charging interest in many future savings, lending, credit, and mortgage Hydro dApps. There will be Layer-3 dApps and Layer-4 APIs that hook into this utility smart contract function.

Task Reference: Issue #264
Developer Bounty: 4,000,000 Hydro (txn)
Author: @ricktobacco
Deliverable: Solidity Smart Contract
Hydro Product Orders: An Ethereum smart contract on top of Hydro Snowflake that allows you to publish products, purchase them with HYDRO and dispute orders in case there's any problem. Remember to install all the dependencies with npm i before running the tests or using the contracts. All the contract code is stored inside the contracts folder.

Task Reference: Issue #256
Developer Bounty: 4,000,000 Hydro (txn)
Author: @merlox
Deliverable: Smart Contract
Hydro Gift Cards: An Ethereum smart contract on top of Hydro Snowflake that allows a certain percentage of interest on a defined principal amount, in HYDRO, to accrue and be charged (or paid) to a wallet tied to a SnowflakeID, and then for that balance to automatically be withdrawn (or paid). The smart contract will guarantee that the money is in the account by enforcing an escrow of the accruing payment within the wallet, thus eliminating payment default, or fraud from institutions. This utility smart contract will power charging interest in many future savings, lending, credit, and mortgage Hydro dApps. There will be Layer-3 dApps and Layer-4 APIs that hook into this utility smart contract function.

Task Reference: Issue #253
Developer Bounty: 4,000,000 Hydro (txn)
Author: @kdmukai
Deliverable: Solidity Smart Contract
Hydro Invoicing: An Ethereum smart contract on top of Hydro Snowflake that allows a business to invoice another business or consumer for a specific amount, on a specified date, and in a certain amount of Hydro. This Ethereum smart contract is built on top of Hydro Snowflake.

Task Reference: Issue #254
Developer Bounty: 3,000,000 Hydro (txn)
Author: @clemlak
Deliverable: Solidity Smart Contract
Hydro Finance: An Ethereum smart contract on top of Hydro Snowflake that stores your credit cards, bank and investment accounts in one solidity contract named HydroFinance.sol using encryption to secure data on the blockchain. It receives the credit card data, encrypts it using your unique EIN identifier and stores that information into your user account. You can then generate the encryption result off-chain using web3.utils.soliditySha3() and your required parameters, to generate the hash that you can use to verify your account. This is the only method to securely protect data on the open blockchain since we can't store sensitive information without encryptions.

Task Reference: Issue #257

Developer Bounty: 3,000,000 Hydro (txn)

Author: @merlox

Deliverable: Solidity Smart Contract

3rd Party Hydro Plugins:
Raindrop Client - Wordpress Plugin: Hydro Multi Factor Authentication Plugin (MFA) for Wordpress adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.

Task Reference: Issue #202, Issue #223, and Issue #230
Developer Bounty: 500,000 Hydro (txn, txn, txn)
Author: @adrenth
Deliverable: Wordpress Plugin
Raindrop Client - Joomla Plugin: Hydro Multi Factor Authentication Plugin (MFA) for Joomla adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.

Task Reference: Issue #219
Developer Bounty: 700,000 Hydro (txn, txn)
Author: @DaveM2011, @realquink, @mitdralla
Deliverable: Joomla Plugin
Raindrop Client - Laravel Plugin: Hydro Multi Factor Authentication Plugin (MFA) for Laravel adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.

Task Reference: Issue #272
Developer Bounty: 2,000,000 Hydro (txn)
Author: @adrenth, @realquink, @mitdralla
Deliverable: Laravel Plugin
Raindrop Client - SalesForce Plugin: Hydro Multi Factor Authentication Plugin (MFA) for OctoberCMS adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.

Task Reference: Issue #220
Developer Bounty: 800,000 Hydro
Author: @brett91ag
Deliverable: SalesForce Plugin
Raindrop Client - Drupal Plugin: Hydro Multi Factor Authentication Plugin (MFA) for OctoberCMS adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.

Task Reference: Issue #217
Developer Bounty: 800,000 Hydro (txn)
Author: @proofoftom
Deliverable: Drupal Plugin
Raindrop Client - OctoberCMS Plugin: Hydro Multi Factor Authentication Plugin (MFA) for OctoberCMS adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.

Task Reference: Issue #254
Developer Bounty: 800,000 Hydro (txn)
Author: @crypt0h3nk
Deliverable: OctoberCMS Plugin
Raindrop Client - Passport.js Module: Hydro Multi Factor Authentication Plugin (MFA) for Passport.js adds another security layer to your website using blockchain-based authentication layer. It’s designed to work out of the box and offers unparalleled security standards for your website and your users, even beating google authenticator which is prone to phishing scams.

Task Reference: Issue #211
Developer Bounty: 500,000 Hydro (txn, txn)
Author: @Red-Maximus
Deliverable: Passport.js Module
Hydro SDKs:
Hydro Raindrop SDK for PHP: This PHP library provides a suite of convenience functions intended to simplify the integration of Hydro's Raindrop authentication into your project. More information, including detailed API documentation, is available in the Raindrop documentation.

Task Reference: Issue #208
Developer Bounty: 200,000 Hydro (txn)
Author: @adrenth
Deliverable: SDK
Hydro Raindrop SDK for Java: This Java library provides a suite of convenience functions intended to simplify the integration of Hydro's Raindrop authentication into your project. More information, including detailed API documentation, is available in the Raindrop documentation.

Task Reference: Issue #209
Developer Bounty: 200,000 Hydro (txn)
Author: @serkanalgl
Deliverable: SDK
Hydro Raindrop SDK for ColdFusion: This ColdFusion library provides a suite of convenience functions intended to simplify the integration of Hydro's Raindrop authentication into your project. More information, including detailed API documentation, is available in the Raindrop documentation.

Task Reference: Issue #212
Developer Bounty: 25,000 Hydro (txn)
Author: @brett91ag
Deliverable: SDK
Hydro Code Audits:
Decentralized Ambassador Smart Contract: The Decentralized Ambassador (DA) Program is an initiative to more heavily involve the Hydro community in the ongoing decentralization and global expansion of the Hydro blockchain ecosystem. This task is to evaluate the current master state of the Solidity code in the DA Program smart contract, in order to identify any areas of potential improvement.

Task Reference: Issue #218
Developer Bounty: 450,000 Hydro (txn, txn)
Author: @clemlak, @samglos
Deliverable: Smart Contract Audit
Misc Development:
Hydro Raindrop Wordpress Testing: Testing and quality evaluation of the Hydro Raindrop Wordpress Plugin code, functionality and front end UI.

Task Reference: Issue #236
Developer Bounty: 200,000 Hydro (txn, txn, txn)
Author: @adrenth, @realquink, @Riskex1
Deliverable: Testing
Snowflake Identicon Generator - Library: The Decentralized Ambassador (DA) Program is an initiative to more heavily involve the Hydro community in the ongoing decentralization and global expansion of the Hydro blockchain ecosystem. This task is to evaluate the current master state of the Solidity code in the DA Program smart contract, in order to identify any areas of potential improvement.

Task Reference: Issue #221
Developer Bounty: 600,000 Hydro (txn, txn)
Author: @cyphercodes96, @Amirh24
Deliverable: Smart Contract Audit
Snowflake Identicon Generator - Design: The Decentralized Ambassador (DA) Program is an initiative to more heavily involve the Hydro community in the ongoing decentralization and global expansion of the Hydro blockchain ecosystem. This task is to evaluate the current master state of the Solidity code in the DA Program smart contract, in order to identify any areas of potential improvement.

Task Reference: Issue #226
Developer Bounty: 600,000 Hydro (txn)
Author: @puppetbrain
Deliverable: Snowflake Design Assets
