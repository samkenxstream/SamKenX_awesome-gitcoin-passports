<!--
To Do:
- 


Inspiration:
https://github.com/jthegedus/awesome-firebase/blob/main/readme.md
https://github.com/Derjyn/awesome-stripe/blob/master/README.md
https://github.com/unicodeveloper/awesome-nextjs/blob/master/README.md
https://github.com/prayash/awesome-gatsby/blob/master/README.md
https://github.com/sindresorhus/awesome-nodejs/blob/main/readme.md
https://github.com/lyqht/awesome-supabase/blob/main/README.md
https://github.com/testthedocs/awesome-docs/blob/main/README.md
https://github.com/algolia/awesome-algolia/blob/master/README.md
https://github.com/sindresorhus/awesome/blob/main/readme.md
https://github.com/agamm/awesome-developer-first/blob/main/README.md
-->
<div id="top"></div>

# Awesome Gitcoin Passports [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[ <img src="./static/passport.svg" alt="Logo" width="350" height="100" align="right"> ](https://go.gitcoin.co/passport?utm_source=awesome-passports&utm_medium=referral&utm_content=Passport)

> Curated list of all the resources, articles, and code samples about using Gitcoin's Passport and Stamps

[Gitcoin Passport](https://go.gitcoin.co/passport?utm_source=awesome-passports&utm_medium=referral&utm_content=Passport): Protect Your Community From Bots and Bad Actors, all without storing your users’
personal information.

## Contents

- [Featured](#featured)
- [Official Docs and Quickstarts](#official-docs-and-quickstarts)
  - [Updates](#updates)
  - [Official Documentation](#official-documentation)
  - [Getting Started](#getting-started)
  - [Getting Involved](#getting-involved)
- [Samples](#samples)
- [Tutorials](#tutorials)
- [Stamp Implementations](#stamp-implementations)
- [Project Showcase](#project-showcase)
- [Contribute](#contribute)

## Featured

<!-- Inspired by the Awesome Firebase list

- Most recent blog post(s)
- Passports twitter account?
- A good introductory video on what passports is?

Firebase: https://github.com/jthegedus/awesome-firebase/blob/main/readme.md#featured-new-releases -->

- [Introducing Passport - Digital Identity as a Public Good](https://go.gitcoin.co/blog/intro-to-passport): Introducing Passports and Stamps
- [Gitcoin Passport <> Snapshot: Making DAO coordination more secure](https://go.gitcoin.co/blog/gitcoin-passport-snapshot-making-dao-coordination-more-secure): Protect your DAO from sybil voting attacks by using Passports with Snapshot and the Quadratic Voting strategy.
- [Defend Quadratic Funding Against Sybil Attacks](https://www.youtube.com/watch?v=v1Dm7FI2AdU): What are Sybil attacks and how does Passport help you defend your community against them.
- [Beginners Guide to Developing with Gitcoin Passports (video)](https://www.youtube.com/watch?v=MP4VnlcjDhk)
- [Overview of Gitcoin Passport with Kevin Olsen (video)](https://www.youtube.com/watch?v=UGYixVLwzrw)

<img src="./static/star-banner.png" alt="Logo">

([Back to the top](#top))

## Official Docs and Quickstarts

<!--
Inspired by the Awesome Stripe list and the Awesome Firebase list

Stripe: https://github.com/Derjyn/awesome-stripe/blob/master/README.md#core-resources
Firebase: https://github.com/jthegedus/awesome-firebase/blob/main/readme.md#official-docs--quickstarts

-->

- [Passport Documentation](https://docs.passport.gitcoin.co/)
- [Creating Your Passport](https://docs.passport.gitcoin.co/gitcoin-guides/creating-your-passport)
- [Passport SDK: Getting Started](https://docs.passport.gitcoin.co/gitcoin-passport-sdk/getting-started)

### Updates

Stay up to date with the latest information on Passports.

- [Official Website](https://go.gitcoin.co/passport?utm_source=awesome-passports&utm_medium=referral&utm_content=Passport)
- [Twitter Account](https://twitter.com/gitcoinpassport)
- [Official Blog](https://go.gitcoin.co/blog/tag/gitcoin-passport)

### Official Documentation

These are the best places to get started working with Passports.

- [Official Documentation](https://docs.passport.gitcoin.co/)
- [Creating Your Passport](https://docs.passport.gitcoin.co/gitcoin-guides/creating-your-passport)
- [Passport SDK: Getting Started](https://docs.passport.gitcoin.co/gitcoin-passport-sdk/getting-started)
- [Integrating Passports into your dApp](https://docs.passport.gitcoin.co/gitcoin-passport-sdk/integrating-passport-in-your-dapp)
- [Integrating a new Stamp](https://docs.passport.gitcoin.co/gitcoin-passport-sdk/integrating-a-new-stamp)
- [FAQ](https://docs.passport.gitcoin.co/gitcoin-guides/faq)

### Getting Started

Resources to help you get started building with Passports.

- [Introducing Passport - Digital Identity as a Public Good](https://go.gitcoin.co/blog/intro-to-passport)
- [Introducing Passport (YouTube)](https://www.youtube.com/watch?v=OyGj10pQfLY)
- [Beginners Guide To Developing With Gitcoin Passport](https://www.youtube.com/watch?v=MP4VnlcjDhk)

### Getting Involved

Interested in getting involved? Join us in [Discord](https://gitcoin.co/discord)
and look for the [🛠passport-builders
channel](https://discord.com/channels/562828676480237578/986222591096279040).

([Back to the top](#top))

## Samples

A list of samples for integrating Passports into an application.

### Scorer API

- [Score a Passport (Example)](https://github.com/gitcoinco/passport-scorer/tree/main/examples/example-score-a-passport): Simple, HTML and JavaScript example of how to score a passport using the [Scorer API](https://www.scorer.gitcoin.co/).
- [Nexth Starter Kit (Passport Integration)](https://github.com/wslyvh/nexth/blob/main/src/pages/examples/passport.tsx): A Next.js + Ethereum starter kit for quickly shipping web3 apps. General starter kit with a sample Passport integration.
- [Sybil Form](https://github.com/dabit3/sybil-form): A fully configurable sybil-resistant form built with Gitcoin Passport, Next.js, Arweave, and EXM.

### Passport SDK

- [Example Nextjs Passport SDK Verifier](https://github.com/gitcoinco/passport-sdk/tree/main/examples/example-nextjs-passport-sdk-verifier): Sample Next.js application demonstrating how to use the Passport Verifier.
- [Example Passport SDK Reader](https://github.com/gitcoinco/passport-sdk/tree/main/examples/example-passport-sdk-reader): A simple React application demonstrating how to work with the Passport SDK Stamp Reader.
- [Example Passport SDK Verifier](https://github.com/gitcoinco/passport-sdk/tree/main/examples/example-passport-sdk-verifier): A simple React application demonstrating how to work with the Passport SDK Stamp Verifier.
- [Scaffold Eth](https://github.com/farque65/Scaffold-eth-gitcoin-passport): Scaffold-ETH Passport starter and demo codebase for how to use Passport in a React application.
- [Passport Checker](https://github.com/Rask467/passport-checker): Community reference application showing what you can do with Passport and how to integrate it into a Next.js application.

([Back to the top](#top))

## Tutorials

Tutorials and guides for how to work with Passports.

- [Integrating Passport in your DApp](https://docs.passport.gitcoin.co/gitcoin-passport-sdk/integrating-passport-in-your-dapp)
- [Beginners Guide to Developing with Gitcoin Passports (video)](https://www.youtube.com/watch?v=MP4VnlcjDhk)

([Back to the top](#top))

## Stamp Implementations

Sample implementations of Stamp Providers. Use these as a reference for
implementing your own.

- [Google OAuth Stamp](https://github.com/gitcoinco/passport/pull/31)
- [ENS Stamp](https://github.com/gitcoinco/passport/pull/71)
- [Proof of Humanity Stamp](https://github.com/gitcoinco/passport/pull/75)
- [Twitter OAuth Stamp](https://github.com/gitcoinco/passport/pull/87)
- [POAP Stamp](https://github.com/gitcoinco/passport/pull/93)
- [Facebook Stamp](https://github.com/gitcoinco/passport/pull/94)
- [BrightId Stamp](https://github.com/gitcoinco/passport/pull/126)

([Back to the top](#top))

## Project Showcase

- EthStaker Discord Bot: [Website](https://github.com/remyroy/ethstaker-discord-bot) | [Repo](https://github.com/remyroy/ethstaker-discord-bot)
- Identity Staking Application: [Website](https://staking.passport.gitcoin.co/) | [Repo](https://github.com/moonshotcollective/id-staking)
- Passport Lookup Tool: [Website](https://passport-lookup-tool.vercel.app/) | [Repo](https://github.com/moonshotcollective/id-staking-passport-api/tree/reader-api)
- Scaffold-ETH Gitcoin Passport: [Website](https://lucianhymer.github.io/Scaffold-eth-gitcoin-passport/) | [Repo](https://github.com/farque65/Scaffold-eth-gitcoin-passport)

([Back to the top](#top))

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

([Back to the top](#top))
