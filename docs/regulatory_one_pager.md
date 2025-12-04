Internull Institutional – Regulatory Compliance One-Pager
A privacy-preserving technical layer designed to be fully compatible with EU, Swiss, and U.S. regulatory frameworks

Internull Institutional provides cross-chain transaction privacy for VCs, hedge funds, family offices, market makers, and protocol treasuries without interfering with their regulatory obligations. Internull does not act as a custodian, intermediary, CASP, MSB, or financial service provider; instead, it serves as a technical privacy infrastructure that institutions integrate into their existing compliance frameworks.

The design principle is clear:
Strong privacy on-chain; full compliance off-chain — owned and controlled by the regulated entity using Internull.

1. EU Regulatory Compatibility
✔ MiCA — Regulation (EU) 2023/1114 (Compatibility)

MiCA regulates crypto-asset service providers (CASPs), not general-purpose software or privacy infrastructure.

Internull does not perform MiCA-regulated services such as:

custody (Art. 3(1) MiCA)

execution of orders

operating a trading platform

placing crypto-assets

Therefore, MiCA obligations remain with the institution using Internull, not Internull itself.

Internull is MiCA-compatible because its architecture supports:

AML/CTF frameworks that CASPs must adopt under MiCA Title V

auditability, which aligns with MiCA’s record-keeping requirements

no custody, meaning Internull avoids MiCA licensing triggers

Institutions using Internull can meet all their obligations under MiCA Title V (Arts. 53–111) while benefiting from privacy on-chain.

✔ Travel Rule (EU Transfer of Funds Regulation (TFR)) — Regulation (EU) 2023/1113

The EU’s recast Transfer of Funds Regulation applies the Travel Rule to all crypto transfers with no minimum threshold (Arts. 14–17).

Internull supports TFR compliance by enabling institutions to:

attach originator and beneficiary information off-chain (required under Art. 14)

retain structured records (Art. 16)

handle transfers to self-hosted wallets through off-chain verification (Art. 17)

Because Internull never strips Travel Rule data — it simply separates it from the public blockchain — CASPs can comply with the TFR while maintaining privacy on-chain for competitive reasons.

✔ AMLD4/5 — Directive (EU) 2015/849 & amendments

AMLD4/5 require:

Customer Due Diligence (Art. 13)

Ongoing monitoring (Art. 18)

Data retention for five years (Art. 40)

Internull supports these obligations by providing:

mechanisms for institutions to store and link deposit/withdrawal provenance off-chain

encrypted logs enabling institutions to demonstrate lawful source/destination of funds to auditors or FIUs

sanctions-screening hooks for institutional workflows

Again, obligations stay with the CASP, not Internull.

✔ DORA — Regulation (EU) 2022/2554 (Digital Operational Resilience Act)

DORA applies to EU financial entities, not to general technology vendors per se.

However, Internull is engineered to be compatible with DORA outsourcing standards, which require:

ICT risk management (Arts. 5, 8–15)

high availability and incident reporting capabilities

oversight of critical ICT third-party service providers

Internull’s institutional deployment allows CASPs and financial institutions to treat Internull as a DORA-compatible ICT component, with:

redundancy and uptime guarantees

secure smart contract architecture

auditability and incident-response integration

This makes Internull safe for use by EU-regulated entities.

2. Swiss Regulatory Compatibility
✔ Swiss Anti-Money Laundering Act (AMLA, SR 955.0)
✔ AMLO-FINMA (SR 955.033.0)
✔ FINMA Guidance 02/2019 — “Payments on the Blockchain”

Swiss law requires VASPs to:

identify contracting parties (AMLA Art. 3)

verify beneficial ownership (Art. 4)

collect Travel Rule data for blockchain transfers

verify control of unhosted wallets (FINMA 02/2019)

Internull supports these requirements by enabling institutions to:

verify ownership of self-hosted wallets prior to interacting with privacy pools

attach Travel Rule data off-chain

maintain full internal traceability for FINMA audits

Internull does not perform VASP services and therefore does not fall under FINMA licensing, but its design enables Swiss-regulated institutions to use it safely.

3. U.S. Regulatory Compatibility
✔ Bank Secrecy Act (BSA) — 31 U.S.C. § 5311 et seq.
✔ FinCEN Guidance FIN-2019-G001 (Convertible Virtual Currency Entities)
✔ FinCEN Advisory FIN-2019-A003 (Mixers/Tumblers)
✔ OFAC Sanctions Compliance (31 C.F.R. Chapter V)

Under U.S. law, an entity becomes a regulated Money Services Business (MSB) if it:

accepts and transmits value (31 C.F.R. §1010.100(ff)), or

exercises control over customer funds.

Internull does neither:

it does not control private keys,

does not custody assets,

does not transmit money on behalf of customers.

Therefore, Internull is not a money transmitter, and MSB registration does not apply to the tech provider.

Instead, the institution using Internull (exchange, broker, OTC desk) continues to apply:

KYC/CDD

OFAC sanctions screening

Travel Rule compliance

SAR reporting obligations

Internull supports this by providing:

sanctions-screening hooks

off-chain traceability for compliance audits

a structure that explicitly forbids public, permissionless access, mitigating FinCEN mixer concerns (as raised in FIN-2019-A003)

This architecture avoids the failings of Tornado Cash, which was sanctioned because it was publicly available to DPRK-linked actors, not because privacy tech is illegal.

4. Why Internull Is Compliance-Friendly by Design

Across all jurisdictions, Internull follows four core principles:

1. No custody. No execution. No financial service.

→ Avoids CASP, MSB, VASP licensing triggers.

2. Permissioned institutional pools.

→ No commingling with illicit retail flow (a key FINMA, FATF, and OFAC concern).

3. Travel Rule & AML compatibility through off-chain messaging.

→ Institutions retain full identity records, as required under MiCA, AMLD, TFR, AMLA, BSA.

4. Internal auditability despite public anonymity.

→ Enables compliance teams to show complete transaction provenance privately.
