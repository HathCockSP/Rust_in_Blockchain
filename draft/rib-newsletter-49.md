---
title: "RiB Newsletter #49"
description: "June 2023"
date: 2023-07-05
categories:
  - "newsletters"
summary: "_TODO_"
---

Welcome to the #49 edition of Rust in Blockchain, the monthly
newsletter about Rust, distributed systems, cryptography, and other
industry topics.
[Previous: #48](/newsletters/rib-newsletter-48/).

&nbsp;

## Thanks

Thanks to contributors:
[Julian Martinez],
[Brian Anderson] and [Aimee Zhu].
Thank you for your help!

RiB needs help to keep up with Rust blockchain projects.
If you follow a particular project, or otherwise find information
that is beneficial to the Rust & blockchain community,
please contribute to the next issue
by submitting a PR to the [next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

[Julian Martinez]: https://github.com/Julian-dev28
[Brian Anderson]: https://github.com/brson
[Aimee Zhu]: https://github.com/Aimeedeer

&nbsp;


## Project Spotlight

Each month we like to shine a light on a notable Rust blockchain project. This month that project is…

[Locutus](https://github.com/freenet/locutus).

Locutus is a project created by Freenet.
It is a platform for creating decentralized applications
on top of a decentralized key-value store.
It is not blockchain based.


&nbsp;


## Interesting Things

#### Papers

- [SoK: Data Sovereignty](https://eprint.iacr.org/2023/967)
- [Concurrent Asynchronous Byzantine Agreement in Expected-Constant Rounds, Revisited](https://eprint.iacr.org/2023/1003)
- [EDEN - a practical, SNARK-friendly combinator VM and ISA](https://eprint.iacr.org/2023/1021)
- [VSS from Distributed ZK Proofs and Applications](https://eprint.iacr.org/2023/992)
- [Automated Analysis of Halo2 Circuits](https://eprint.iacr.org/2023/1051)

#### Projects

- [Orion](https://github.com/gizatechxyz/orion).
  ONNX Runtime in Cairo 1.0 for verifiable ML inference using STARK.
  Blog post: [Introducing Orion: A verifiable, extensible framework to superpower web3 & AI](https://mirror.xyz/gizatech.eth/EtbskbyzVMIhGhgX_xl1yjTOMKW66jjujIr_HcfO2YQ)
- [Locutus](https://github.com/freenet/locutus).
  A software platform for writing create decentralized applications.

&nbsp;

## Most Active in June

[Solana](https://github.com/solana-labs/solana):
404 merged PRs,
83 closed issues,
31 open issues

[Reth](https://github.com/paradigmxyz/reth):
366 merged PRs,
138 closed issues,
59 open issues

[Sui](https://github.com/MystenLabs):
359 merged PRs,
41 closed issues,
16 open issues

[Parity](https://github.com/paritytech):
348 merged PRs,
133 closed issues,
129 open issues

[Aptos](https://github.com/aptos-labs):
296 merged PRs,
63 closed issues,
46 open issues


&nbsp;

## Project Updates

<!-- NB: This list needs to be kept in sync with rib-bible.md / rib-config.toml -->

#### [Aleo](https://github.com/AleoHQ)

154 merged PRs ([1][aleo-merged-prs-1], [2][aleo-merged-prs-2], [3][aleo-merged-prs-3], [4][aleo-merged-prs-4], [5][aleo-merged-prs-5]),
74 closed issues ([1][aleo-closed_issues-1], [2][aleo-closed_issues-2], [3][aleo-closed_issues-3], [4][aleo-closed_issues-4], [5][aleo-closed_issues-5]),
25 open issues ([1][aleo-open_issues-1], [2][aleo-open_issues-2], [3][aleo-open_issues-3], [4][aleo-open_issues-4])

[aleo-merged-prs-1]: https://github.com/AleoHQ/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aleo-merged-prs-2]: https://github.com/AleoHQ/leo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aleo-merged-prs-3]: https://github.com/AleoHQ/snarkOS/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aleo-merged-prs-4]: https://github.com/AleoHQ/snarkVM/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aleo-merged-prs-5]: https://github.com/AleoHQ/welcome/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aleo-closed_issues-1]: https://github.com/AleoHQ/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aleo-closed_issues-2]: https://github.com/AleoHQ/leo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aleo-closed_issues-3]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aleo-closed_issues-4]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aleo-closed_issues-5]: https://github.com/AleoHQ/welcome/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aleo-open_issues-1]: https://github.com/AleoHQ/sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aleo-open_issues-2]: https://github.com/AleoHQ/snarkOS/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aleo-open_issues-3]: https://github.com/AleoHQ/snarkVM/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aleo-open_issues-4]: https://github.com/AleoHQ/welcome/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Launching Aleo Deploy Incentives](https://www.aleo.org/post/launching-aleo-deploy-incentives)

#### [Anoma](https://github.com/anoma)

100 merged PRs ([1][anoma-merged-prs-1], [2][anoma-merged-prs-2], [3][anoma-merged-prs-3]),
39 closed issues ([1][anoma-closed_issues-1], [2][anoma-closed_issues-2], [3][anoma-closed_issues-3]),
25 open issues ([1][anoma-open_issues-1], [2][anoma-open_issues-2], [3][anoma-open_issues-3])

[anoma-merged-prs-1]: https://github.com/anoma/namada/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[anoma-merged-prs-2]: https://github.com/anoma/vamp-ir/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[anoma-merged-prs-3]: https://github.com/anoma/taiga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[anoma-closed_issues-1]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[anoma-closed_issues-2]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[anoma-closed_issues-3]: https://github.com/anoma/taiga/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[anoma-open_issues-1]: https://github.com/anoma/masp/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[anoma-open_issues-2]: https://github.com/anoma/namada/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[anoma-open_issues-3]: https://github.com/anoma/vamp-ir/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Aptos](https://github.com/aptos-labs)

296 merged PRs ([1][aptos-merged-prs-1]),
63 closed issues ([1][aptos-closed_issues-1]),
46 open issues ([1][aptos-open_issues-1])

[aptos-merged-prs-1]: https://github.com/aptos-labs/aptos-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aptos-closed_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aptos-open_issues-1]: https://github.com/aptos-labs/aptos-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Casper](https://github.com/casper-network)

56 merged PRs ([1][casper-merged-prs-1], [2][casper-merged-prs-2]),
75 closed issues ([1][casper-closed_issues-1], [2][casper-closed_issues-2]),
34 open issues ([1][casper-open_issues-1], [2][casper-open_issues-2])

[casper-merged-prs-1]: https://github.com/casper-network/casper-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[casper-merged-prs-2]: https://github.com/casper-network/docs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[casper-closed_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[casper-closed_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[casper-open_issues-1]: https://github.com/casper-network/casper-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[casper-open_issues-2]: https://github.com/casper-network/docs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Concordium](https://github.com/Concordium)

61 merged PRs ([1][concordium-merged-prs-1], [2][concordium-merged-prs-2], [3][concordium-merged-prs-3], [4][concordium-merged-prs-4], [5][concordium-merged-prs-5], [6][concordium-merged-prs-6], [7][concordium-merged-prs-7]),
59 closed issues ([1][concordium-closed_issues-1], [2][concordium-closed_issues-2], [3][concordium-closed_issues-3], [4][concordium-closed_issues-4], [5][concordium-closed_issues-5]),
28 open issues ([1][concordium-open_issues-1], [2][concordium-open_issues-2], [3][concordium-open_issues-3], [4][concordium-open_issues-4], [5][concordium-open_issues-5])

[concordium-merged-prs-1]: https://github.com/Concordium/concordium-rust-smart-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-merged-prs-2]: https://github.com/Concordium/concordium-contracts-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-merged-prs-3]: https://github.com/Concordium/concordium-rust-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-merged-prs-4]: https://github.com/Concordium/concordium-base/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-merged-prs-5]: https://github.com/Concordium/concordium-transaction-logger/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-merged-prs-6]: https://github.com/Concordium/concordium-euro2ccd-service/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-merged-prs-7]: https://github.com/Concordium/concordium-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-closed_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-closed_issues-2]: https://github.com/Concordium/concordium-rust-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-closed_issues-3]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-closed_issues-4]: https://github.com/Concordium/concordium-transaction-logger/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-closed_issues-5]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-open_issues-1]: https://github.com/Concordium/concordium-rust-smart-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-open_issues-2]: https://github.com/Concordium/concordium-contracts-common/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-open_issues-3]: https://github.com/Concordium/concordium-base/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-open_issues-4]: https://github.com/Concordium/concordium-transaction-logger/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[concordium-open_issues-5]: https://github.com/Concordium/concordium-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Conflux](https://github.com/Conflux-Chain)

12 merged PRs ([1][conflux-merged-prs-1]),
3 closed issues ([1][conflux-closed_issues-1]),
1 open issues ([1][conflux-open_issues-1])

[conflux-merged-prs-1]: https://github.com/Conflux-Chain/conflux-rust/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[conflux-closed_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[conflux-open_issues-1]: https://github.com/Conflux-Chain/conflux-rust/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [DarkFi](https://dark.fi)

6 merged PRs ([1][darkfi-merged-prs-1]),
1 closed issues ([1][darkfi-closed_issues-1]),
0 open issues

[darkfi-merged-prs-1]: https://github.com/darkrenaissance/darkfi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[darkfi-closed_issues-1]: https://github.com/darkrenaissance/darkfi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Dfinity](https://github.com/dfinity)

68 merged PRs ([1][dfinity-merged-prs-1], [2][dfinity-merged-prs-2], [3][dfinity-merged-prs-3], [4][dfinity-merged-prs-4], [5][dfinity-merged-prs-5]),
9 closed issues ([1][dfinity-closed_issues-1], [2][dfinity-closed_issues-2], [3][dfinity-closed_issues-3], [4][dfinity-closed_issues-4]),
4 open issues ([1][dfinity-open_issues-1], [2][dfinity-open_issues-2], [3][dfinity-open_issues-3])

[dfinity-merged-prs-1]: https://github.com/dfinity/sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dfinity-merged-prs-2]: https://github.com/dfinity/agent-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dfinity-merged-prs-3]: https://github.com/dfinity/cdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dfinity-merged-prs-4]: https://github.com/dfinity/candid/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dfinity-merged-prs-5]: https://github.com/dfinity/quill/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dfinity-closed_issues-1]: https://github.com/dfinity/sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dfinity-closed_issues-2]: https://github.com/dfinity/agent-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dfinity-closed_issues-3]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dfinity-closed_issues-4]: https://github.com/dfinity/vessel/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dfinity-open_issues-1]: https://github.com/dfinity/cdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dfinity-open_issues-2]: https://github.com/dfinity/candid/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dfinity-open_issues-3]: https://github.com/dfinity/vessel/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Announcing the Motoko Dev Server: live-reloading for Web3 dapps](https://medium.com/dfinity/announcing-the-motoko-dev-server-live-reloading-for-web3-dapps-20363088afb4)
- [A Glimpse into Motoko and AgorApp embeddable IDE](https://medium.com/dfinity/a-glimpse-into-motoko-and-agorapp-embeddable-ide-dc872826cd82)
- [Gaming and Metaverse — announcing the next edition of ICP.Lab for builders.](https://medium.com/dfinity/gaming-and-metaverse-announcing-the-next-edition-of-icp-lab-for-builders-8493d182f3d4)

#### [Dusk Network](https://github.com/dusk-network)

15 merged PRs ([1][dusk_network-merged-prs-1], [2][dusk_network-merged-prs-2], [3][dusk_network-merged-prs-3]),
10 closed issues ([1][dusk_network-closed_issues-1], [2][dusk_network-closed_issues-2]),
15 open issues ([1][dusk_network-open_issues-1], [2][dusk_network-open_issues-2], [3][dusk_network-open_issues-3])

[dusk_network-merged-prs-1]: https://github.com/dusk-network/plonk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dusk_network-merged-prs-2]: https://github.com/dusk-network/rusk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dusk_network-merged-prs-3]: https://github.com/dusk-network/wallet-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dusk_network-closed_issues-1]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dusk_network-closed_issues-2]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dusk_network-open_issues-1]: https://github.com/dusk-network/plonk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dusk_network-open_issues-2]: https://github.com/dusk-network/rusk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[dusk_network-open_issues-3]: https://github.com/dusk-network/wallet-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Testnet DayLight | Release Cycle Update #22](https://dusk.network/news/release-cycle-update-22)
- [The Three Pillars of Dusk](https://dusk.network/news/the-3-pillars-of-dusk)

#### [Espresso Systems](https://github.com/EspressoSystems)

50 merged PRs ([1][espresso_systems-merged-prs-1], [2][espresso_systems-merged-prs-2]),
33 closed issues ([1][espresso_systems-closed_issues-1], [2][espresso_systems-closed_issues-2]),
21 open issues ([1][espresso_systems-open_issues-1], [2][espresso_systems-open_issues-2])

[espresso_systems-merged-prs-1]: https://github.com/EspressoSystems/jellyfish/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[espresso_systems-merged-prs-2]: https://github.com/EspressoSystems/HotShot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[espresso_systems-closed_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[espresso_systems-closed_issues-2]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[espresso_systems-open_issues-1]: https://github.com/EspressoSystems/jellyfish/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[espresso_systems-open_issues-2]: https://github.com/EspressoSystems/HotShot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Filecoin](https://github.com/filecoin-project)

134 merged PRs ([1][filecoin-merged-prs-1], [2][filecoin-merged-prs-2], [3][filecoin-merged-prs-3], [4][filecoin-merged-prs-4], [5][filecoin-merged-prs-5], [6][filecoin-merged-prs-6], [7][filecoin-merged-prs-7]),
58 closed issues ([1][filecoin-closed_issues-1], [2][filecoin-closed_issues-2], [3][filecoin-closed_issues-3], [4][filecoin-closed_issues-4]),
66 open issues ([1][filecoin-open_issues-1], [2][filecoin-open_issues-2], [3][filecoin-open_issues-3], [4][filecoin-open_issues-4])

[filecoin-merged-prs-1]: https://github.com/filecoin-project/builtin-actors/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[filecoin-merged-prs-2]: https://github.com/filecoin-project/ec-gpu/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[filecoin-merged-prs-3]: https://github.com/filecoin-project/filecoin-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[filecoin-merged-prs-4]: https://github.com/lurk-lab/neptune/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[filecoin-merged-prs-5]: https://github.com/filecoin-project/ref-fvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[filecoin-merged-prs-6]: https://github.com/filecoin-project/rust-fil-proofs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[filecoin-merged-prs-7]: https://github.com/ChainSafe/forest/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[filecoin-closed_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[filecoin-closed_issues-2]: https://github.com/lurk-lab/neptune/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[filecoin-closed_issues-3]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[filecoin-closed_issues-4]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[filecoin-open_issues-1]: https://github.com/filecoin-project/builtin-actors/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[filecoin-open_issues-2]: https://github.com/filecoin-project/ref-fvm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[filecoin-open_issues-3]: https://github.com/filecoin-project/rust-fil-proofs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[filecoin-open_issues-4]: https://github.com/ChainSafe/forest/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Filecoin Virtual Machine (FVM) Builder Cohort Launches to Mainnet](https://filecoin.io/blog/posts/filecoin-virtual-machine-fvm-builder-cohort-launches-to-mainnet/)
- [100 Days of FVM](https://filecoin.io/blog/posts/100-days-of-fvm/)

#### [Findora](https://github.com/FindoraNetwork)

45 merged PRs ([1][findora-merged-prs-1], [2][findora-merged-prs-2], [3][findora-merged-prs-3], [4][findora-merged-prs-4]),
0 closed issues,
0 open issues

[findora-merged-prs-1]: https://github.com/FindoraNetwork/platform/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[findora-merged-prs-2]: https://github.com/FindoraNetwork/findora-scanner/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[findora-merged-prs-3]: https://github.com/FindoraNetwork/storage/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[findora-merged-prs-4]: https://github.com/FindoraNetwork/noah/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Fluence](https://github.com/fluencelabs)

69 merged PRs ([1][fluence-merged-prs-1], [2][fluence-merged-prs-2], [3][fluence-merged-prs-3], [4][fluence-merged-prs-4], [5][fluence-merged-prs-5], [6][fluence-merged-prs-6], [7][fluence-merged-prs-7]),
0 closed issues,
0 open issues

[fluence-merged-prs-1]: https://github.com/fluencelabs/marine/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fluence-merged-prs-2]: https://github.com/fluencelabs/aquavm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fluence-merged-prs-3]: https://github.com/fluencelabs/examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fluence-merged-prs-4]: https://github.com/fluencelabs/registry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fluence-merged-prs-5]: https://github.com/fluencelabs/trust-graph/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fluence-merged-prs-6]: https://github.com/fluencelabs/aqua-ipfs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fluence-merged-prs-7]: https://github.com/fluencelabs/nox/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Fuel](https://github.com/FuelLabs)

158 merged PRs ([1][fuel-merged-prs-1], [2][fuel-merged-prs-2], [3][fuel-merged-prs-3], [4][fuel-merged-prs-4], [5][fuel-merged-prs-5], [6][fuel-merged-prs-6], [7][fuel-merged-prs-7]),
101 closed issues ([1][fuel-closed_issues-1], [2][fuel-closed_issues-2], [3][fuel-closed_issues-3], [4][fuel-closed_issues-4], [5][fuel-closed_issues-5]),
67 open issues ([1][fuel-open_issues-1], [2][fuel-open_issues-2], [3][fuel-open_issues-3], [4][fuel-open_issues-4], [5][fuel-open_issues-5], [6][fuel-open_issues-6])

[fuel-merged-prs-1]: https://github.com/FuelLabs/faucet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-merged-prs-2]: https://github.com/FuelLabs/fuel-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-merged-prs-3]: https://github.com/FuelLabs/fuel-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-merged-prs-4]: https://github.com/FuelLabs/fuel-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-merged-prs-5]: https://github.com/FuelLabs/fuels-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-merged-prs-6]: https://github.com/FuelLabs/fuelup/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-merged-prs-7]: https://github.com/FuelLabs/sway/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-closed_issues-1]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-closed_issues-2]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-closed_issues-3]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-closed_issues-4]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-closed_issues-5]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-open_issues-1]: https://github.com/FuelLabs/fuel-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-open_issues-2]: https://github.com/FuelLabs/fuel-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-open_issues-3]: https://github.com/FuelLabs/fuel-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-open_issues-4]: https://github.com/FuelLabs/fuels-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-open_issues-5]: https://github.com/FuelLabs/fuelup/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fuel-open_issues-6]: https://github.com/FuelLabs/sway/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Sway Summer Online Hackathon](https://fuel-labs.ghost.io/sway-summer-online-hackathon/)
- [Introducing Fuel’s New Grants Program: Sparking Further Innovation in the Modular Ecosystem](https://fuel-labs.ghost.io/introducing-fuels-new-grants-program/)

#### [Golem](https://github.com/golemfactory)

19 merged PRs ([1][golem-merged-prs-1], [2][golem-merged-prs-2], [3][golem-merged-prs-3]),
22 closed issues ([1][golem-closed_issues-1], [2][golem-closed_issues-2]),
32 open issues ([1][golem-open_issues-1], [2][golem-open_issues-2], [3][golem-open_issues-3], [4][golem-open_issues-4])

[golem-merged-prs-1]: https://github.com/golemfactory/yagna/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[golem-merged-prs-2]: https://github.com/golemfactory/ya-relay/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[golem-merged-prs-3]: https://github.com/golemfactory/ya-runtime-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[golem-closed_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[golem-closed_issues-2]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[golem-open_issues-1]: https://github.com/golemfactory/yagna/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[golem-open_issues-2]: https://github.com/golemfactory/ya-client/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[golem-open_issues-3]: https://github.com/golemfactory/ya-relay/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[golem-open_issues-4]: https://github.com/golemfactory/ya-runtime-vm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Yagna 0.12.2 Patch Release: Restoring Functionality and Addressing Rinkeby Shutdown](https://blog.golemproject.net/yagna-0-12-2-patch-release/)

#### [Grin](https://github.com/mimblewimble/grin)

7 merged PRs ([1][grin-merged-prs-1]),
1 closed issues ([1][grin-closed_issues-1]),
3 open issues ([1][grin-open_issues-1])

[grin-merged-prs-1]: https://github.com/mimblewimble/grin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[grin-closed_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[grin-open_issues-1]: https://github.com/mimblewimble/grin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Helium](https://github.com/helium)

8 merged PRs ([1][helium-merged-prs-1], [2][helium-merged-prs-2], [3][helium-merged-prs-3]),
1 closed issues ([1][helium-closed_issues-1]),
0 open issues

[helium-merged-prs-1]: https://github.com/helium/gateway-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[helium-merged-prs-2]: https://github.com/helium/semtech-udp/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[helium-merged-prs-3]: https://github.com/helium/helium-crypto-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[helium-closed_issues-1]: https://github.com/helium/gateway-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Got SOL? Helium Transactions on Solana Explained!](https://blog.helium.com/got-sol-helium-transactions-on-solana-explained-e254827e929f)

#### [Holochain](https://github.com/holochain/)

74 merged PRs ([1][holochain-merged-prs-1], [2][holochain-merged-prs-2]),
3 closed issues ([1][holochain-closed_issues-1]),
4 open issues ([1][holochain-open_issues-1], [2][holochain-open_issues-2])

[holochain-merged-prs-1]: https://github.com/holochain/holochain/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[holochain-merged-prs-2]: https://github.com/holochain/launcher/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[holochain-closed_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[holochain-open_issues-1]: https://github.com/holochain/holochain/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[holochain-open_issues-2]: https://github.com/holochain/launcher/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Holochain 0.1.5 Released](https://blog.holochain.org/holochain-0-1-5-released/)

#### [IOTA](https://github.com/iotaledger)

32 merged PRs ([1][iota-merged-prs-1], [2][iota-merged-prs-2], [3][iota-merged-prs-3], [4][iota-merged-prs-4], [5][iota-merged-prs-5]),
1 closed issues ([1][iota-closed_issues-1]),
0 open issues

[iota-merged-prs-1]: https://github.com/iotaledger/wallet.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[iota-merged-prs-2]: https://github.com/iotaledger/iota.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[iota-merged-prs-3]: https://github.com/iotaledger/identity.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[iota-merged-prs-4]: https://github.com/iotaledger/stronghold.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[iota-merged-prs-5]: https://github.com/iotaledger/chronicle.rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[iota-closed_issues-1]: https://github.com/iotaledger/identity.rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Q2 2023 Progress Report](https://blog.iota.org/q2-2023-progress-report/)

#### [Maidsafe](https://github.com/maidsafe)

110 merged PRs ([1][maidsafe-merged-prs-1], [2][maidsafe-merged-prs-2]),
14 closed issues ([1][maidsafe-closed_issues-1]),
17 open issues ([1][maidsafe-open_issues-1])

[maidsafe-merged-prs-1]: https://github.com/maidsafe/sn_dbc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[maidsafe-merged-prs-2]: https://github.com/maidsafe/safe_network/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[maidsafe-closed_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[maidsafe-open_issues-1]: https://github.com/maidsafe/safe_network/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [MobileCoin](https://github.com/mobilecoinfoundation)

22 merged PRs ([1][mobilecoin-merged-prs-1]),
0 closed issues,
4 open issues ([1][mobilecoin-open_issues-1])

[mobilecoin-merged-prs-1]: https://github.com/mobilecoinfoundation/mobilecoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[mobilecoin-open_issues-1]: https://github.com/mobilecoinfoundation/mobilecoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [MultiversX](https://github.com/multiversx)

46 merged PRs ([1][multiversx-merged-prs-1], [2][multiversx-merged-prs-2], [3][multiversx-merged-prs-3]),
0 closed issues,
1 open issues ([1][multiversx-open_issues-1])

[multiversx-merged-prs-1]: https://github.com/multiversx/mx-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[multiversx-merged-prs-2]: https://github.com/multiversx/mx-exchange-sc/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[multiversx-merged-prs-3]: https://github.com/multiversx/mx-bridge-eth-sc-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[multiversx-open_issues-1]: https://github.com/multiversx/mx-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [NEAR](https://github.com/nearprotocol/nearcore)

157 merged PRs ([1][near-merged-prs-1], [2][near-merged-prs-2], [3][near-merged-prs-3], [4][near-merged-prs-4], [5][near-merged-prs-5], [6][near-merged-prs-6], [7][near-merged-prs-7], [8][near-merged-prs-8], [9][near-merged-prs-9], [10][near-merged-prs-10]),
58 closed issues ([1][near-closed_issues-1], [2][near-closed_issues-2], [3][near-closed_issues-3], [4][near-closed_issues-4], [5][near-closed_issues-5], [6][near-closed_issues-6], [7][near-closed_issues-7], [8][near-closed_issues-8]),
40 open issues ([1][near-open_issues-1], [2][near-open_issues-2], [3][near-open_issues-3], [4][near-open_issues-4], [5][near-open_issues-5], [6][near-open_issues-6], [7][near-open_issues-7])

[near-merged-prs-1]: https://github.com/near/workspaces-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-merged-prs-2]: https://github.com/near/nearcore/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-merged-prs-3]: https://github.com/near/near-cli-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-merged-prs-4]: https://github.com/near/near-sdk-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-merged-prs-5]: https://github.com/near/near-jsonrpc-client-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-merged-prs-6]: https://github.com/near/core-contracts/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-merged-prs-7]: https://github.com/near/near-lake-framework-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-merged-prs-8]: https://github.com/near/near-lake-indexer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-merged-prs-9]: https://github.com/near/borsh-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-merged-prs-10]: https://github.com/near/near-indexer-for-explorer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-closed_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-closed_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-closed_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-closed_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-closed_issues-5]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-closed_issues-6]: https://github.com/near/near-lake-framework-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-closed_issues-7]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-closed_issues-8]: https://github.com/near/wasmer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-open_issues-1]: https://github.com/near/workspaces-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-open_issues-2]: https://github.com/near/nearcore/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-open_issues-3]: https://github.com/near/near-cli-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-open_issues-4]: https://github.com/near/near-sdk-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-open_issues-5]: https://github.com/near/core-contracts/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-open_issues-6]: https://github.com/near/near-lake-indexer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[near-open_issues-7]: https://github.com/near/borsh-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Blockchain Scaling Approaches: NEAR Sharding vs. Layer 2s](https://pages.near.org/blog/blockchain-scaling-approaches-near-sharding-vs-layer-2s/)
- [Encode x NEAR Horizon Bootcamp: Your Mission to Master Web3 Rust Contracts](https://pages.near.org/blog/encode-x-near-horizon-bootcamp-your-mission-to-master-web3-rust-contracts/)
- [The Fast Rainbow Bridge for NEAR to Ethereum Token Transfers is Live!](https://medium.com/nearprotocol/the-fast-rainbow-bridge-for-near-to-ethereum-token-transfers-is-live-7ccaea4eb35e)

#### [Nervos](https://github.com/nervosnetwork)

47 merged PRs ([1][nervos-merged-prs-1], [2][nervos-merged-prs-2], [3][nervos-merged-prs-3], [4][nervos-merged-prs-4], [5][nervos-merged-prs-5]),
12 closed issues ([1][nervos-closed_issues-1], [2][nervos-closed_issues-2], [3][nervos-closed_issues-3], [4][nervos-closed_issues-4]),
11 open issues ([1][nervos-open_issues-1], [2][nervos-open_issues-2], [3][nervos-open_issues-3])

[nervos-merged-prs-1]: https://github.com/nervosnetwork/ckb/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[nervos-merged-prs-2]: https://github.com/nervosnetwork/ckb-vm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[nervos-merged-prs-3]: https://github.com/nervosnetwork/ckb-cli/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[nervos-merged-prs-4]: https://github.com/nervosnetwork/capsule/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[nervos-merged-prs-5]: https://github.com/godwokenrises/godwoken/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[nervos-closed_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[nervos-closed_issues-2]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[nervos-closed_issues-3]: https://github.com/nervosnetwork/capsule/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[nervos-closed_issues-4]: https://github.com/godwokenrises/godwoken/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[nervos-open_issues-1]: https://github.com/nervosnetwork/ckb/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[nervos-open_issues-2]: https://github.com/nervosnetwork/ckb-cli/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[nervos-open_issues-3]: https://github.com/godwokenrises/godwoken/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Oasis](https://github.com/oasisprotocol)

1 merged PRs ([1][oasis-merged-prs-1]),
0 closed issues,
1 open issues ([1][oasis-open_issues-1])

[oasis-merged-prs-1]: https://github.com/oasisprotocol/oasis-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[oasis-open_issues-1]: https://github.com/oasisprotocol/oasis-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Oasis May 2023 Engineering Update](https://oasisprotocol.org/blog/may-2023-engineering-update)

#### [Parity](https://github.com/paritytech)

348 merged PRs ([1][parity-merged-prs-1], [2][parity-merged-prs-2], [3][parity-merged-prs-3], [4][parity-merged-prs-4], [5][parity-merged-prs-5], [6][parity-merged-prs-6], [7][parity-merged-prs-7], [8][parity-merged-prs-8], [9][parity-merged-prs-9], [10][parity-merged-prs-10], [11][parity-merged-prs-11], [12][parity-merged-prs-12], [13][parity-merged-prs-13], [14][parity-merged-prs-14]),
133 closed issues ([1][parity-closed_issues-1], [2][parity-closed_issues-2], [3][parity-closed_issues-3], [4][parity-closed_issues-4], [5][parity-closed_issues-5], [6][parity-closed_issues-6], [7][parity-closed_issues-7], [8][parity-closed_issues-8], [9][parity-closed_issues-9], [10][parity-closed_issues-10], [11][parity-closed_issues-11], [12][parity-closed_issues-12]),
129 open issues ([1][parity-open_issues-1], [2][parity-open_issues-2], [3][parity-open_issues-3], [4][parity-open_issues-4], [5][parity-open_issues-5], [6][parity-open_issues-6], [7][parity-open_issues-7], [8][parity-open_issues-8], [9][parity-open_issues-9], [10][parity-open_issues-10], [11][parity-open_issues-11], [12][parity-open_issues-12], [13][parity-open_issues-13], [14][parity-open_issues-14])

[parity-merged-prs-1]: https://github.com/paritytech/substrate/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-merged-prs-2]: https://github.com/paritytech/polkadot/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-merged-prs-3]: https://github.com/paritytech/cumulus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-merged-prs-4]: https://github.com/paritytech/parity-signer/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-merged-prs-5]: https://github.com/paritytech/ink/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-merged-prs-6]: https://github.com/paritytech/parity-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-merged-prs-7]: https://github.com/paritytech/subxt/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-merged-prs-8]: https://github.com/paritytech/jsonrpsee/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-merged-prs-9]: https://github.com/paritytech/frontier/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-merged-prs-10]: https://github.com/paritytech/cargo-contract/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-merged-prs-11]: https://github.com/paritytech/substrate-contracts-node/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-merged-prs-12]: https://github.com/paritytech/ink-playground/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-merged-prs-13]: https://github.com/paritytech/metadata-portal/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-merged-prs-14]: https://github.com/paritytech/parity-bridges-common/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-closed_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-closed_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-closed_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-closed_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-closed_issues-5]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-closed_issues-6]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-closed_issues-7]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-closed_issues-8]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-closed_issues-9]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-closed_issues-10]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-closed_issues-11]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-closed_issues-12]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-open_issues-1]: https://github.com/paritytech/substrate/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-open_issues-2]: https://github.com/paritytech/polkadot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-open_issues-3]: https://github.com/paritytech/cumulus/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-open_issues-4]: https://github.com/paritytech/parity-signer/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-open_issues-5]: https://github.com/paritytech/smoldot/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-open_issues-6]: https://github.com/paritytech/ink/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-open_issues-7]: https://github.com/paritytech/parity-common/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-open_issues-8]: https://github.com/paritytech/subxt/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-open_issues-9]: https://github.com/paritytech/jsonrpsee/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-open_issues-10]: https://github.com/paritytech/frontier/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-open_issues-11]: https://github.com/paritytech/cargo-contract/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-open_issues-12]: https://github.com/paritytech/substrate-contracts-node/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-open_issues-13]: https://github.com/paritytech/ink-playground/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[parity-open_issues-14]: https://github.com/paritytech/parity-bridges-common/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [XCM v3: Breaking New Ground for Web3 Interoperability](https://medium.com/polkadot-network/xcm-v3-breaking-new-ground-for-web3-interoperability-5fe6e7ebfaa8)

#### [Radix](https://github.com/radixdlt)

119 merged PRs ([1][radix-merged-prs-1]),
0 closed issues,
2 open issues ([1][radix-open_issues-1])

[radix-merged-prs-1]: https://github.com/radixdlt/radixdlt-scrypto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[radix-open_issues-1]: https://github.com/radixdlt/radixdlt-scrypto/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Secret Network](https://github.com/enigmampc/SecretNetwork)

7 merged PRs ([1][secret_network-merged-prs-1], [2][secret_network-merged-prs-2]),
0 closed issues,
3 open issues ([1][secret_network-open_issues-1], [2][secret_network-open_issues-2])

[secret_network-merged-prs-1]: https://github.com/scrtlabs/SecretNetwork/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[secret_network-merged-prs-2]: https://github.com/scrtlabs/secret-toolkit/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[secret_network-open_issues-1]: https://github.com/scrtlabs/SecretNetwork/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[secret_network-open_issues-2]: https://github.com/scrtlabs/secret-toolkit/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Secret Feature: 1RPC](https://scrt.network/blog/secret-feature-1rpc)
- [Secret Network is now supported on Babylon Testnet](https://scrt.network/blog/babylon-chain-testnet)
- [Privacy-as-a-Service Showcase: BIDSHOP](https://scrt.network/blog/paas-showcase-bidshop)

#### [Solana](https://github.com/solana-labs/solana)

404 merged PRs ([1][solana-merged-prs-1], [2][solana-merged-prs-2], [3][solana-merged-prs-3]),
83 closed issues ([1][solana-closed_issues-1], [2][solana-closed_issues-2]),
31 open issues ([1][solana-open_issues-1], [2][solana-open_issues-2])

[solana-merged-prs-1]: https://github.com/solana-labs/solana/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[solana-merged-prs-2]: https://github.com/solana-labs/solana-program-library/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[solana-merged-prs-3]: https://github.com/solana-labs/solana-accountsdb-plugin-postgres/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[solana-closed_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[solana-closed_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[solana-open_issues-1]: https://github.com/solana-labs/solana/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[solana-open_issues-2]: https://github.com/solana-labs/solana-program-library/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Soroban](https://github.com/stellar)

145 merged PRs ([1][soroban-merged-prs-1], [2][soroban-merged-prs-2], [3][soroban-merged-prs-3], [4][soroban-merged-prs-4], [5][soroban-merged-prs-5]),
66 closed issues ([1][soroban-closed_issues-1], [2][soroban-closed_issues-2], [3][soroban-closed_issues-3], [4][soroban-closed_issues-4]),
49 open issues ([1][soroban-open_issues-1], [2][soroban-open_issues-2], [3][soroban-open_issues-3], [4][soroban-open_issues-4])

[soroban-merged-prs-1]: https://github.com/stellar/rs-soroban-sdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[soroban-merged-prs-2]: https://github.com/stellar/rs-soroban-env/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[soroban-merged-prs-3]: https://github.com/stellar/soroban-tools/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[soroban-merged-prs-4]: https://github.com/stellar/soroban-examples/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[soroban-merged-prs-5]: https://github.com/stellar/scaffold-soroban/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[soroban-closed_issues-1]: https://github.com/stellar/rs-soroban-sdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[soroban-closed_issues-2]: https://github.com/stellar/rs-soroban-env/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[soroban-closed_issues-3]: https://github.com/stellar/soroban-tools/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[soroban-closed_issues-4]: https://github.com/stellar/soroban-examples/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[soroban-open_issues-1]: https://github.com/stellar/rs-soroban-sdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[soroban-open_issues-2]: https://github.com/stellar/rs-soroban-env/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[soroban-open_issues-3]: https://github.com/stellar/soroban-tools/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[soroban-open_issues-4]: https://github.com/stellar/soroban-examples/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Soroban’s Technical Design Decisions & Learnings from Ethereum](https://www.stellar.org/developers-blog/sorobans-technical-design-decisions-learnings-from-ethereum)
- [Announcing the Soroban Security Bug Bounty](https://www.stellar.org/developers-blog/soroban-security-bug-bounty)

#### [Subspace Network](https://github.com/subspace)

70 merged PRs ([1][subspace_network-merged-prs-1]),
65 closed issues ([1][subspace_network-closed_issues-1]),
40 open issues ([1][subspace_network-open_issues-1])

[subspace_network-merged-prs-1]: https://github.com/subspace/subspace/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[subspace_network-closed_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[subspace_network-open_issues-1]: https://github.com/subspace/subspace/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Sui](https://github.com/MystenLabs)

359 merged PRs ([1][sui-merged-prs-1]),
41 closed issues ([1][sui-closed_issues-1]),
16 open issues ([1][sui-open_issues-1])

[sui-merged-prs-1]: https://github.com/MystenLabs/sui/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[sui-closed_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[sui-open_issues-1]: https://github.com/MystenLabs/sui/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Introducing Capy Trading Bot](https://tech.mystenlabs.com/introducing-capy-trading-bot/)

#### [Zcash](https://github.com/zcash)

108 merged PRs ([1][zcash-merged-prs-1], [2][zcash-merged-prs-2], [3][zcash-merged-prs-3], [4][zcash-merged-prs-4], [5][zcash-merged-prs-5]),
59 closed issues ([1][zcash-closed_issues-1], [2][zcash-closed_issues-2], [3][zcash-closed_issues-3], [4][zcash-closed_issues-4]),
32 open issues ([1][zcash-open_issues-1], [2][zcash-open_issues-2], [3][zcash-open_issues-3])

[zcash-merged-prs-1]: https://github.com/ZcashFoundation/zebra/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zcash-merged-prs-2]: https://github.com/zcash/halo2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zcash-merged-prs-3]: https://github.com/zcash/incrementalmerkletree/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zcash-merged-prs-4]: https://github.com/zcash/librustzcash/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zcash-merged-prs-5]: https://github.com/zcash/orchard/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zcash-closed_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zcash-closed_issues-2]: https://github.com/zcash/halo2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zcash-closed_issues-3]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zcash-closed_issues-4]: https://github.com/zcash/orchard/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zcash-open_issues-1]: https://github.com/ZcashFoundation/zebra/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zcash-open_issues-2]: https://github.com/zcash/librustzcash/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zcash-open_issues-3]: https://github.com/zcash/pasta_curves/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [zkSync Era](https://github.com/matter-labs)

5 merged PRs ([1][zksync_era-merged-prs-1], [2][zksync_era-merged-prs-2], [3][zksync_era-merged-prs-3]),
12 closed issues ([1][zksync_era-closed_issues-1], [2][zksync_era-closed_issues-2], [3][zksync_era-closed_issues-3], [4][zksync_era-closed_issues-4]),
21 open issues ([1][zksync_era-open_issues-1], [2][zksync_era-open_issues-2], [3][zksync_era-open_issues-3], [4][zksync_era-open_issues-4])

[zksync_era-merged-prs-1]: https://github.com/matter-labs/zksync-era/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zksync_era-merged-prs-2]: https://github.com/matter-labs/foundry-zksync/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zksync_era-merged-prs-3]: https://github.com/matter-labs/era-compiler-llvm-builder/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zksync_era-closed_issues-1]: https://github.com/matter-labs/zksync-era/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zksync_era-closed_issues-2]: https://github.com/matter-labs/foundry-zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zksync_era-closed_issues-3]: https://github.com/matter-labs/era-compiler-solidity/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zksync_era-closed_issues-4]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zksync_era-open_issues-1]: https://github.com/matter-labs/zksync-era/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zksync_era-open_issues-2]: https://github.com/matter-labs/foundry-zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zksync_era-open_issues-3]: https://github.com/matter-labs/era-compiler-solidity/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[zksync_era-open_issues-4]: https://github.com/matter-labs/zksync/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Introduction to Hyperchains](https://blog.matter-labs.io/introduction-to-hyperchains-fdb33414ead7)
- [Introducing the ZK Stack](https://blog.matter-labs.io/introducing-the-zk-stack-c24240c2532a)

&nbsp;

### Rust in Bitcoin

For discussion join the [Rust in Bitcoin Telegram group][ribtc].

[ribtc]: https://t.me/rust_in_bitcoin

#### [AluVM](https://github.com/AluVM)

19 merged PRs ([1][aluvm-merged-prs-1], [2][aluvm-merged-prs-2]),
8 closed issues ([1][aluvm-closed_issues-1]),
3 open issues ([1][aluvm-open_issues-1], [2][aluvm-open_issues-2])

[aluvm-merged-prs-1]: https://github.com/AluVM/rust-aluvm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aluvm-merged-prs-2]: https://github.com/AluVM/aluasm/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aluvm-closed_issues-1]: https://github.com/AluVM/rust-aluvm/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aluvm-open_issues-1]: https://github.com/AluVM/rust-aluvm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[aluvm-open_issues-2]: https://github.com/AluVM/aluasm/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [BDK](https://github.com/bitcoindevkit/bdk)

22 merged PRs ([1][bdk-merged-prs-1], [2][bdk-merged-prs-2], [3][bdk-merged-prs-3], [4][bdk-merged-prs-4]),
19 closed issues ([1][bdk-closed_issues-1], [2][bdk-closed_issues-2], [3][bdk-closed_issues-3], [4][bdk-closed_issues-4]),
18 open issues ([1][bdk-open_issues-1], [2][bdk-open_issues-2], [3][bdk-open_issues-3])

[bdk-merged-prs-1]: https://github.com/bitcoindevkit/bdk/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[bdk-merged-prs-2]: https://github.com/bitcoindevkit/bdk-ffi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[bdk-merged-prs-3]: https://github.com/bitcoindevkit/rust-hwi/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[bdk-merged-prs-4]: https://github.com/bitcoindevkit/rust-electrum-client/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[bdk-closed_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[bdk-closed_issues-2]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[bdk-closed_issues-3]: https://github.com/bitcoindevkit/rust-hwi/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[bdk-closed_issues-4]: https://github.com/bitcoindevkit/rust-electrum-client/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[bdk-open_issues-1]: https://github.com/bitcoindevkit/bdk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[bdk-open_issues-2]: https://github.com/bitcoindevkit/bdk-ffi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[bdk-open_issues-3]: https://github.com/bitcoindevkit/rust-hwi/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [BitMask](https://github.com/diba-io/bitmask-core)

16 merged PRs ([1][bitmask-merged-prs-1]),
4 closed issues ([1][bitmask-closed_issues-1]),
4 open issues ([1][bitmask-open_issues-1])

[bitmask-merged-prs-1]: https://github.com/diba-io/bitmask-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[bitmask-closed_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[bitmask-open_issues-1]: https://github.com/diba-io/bitmask-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Electrs](https://github.com/romanz/electrs)

8 merged PRs ([1][electrs-merged-prs-1]),
13 closed issues ([1][electrs-closed_issues-1]),
0 open issues

[electrs-merged-prs-1]: https://github.com/romanz/electrs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[electrs-closed_issues-1]: https://github.com/romanz/electrs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Fedimint](https://github.com/fedimint/fedimint)

45 merged PRs ([1][fedimint-merged-prs-1]),
18 closed issues ([1][fedimint-closed_issues-1]),
23 open issues ([1][fedimint-open_issues-1])

[fedimint-merged-prs-1]: https://github.com/fedimint/fedimint/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fedimint-closed_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[fedimint-open_issues-1]: https://github.com/fedimint/fedimint/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [LDK](https://github.com/lightningdevkit/rust-lightning)

31 merged PRs ([1][ldk-merged-prs-1], [2][ldk-merged-prs-2]),
12 closed issues ([1][ldk-closed_issues-1]),
16 open issues ([1][ldk-open_issues-1], [2][ldk-open_issues-2])

[ldk-merged-prs-1]: https://github.com/lightningdevkit/rust-lightning/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[ldk-merged-prs-2]: https://github.com/lightningdevkit/ldk-c-bindings/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[ldk-closed_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[ldk-open_issues-1]: https://github.com/lightningdevkit/rust-lightning/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[ldk-open_issues-2]: https://github.com/lightningdevkit/ldk-c-bindings/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [LNP/BP](https://github.com/LNP-BP)

4 merged PRs ([1][lnp/bp-merged-prs-1], [2][lnp/bp-merged-prs-2]),
1 closed issues ([1][lnp/bp-closed_issues-1]),
0 open issues

[lnp/bp-merged-prs-1]: https://github.com/LNP-BP/client_side_validation/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[lnp/bp-merged-prs-2]: https://github.com/BP-WG/bp-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[lnp/bp-closed_issues-1]: https://github.com/LNP-BP/client_side_validation/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Nakamoto](https://github.com/cloudhead/nakamoto)

2 merged PRs ([1][nakamoto-merged-prs-1]),
1 closed issues ([1][nakamoto-closed_issues-1]),
0 open issues

[nakamoto-merged-prs-1]: https://github.com/cloudhead/nakamoto/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[nakamoto-closed_issues-1]: https://github.com/cloudhead/nakamoto/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Nomic](https://github.com/nomic-io)

18 merged PRs ([1][nomic-merged-prs-1], [2][nomic-merged-prs-2]),
0 closed issues,
1 open issues ([1][nomic-open_issues-1])

[nomic-merged-prs-1]: https://github.com/nomic-io/nomic/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[nomic-merged-prs-2]: https://github.com/nomic-io/orga/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[nomic-open_issues-1]: https://github.com/nomic-io/merk/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [RGB](https://github.com/rgb-wg)

5 merged PRs ([1][rgb-merged-prs-1]),
2 closed issues ([1][rgb-closed_issues-1]),
2 open issues ([1][rgb-open_issues-1])

[rgb-merged-prs-1]: https://github.com/RGB-WG/rgb-core/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[rgb-closed_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[rgb-open_issues-1]: https://github.com/RGB-WG/rgb-core/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Rust Bitcoin](https://github.com/rust-bitcoin/rust-bitcoin)

21 merged PRs ([1][rust_bitcoin-merged-prs-1], [2][rust_bitcoin-merged-prs-2], [3][rust_bitcoin-merged-prs-3]),
12 closed issues ([1][rust_bitcoin-closed_issues-1], [2][rust_bitcoin-closed_issues-2], [3][rust_bitcoin-closed_issues-3]),
13 open issues ([1][rust_bitcoin-open_issues-1], [2][rust_bitcoin-open_issues-2], [3][rust_bitcoin-open_issues-3], [4][rust_bitcoin-open_issues-4])

[rust_bitcoin-merged-prs-1]: https://github.com/rust-bitcoin/rust-bitcoin/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[rust_bitcoin-merged-prs-2]: https://github.com/rust-bitcoin/rust-miniscript/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[rust_bitcoin-merged-prs-3]: https://github.com/rust-bitcoin/rust-wallet/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[rust_bitcoin-closed_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[rust_bitcoin-open_issues-1]: https://github.com/rust-bitcoin/rust-bitcoin/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[rust_bitcoin-open_issues-2]: https://github.com/rust-bitcoin/rust-secp256k1/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[rust_bitcoin-open_issues-3]: https://github.com/rust-bitcoin/rust-miniscript/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[rust_bitcoin-open_issues-4]: https://github.com/rust-bitcoin/rust-bitcoincore-rpc/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Rust Simplicity](https://github.com/BlockstreamResearch/rust-simplicity)

34 merged PRs ([1][rust_simplicity-merged-prs-1]),
17 closed issues ([1][rust_simplicity-closed_issues-1]),
10 open issues ([1][rust_simplicity-open_issues-1])

[rust_simplicity-merged-prs-1]: https://github.com/BlockstreamResearch/rust-simplicity/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[rust_simplicity-closed_issues-1]: https://github.com/BlockstreamResearch/rust-simplicity/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[rust_simplicity-open_issues-1]: https://github.com/BlockstreamResearch/rust-simplicity/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

If we've missed any other notable Rust Bitcoin projects or ecosystems, feel free to contribute!


&nbsp;

### Rust in Ethereum

#### [Ethers-rs](https://github.com/gakonst/ethers-rs)

19 merged PRs ([1][ethers-rs-merged-prs-1]),
11 closed issues ([1][ethers-rs-closed_issues-1]),
10 open issues ([1][ethers-rs-open_issues-1])

[ethers-rs-merged-prs-1]: https://github.com/gakonst/ethers-rs/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[ethers-rs-closed_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[ethers-rs-open_issues-1]: https://github.com/gakonst/ethers-rs/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Foundry](https://github.com/foundry-rs/foundry)

69 merged PRs ([1][foundry-merged-prs-1]),
124 closed issues ([1][foundry-closed_issues-1]),
34 open issues ([1][foundry-open_issues-1])

[foundry-merged-prs-1]: https://github.com/foundry-rs/foundry/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[foundry-closed_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[foundry-open_issues-1]: https://github.com/foundry-rs/foundry/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Lighthouse](https://github.com/sigp/lighthouse)

28 merged PRs ([1][lighthouse-merged-prs-1], [2][lighthouse-merged-prs-2]),
32 closed issues ([1][lighthouse-closed_issues-1], [2][lighthouse-closed_issues-2]),
30 open issues ([1][lighthouse-open_issues-1], [2][lighthouse-open_issues-2])

[lighthouse-merged-prs-1]: https://github.com/sigp/lighthouse/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[lighthouse-merged-prs-2]: https://github.com/sigp/discv5/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[lighthouse-closed_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[lighthouse-closed_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[lighthouse-open_issues-1]: https://github.com/sigp/lighthouse/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot
[lighthouse-open_issues-2]: https://github.com/sigp/discv5/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Mir Protocol](https://github.com/mir-protocol)

35 merged PRs ([1][mir_protocol-merged-prs-1]),
1 closed issues ([1][mir_protocol-closed_issues-1]),
5 open issues ([1][mir_protocol-open_issues-1])

[mir_protocol-merged-prs-1]: https://github.com/mir-protocol/plonky2/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[mir_protocol-closed_issues-1]: https://github.com/mir-protocol/plonky2/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[mir_protocol-open_issues-1]: https://github.com/mir-protocol/plonky2/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Reth](https://github.com/paradigmxyz/reth)

366 merged PRs ([1][reth-merged-prs-1]),
138 closed issues ([1][reth-closed_issues-1]),
59 open issues ([1][reth-open_issues-1])

[reth-merged-prs-1]: https://github.com/paradigmxyz/reth/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[reth-closed_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[reth-open_issues-1]: https://github.com/paradigmxyz/reth/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Rust Web3](https://github.com/tomusdrw/rust-web3)

10 merged PRs ([1][rust_web3-merged-prs-1]),
0 closed issues,
1 open issues ([1][rust_web3-open_issues-1])

[rust_web3-merged-prs-1]: https://github.com/tomusdrw/rust-web3/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[rust_web3-open_issues-1]: https://github.com/tomusdrw/rust-web3/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

#### [Starkware](https://github.com/starkware-libs)

256 merged PRs ([1][starkware-merged-prs-1], [2][starkware-merged-prs-2], [3][starkware-merged-prs-3]),
19 closed issues ([1][starkware-closed_issues-1], [2][starkware-closed_issues-2]),
31 open issues ([1][starkware-open_issues-1])

[starkware-merged-prs-1]: https://github.com/starkware-libs/cairo/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[starkware-merged-prs-2]: https://github.com/starkware-libs/papyrus/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[starkware-merged-prs-3]: https://github.com/starkware-libs/starknet-api/pulls?q=is%3Apr+is%3Aclosed+merged%3A2023-06-01..2023-06-30%20-author:app/dependabot
[starkware-closed_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[starkware-closed_issues-2]: https://github.com/starkware-libs/papyrus/issues?q=is%3Aissue+is%3Aclosed+closed%3A2023-06-01..2023-06-30%20-author:app/dependabot
[starkware-open_issues-1]: https://github.com/starkware-libs/cairo/issues?q=is%3Aissue+is%3Aopen+created%3A2023-06-01..2023-06-30%20-author:app/dependabot

- [Starknet Quantum Leap: Major Throughput Improvements are Here!](https://medium.com/starkware/starknet-quantum-leap-major-throughput-improvements-are-here-3e4e294ad8cd)
- [Cairo Roadmap: Join the Ride](https://medium.com/starkware/cairo-roadmap-join-the-ride-23f31dcad172)
- [Moving from Solidity to Cairo](https://starkware.medium.com/moving-from-solidity-to-cairo-7d44f9723c68)

If we've missed any other notable Rust Ethereum projects or ecosystems, feel free to contribute!


&nbsp;

## Events

<!--

Dec 1-2 | Online | [Event Sample](https://event.sample)

-->

Jul 6-Aug 6 | Online | [Sway Summer Online Hackathon](https://dorahacks.io/hackathon/sway-summer-hackathon?ref=fuel-labs.ghost.io)

Jul 10 | Online | [Encode x NEAR Horizon Eight-week Coding Bootcamp](https://www.encode.club/encode-near-horizon-bootcamp)

Jul 17-20 | Paris, France | [Ethereum Community Conference (EthCC) 6](https://www.ethcc.io/)

Jul 30-Aug 1 | Barcelona, Spain | [Zcon 4](https://zfnd.org/zcon4/)

Aug 2 | Barcelona, Spain | [ZKProof 5.5](https://zkproof.org/events/zkproof-5-5-barcelona/)

Aug 28-30 | Palo Alto, CA, US | [The Science of Blockchain Conference 2023](https://cbr.stanford.edu/sbc23/)

Sep 5-6 | Seoul, Korea | [Korea Blockchain Week](https://koreablockchainweek.com/)

Sep 11-13 | Berlin, Germany | [DappCon](https://www.dappcon.io/)

Sep 12-13 | Singapore | [DeCompute 2023](https://www.decompute.xyz/)

Sep 12-15 | Albuquerque, NM & Online | [RustConf 2023](https://rustconf.com/)

Sep 20 | London, UK | [zkSummit10](https://www.zksummit.com/)

Sep 26-28 | Madrid, Spain | [Stellar Meridian](https://meridian.stellar.org/)

Oct 5-6 | US - Virtual Eastern | [Blockchain Security Summit 2023](https://www.sans.org/cyber-security-training-events/blockchain-summit-2023/)

Oct 30-Nov 3 | Amsterdam, Netherlands | [Solana Breakpoint](https://solana.com/breakpoint)


&nbsp;

## Careers

<!--

Company name | Location A, B, Remote
- [Job 1](https://job.one)
- [Job 2](https://job.two)

-->



More jobs can be found at [Job Board][page-jobboard].

[page-jobboard]: https://rustinblockchain.org/job-board/

&nbsp;

Want to be included in the next issue? Feel free to submit a PR to the
[next draft](https://github.com/rust-in-blockchain/Rust-in-Blockchain/tree/master/draft).

**Join the discussion on [RiB telegram group][ribtg]** **❤️**

[ribtg]: https://t.me/rustinblockchain


