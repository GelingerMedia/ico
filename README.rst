This package contains Ethereum smart contracts and commnd line toolchain for PentaCore.io Crowdsale.



About the project
=================

`ICO stands for a token or cryptocurrency initial offering crowdsale <https://tokenmarket.net/what-is/ico>`_. It is a common method in blockchain space, decentralized applications and in-game tokens for bootstrap funding of your project.

This project aims to provide standard, secure smart contracts and tools to create crowdsales for Ethereum blockchain.



This package provides

* Crowdsale contracts: token, ICO, uncapped ICO, pricing, transfer lock ups, token upgrade in Solidity smart contract programming language





Token sales
===========

These contracts have been tested, audited and used by several projects. Below are some notable token sales that  have used these contracts

* `Civic <https://www.civic.com/>`_

* `Storj <https://storj.io/>`_

* `Monaco <https://mona.co/>`_

* `DENT <https://dentcoin.com/>`_

* `Bitquence <https://www.bitquence.com/>`_

* `InsureX <http://insurex.co/>`_

* ... and many more!


Features include 
=========================

* **Best practices**: Smart contracts are written with the modern best practices of Ethereum community

* **Separation of concerns**: Crowdsale, token and other logic lies in separate contracts that can be assembled together like lego bricks

* **Testable**: We aim for 100% branch code coverage by automated test suite

* **Auditable**: Our tool chain supports `verifiable EtherScan.io contract builds <http://ico.readthedocs.io/en/latest/verification.html>`_

* **Reusable**: The contract code is modularized and reusable across different projects, all variables are parametrized and there are no hardcoded values or magic numbers

* **Refund**: Built-in refund and minimum funding goal protect investors

* **Migration**: Token holders can opt in to a new version of the token contract in the case the token owner wants to add more functionality to their token

* **Reissuance**: There can be multiple crowdsales for the same token (pre-ICO, ICO, etc.)

* **Emergency stop**: To try to save the situation in the case we found an issue in the contract post-deploy

* **Build upon a foundation**: Instead of building everything from the scratch, use `OpenZeppelin contracts <https://github.com/OpenZeppelin/zeppelin-solidity/>`_ as much as possible as they are the gold standard of Solidity development



