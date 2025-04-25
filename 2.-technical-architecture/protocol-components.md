# Protocol Components

## Sub-chain 1: Semantic & Behavior Layer:

Sub-chain 1 is a behavior analysis blockchain built on a lightweight node listening network and AI tagging nodes. It implements the following functions:

* Listen to full-chain transaction events and parse them with unified encoding.
* Generate a trusted full-chain tagging knowledge base through node voting consensus.
* AI analysis model on nodes analyzes behavior, intent, and characteristics of on-chain behavior, generating behavioral context.
* Node cooperation training to improve the tagging knowledge base.

Sub-chain Components:

1. On-chain lightweight node network: Listens to multi-chain transactions and events, serving as the on-chain behavior data collection layer.
2. Intelligent tagging node network: Combines models and knowledge bases to structure address/transaction behavior tagging.
3. AI tagging model: Maintained by the official FinTax, with node cooperation training, it tags transaction types, address identities, etc., and is deployed on intelligent tagging nodes.
4. On-chain tagging consensus mechanism: Node voting mechanism to unify address labels and behavior classification results.
5. Tagging knowledge base: A structured tagging database synchronized across all nodes.

## Sub-chain 2: zkPassport Layer

Sub-chain 2 is the identity infrastructure based on VC credentials, Zero-Knowledge Proof (zkProof), and privacy proofs.

* Address is identity, allowing for the programmable issuance of VCs.
* Proves permissions/identity/asset legitimacy through Zero-Knowledge Proof.
* Integrates with the True Value Layer, providing full-chain asset proof for zkPassport users.
* Supports integration with real-world credential systems (such as tax certificates, KYC VCs, etc.).
* zkProof is stored on-chain, immutable and verifiable.

Sub-chain Components:

1. Zero-Knowledge Proof generator and verifier: Generates and verifies privacy proofs based on zkSNARK, ensuring data is verified without being disclosed.
2. Off-chain credential integration module: Supports local apps or DApps to upload and verify off-chain credentials. zkProof is stored on-chain in a privacy-preserving manner, while real credentials remain on the local device.
3. zkPassport SDK: A development toolkit that provides VC display, zk generation, and interaction functions for front-end or wallet integration.
4. VC-zkProof on-chain storage node: Managed by a decentralized node network, responsible for receiving, verifying, and storing zkProof, ensuring that proof data on-chain is verifiable, immutable, and consensus-driven.
