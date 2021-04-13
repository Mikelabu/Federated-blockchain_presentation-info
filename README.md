# Federated-blockchain_presentation-info

## Confidential Computing Consortium

The Confidential Computing Consortium (CCC) brings together hardware vendors, cloud providers, and software developers to accelerate the adoption of Trusted Execution Environment (TEE) technologies and standards.

CCC is a project community at the Linux Foundation dedicated to defining and accelerating the adoption of confidential computing. It will embody open governance and open collaboration that has aided the success of similarly ambitious efforts. The effort includes commitments from numerous member organizations and contributions from several open source projects.

Confidential Computing protects data in use by performing computation in a hardware-based Trusted Execution Environment. These secure and isolated environments prevent unauthorized access or modification of applications and data while in use, thereby increasing the security assurances for organizations that manage sensitive and regulated data.

Today, data is often encrypted at rest in storage and in transit across the network, but not while in use in memory. Additionally, the ability to protect data and code while it is in use is limited in conventional computing infrastructure. Organizations that handle sensitive data such as Personally Identifiable Information (PII), financial data, or health information need to mitigate threats that target the confidentiality and integrity of either the application or the data in system memory.

https://confidentialcomputing.io/
https://confidentialcomputing.io/webinar-outreach/



## Enarx

Enarx provides a platform abstraction for Trusted Execution Environments (TEEs) enabling creating and running “private, fungible, serverless” applications.

## What is Enarx?

Enarx is an application deployment system enabling applications to run within Trusted Execution Environments (TEEs) without rewriting for particular platforms or SDKs. It handles attestation and delivery into a run-time “Keep” based on WebAssembly, offering developers a wide range of language choices for implementation.
Enarx is CPU-architecture independent, enabling the same application code to be deployed across multiple targets, abstracting issues such as cross-compilation and differing attestation mechanisms between hardware vendors.
Work is currently underway on AMD SEV and Intel SGX, and we hope to support Intel TDX once we have more details and availability.





![image](https://user-images.githubusercontent.com/50616498/114480130-03372c00-9c56-11eb-9ec4-7e1197148063.png)



### Hyper ledger https://hyperledger-fabric.readthedocs.io/en/release-1.4/identity/identity.html
https://www.youtube.com/watch?v=js3Zjxbo8TM
![image](https://user-images.githubusercontent.com/50616498/114485071-6e393080-9c5f-11eb-9dad-1359ce3e0dae.png)
![image](https://user-images.githubusercontent.com/50616498/114485133-86a94b00-9c5f-11eb-8241-d3467eb69063.png)
![image](https://user-images.githubusercontent.com/50616498/114485189-9a54b180-9c5f-11eb-9631-2c8028735326.png)

# Case Studies
https://www.hyperledger.org/learn/publications/avanza-case-study
https://www.hyperledger.org/learn/publications/kiva-case-study
https://www.hyperledger.org/wp-content/uploads/2017/12/Hyperledger_CaseStudy_Sony.pdf

## https://www.hyperledger.org/learn/publications/kubernetes-case-study
![image](https://user-images.githubusercontent.com/50616498/114487128-26b4a380-9c63-11eb-80f9-8b5424682bce.png)
https://aws.amazon.com/marketplace/pp/B07Z8H2YK1?qid=1618280809300&sr=0-2&ref_=srh_res_product_title

https://hyperledger-fabric.readthedocs.io/en/release-2.2/private-data/private-data.html

urging private data

For very sensitive data, even the parties sharing the private data might want — or might be required by government regulations — to periodically “purge” the data on their peers, leaving behind a hash of the data on the blockchain to serve as immutable evidence of the private data.

In some of these cases, the private data only needs to exist on the peer’s private database until it can be replicated into a database external to the peer’s blockchain. The data might also only need to exist on the peers until a chaincode business process is done with it (trade settled, contract fulfilled, etc).

To support these use cases, private data can be purged if it has not been modified for a configurable number of blocks. Purged private data cannot be queried from chaincode, and is not available to other requesting peers.

![image](https://user-images.githubusercontent.com/50616498/114491707-27e9ce80-9c6b-11eb-9e29-6c50a97c164e.png)







