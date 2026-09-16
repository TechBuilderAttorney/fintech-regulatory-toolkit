# US Payments Regulatory Guide

> **Federal and State Frameworks for Electronic Payments, Card Issuing, ACH, and Stored Value**

**Last Updated:** September 2026

---

## Table of Contents

- [1. Electronic Fund Transfers Act & Regulation E](#1-electronic-fund-transfers-act--regulation-e)
  - [1.1 Scope of Coverage](#11-scope-of-coverage)
  - [1.2 Consumer Liability for Unauthorized Transfers](#12-consumer-liability-for-unauthorized-transfers)
  - [1.3 Error Resolution Procedures](#13-error-resolution-procedures)
  - [1.4 Initial Disclosures](#14-initial-disclosures)
  - [1.5 Preauthorized Transfers](#15-preauthorized-transfers)
  - [1.6 Service Provider Not Holding Consumer's Account](#16-service-provider-not-holding-consumers-account)
  - [1.7 Preemption of State Laws](#17-preemption-of-state-laws)
- [2. Card Issuing: Network Rules and Sponsor Bank Model](#2-card-issuing-network-rules-and-sponsor-bank-model)
  - [2.1 The Sponsor Bank Model](#21-the-sponsor-bank-model)
  - [2.2 What the Sponsorship Agreement Covers](#22-what-the-sponsorship-agreement-covers)
  - [2.3 Card Program Types](#23-card-program-types)
  - [2.4 Interchange Economics](#24-interchange-economics)
  - [2.5 Compliance Perimeter](#25-compliance-perimeter)
- [3. NACHA Operating Rules](#3-nacha-operating-rules)
  - [3.1 Key Definitions](#31-key-definitions)
  - [3.2 2026 NACHA Rule Changes](#32-2026-nacha-rule-changes)
  - [3.3 Return Rates](#33-return-rates)
  - [3.4 Return Reason Codes](#34-return-reason-codes)
  - [3.5 Enforcement](#35-enforcement)
- [4. Stored Value and Prepaid Access](#4-stored-value-and-prepaid-access)
  - [4.1 Federal Definition: Prepaid Access](#41-federal-definition-prepaid-access)
  - [4.2 Closed-Loop Prepaid Access](#42-closed-loop-prepaid-access)
  - [4.3 The Multi-Merchant Gift Card Trap](#43-the-multi-merchant-gift-card-trap)
  - [4.4 Agent-of-the-Payee Doctrine](#44-agent-of-the-payee-doctrine)
  - [4.5 State Money Transmission vs. Prepaid Access](#45-state-money-transmission-vs-prepaid-access)
- [5. Federal Prudential Regulators](#5-federal-prudential-regulators)
  - [5.1 Office of the Comptroller of the Currency (OCC)](#51-office-of-the-comptroller-of-the-currency-occ)
  - [5.2 Federal Reserve Board](#52-federal-reserve-board)
  - [5.3 Federal Deposit Insurance Corporation (FDIC)](#53-federal-deposit-insurance-corporation-fdic)
  - [5.4 National Credit Union Administration (NCUA)](#54-national-credit-union-administration-ncua)
  - [5.5 Federal Trade Commission (FTC)](#55-federal-trade-commission-ftc)
- [6. Sources & Citations](#6-sources--citations)

---

## 1. Electronic Fund Transfers Act & Regulation E

Regulation E (12 CFR Part 1005) implements the Electronic Fund Transfer Act (EFTA) and governs consumer electronic fund transfers, including error resolution, consumer liability, and required disclosures.

### 1.1 Scope of Coverage

Regulation E applies to electronic fund transfers (EFTs) involving consumer accounts, including:

- Point-of-sale transfers
- ATM transactions
- Direct deposits and preauthorized transfers
- Telephone-initiated transfers
- Debit card transactions
- Prepaid account transactions (subject to specific rules)

Prepaid accounts that are not "hybrid prepaid-credit cards" are covered for certain provisions. Hybrid prepaid-credit cards that access both asset and credit features trigger additional Truth in Lending Act (TILA) and Regulation Z requirements.

### 1.2 Consumer Liability for Unauthorized Transfers

Under 12 CFR 1005.6, consumer liability for unauthorized EFTs is tiered based on prompt notification:

| Timing of Notification | Maximum Consumer Liability |
|------------------------|---------------------------|
| Within 2 business days of learning of loss/theft | $50 |
| After 2 business days but within 60 days of transmittal of statement | $500 |
| More than 60 days after statement transmittal | Unlimited (for transfers occurring after the 60-day period) |

The 60-day period is measured from when the institution sends the periodic statement containing the unauthorized transfer.

### 1.3 Error Resolution Procedures

Section 1005.11 establishes the error resolution framework:

**Notice requirements:**

- The institution must provide an error resolution notice annually
- The notice must be substantially similar to Model Form A-7 in the regulation

**Investigation timeline:**

- The institution must investigate and determine whether an error occurred within **10 business days** of receiving notice
- If the institution cannot complete investigation within 10 business days, it may take up to **45 calendar days** total, provided it provisionally credits the consumer's account
- For POS debit card transactions and foreign-initiated transfers, the period may extend to 90 days

**Provisional credit:**

- If the institution takes more than 10 business days, it must provisionally credit the consumer's account within that period
- The consumer must have use of the funds during the investigation

### 1.4 Initial Disclosures

Section 1005.7 requires initial disclosures at the time the consumer contracts for an EFT service. Required content includes:

- Terms and conditions of the EFT service
- Consumer liability for unauthorized transfers
- Telephone number and address for error notification
- Institution's business days
- Summary of the error resolution process
- Fees for EFTs and right to receive documentation

### 1.5 Preauthorized Transfers

Section 1005.10 governs preauthorized transfers:

- **Written authorization required:** Preauthorized transfers from a consumer's account require written authorization, signed or similarly authenticated (electronic signatures acceptable under E-Sign)
- **Copy to consumer:** The party obtaining authorization must provide a copy to the consumer
- **Stop payment:** Consumers may stop payment orally or in writing up to 3 business days before the scheduled transfer
- **Varying amounts:** If the amount varies from the previous transfer, the payee or institution must send written notice at least 10 days before the transfer

### 1.6 Service Provider Not Holding Consumer's Account

Section 1005.14 applies to entities that provide EFT services but do not hold the consumer's account. Such providers are subject to all Regulation E requirements if they:

- Issue a debit card or other access device
- Have no agreement with the account-holding institution regarding such access

### 1.7 Preemption of State Laws

Regulation E sets a floor, not a ceiling. State laws that are inconsistent with federal requirements are preempted. A state law is inconsistent if it:

- Requires or permits a practice prohibited by federal law
- Provides for greater consumer liability than federal limits
- Allows longer error investigation periods
- Requires different disclosure content

States may apply for exemptions if state law is substantially similar and adequately enforced.

---

## 2. Card Issuing: Network Rules and Sponsor Bank Model

### 2.1 The Sponsor Bank Model

A non-bank entity cannot directly join Visa or Mastercard as a principal member without meeting significant capital, operational, and certification requirements. Instead, most fintechs and program managers operate through **BIN sponsorship**.

**How BIN sponsorship works:**

- A bank with principal membership in Visa or Mastercard shares its BIN range with a third party
- The sponsor bank remains the **legal issuer of record** — its name appears on scheme statements, its capital backs the program, its compliance team owns regulatory liability
- The third party operates the customer-facing program: brand, product design, marketing, cardholder support

### 2.2 What the Sponsorship Agreement Covers

A BIN sponsorship agreement is fundamentally a **risk-allocation document**, not a service contract. Key provisions include:

| Provision | What to Watch |
|-----------|---------------|
| **BIN allocation** | Whether BIN ranges are dedicated or shared |
| **Term and renewal** | Notice window for non-renewal; pricing renegotiable when window opens |
| **Exclusivity** | Whether volume may go to a second sponsor |
| **Minimums** | Monthly minimums, committed volume, shortfall payments |
| **Settlement mechanics** | Who holds settlement account, funds release timing, offset rights |
| **Reserves and collateral** | Cash reserve, rolling reserve, letter of credit sized to chargeback exposure |
| **Indemnities** | Whether capped and how long they survive termination |
| **Audit rights** | Bank's right to examine operations and suspend new account opening |
| **Change of control** | Whether a sale needs bank consent or triggers termination |
| **Termination/wind-down** | How long wind-down runs, who funds it, reserve hold periods |

### 2.3 Card Program Types

| Program Type | Description |
|--------------|-------------|
| **Prepaid** | Funds loaded before spending; settlement risk contained by balance |
| **Debit** | Cards linked to balance held at issuer; real-time authorization |
| **Credit** | Cards backed by credit line; requires banking licence to lend on balance sheet |
| **Virtual** | Card numbers issued in software; no physical artifact |

### 2.4 Interchange Economics

Interchange — the fee paid by the merchant's acquirer to the issuer — is the largest revenue line for card programs. The sponsor and program manager split interchange under negotiated terms.

**Regulation II** (Debit Card Interchange Fees and Routing) establishes standards for debit card interchange:

- Caps interchange fees for large issuers (assets ≥ $10 billion) at reasonable and proportional levels
- Exempts small issuers (assets < $10 billion) from the interchange fee standard
- Prohibits network exclusivity — issuers must enable at least two unaffiliated networks
- Prohibits inhibiting merchant routing choice

### 2.5 Compliance Perimeter

The sponsorship contract must define who owns:

- KYC and customer identification
- AML transaction monitoring
- Sanctions screening
- Chargeback management
- Scheme reporting
- Regulatory examination response

The sponsor bank cannot delegate its regulatory obligations — it remains liable to regulators and the card networks regardless of operational delegation.

---

## 3. NACHA Operating Rules

NACHA governs the ACH Network, which processes electronic credit and debit transfers between financial institutions.

### 3.1 Key Definitions

- **ODFI** (Originating Depository Financial Institution): The bank that originates ACH entries on behalf of an Originator
- **RDFI** (Receiving Depository Financial Institution): The bank that receives ACH entries for posting to a Receiver's account
- **Originator**: The entity that initiates ACH entries
- **Third-Party Sender (TPS)**: An entity that acts as an intermediary between an Originator and an ODFI

### 3.2 2026 NACHA Rule Changes

**Phase 1 — Effective March 20, 2026:**

Risk-based fraud monitoring applies to:

- All ODFIs
- Largest non-consumer Originators, Third-Party Service Providers, and Third-Party Senders with 2023 ACH origination volume exceeding 6 million entries

Required processes must be:

- Risk-based
- Documented
- Reasonably designed to identify suspicious activity (including business email compromise and social engineering)

**Standardized Company Entry Descriptions:**

- **PAYROLL** required for wage and salary PPD credit transactions
- **PURCHASE** required for certain online consumer e-commerce debit entries

**Phase 2 — Effective June 22, 2026:**

The volume threshold is eliminated. The fraud monitoring rule applies to all remaining non-consumer Originators, TPSPs, and TPSs regardless of transaction volume.

**Additional Updates — Effective September 18, 2026:**

- Clarification of International ACH Transaction (IAT) classification
- Non-same-day ACH credit funds generally must be available by **9:00 a.m. local time** on settlement date

### 3.3 Return Rates

| Threshold | Rate | Consequence |
|-----------|------|-------------|
| **Unauthorized return rate** | 0.5% | Direct rule violation; corrective action and enforcement through ODFI |
| **Administrative return rate** | 3% | Preliminary inquiry; may lead to enforcement |
| **Overall return rate** | 15% | Preliminary inquiry; may lead to enforcement |

### 3.4 Return Reason Codes

NACHA publishes comprehensive Return Reason Codes and Notification of Change (NOC) Codes. Key unauthorized return codes include:

- **R05** — Unauthorized Debit to Consumer Account
- **R07** — Authorization Revoked by Customer
- **R10** — Customer Advises Originator is Not Known and/or Not Authorized
- **R11** — Customer Advises Entry Not in Accordance with Terms of Authorization
- **R29** — Corporate Customer Advises Not Authorized

### 3.5 Enforcement

NACHA enforcement operates through the ODFI:

| Level | Consequence |
|-------|-------------|
| **Level 1** | Notification and corrective action plan |
| **Level 2** | Financial penalties assessed through ODFI |
| **Level 3** | Restriction or suspension of ACH origination privileges |

---

## 4. Stored Value and Prepaid Access

### 4.1 Federal Definition: Prepaid Access

**31 CFR 1010.100(ww)** defines prepaid access as "access to funds or the value of funds that have been paid in advance and can be retrieved or transferred at some point in the future through an electronic device or vehicle, such as a card, code, electronic serial number, mobile identification number, or personal identification number."

### 4.2 Closed-Loop Prepaid Access

**31 CFR 1010.100(kkk)** defines closed-loop prepaid access as prepaid access usable only for goods or services in transactions involving a **defined merchant or location** (or set of locations), such as a specific retailer or retail chain, college campus, or subway system.

**Key distinction:** The closed-loop exemption applies to the **instrument**, not the operator. An entity can sell closed-loop instruments and still be a money transmitter if it is separately engaged in the transfer of funds between parties.

### 4.3 The Multi-Merchant Gift Card Trap

The most underappreciated compliance risk: a multi-merchant gift card program can trigger money transmission regulation even if the card itself is closed-loop.

**The problem sequence:**

1. Operator collects funds from customer when card is sold
2. Operator later transmits funds to the merchant when card is redeemed
3. This is the textbook definition of money transmission under federal law (31 CFR 1010.100(ff)) and state money transmission statutes

**The closed-loop exemption does not protect the operator** — it only exempts the instrument from being a regulated prepaid access product.

### 4.4 Agent-of-the-Payee Doctrine

The exemption that actually protects operators is the **agent-of-the-payee doctrine**:

**Concept:** If the operator collects money from a customer as the **appointed agent of the merchant** who will deliver goods or services, the customer's payment to the operator is legally a payment to the merchant. The merchant's obligation is extinguished at that moment. Subsequent settlement between operator and merchant is internal, not a transmission of funds between strangers.

**Requirements to invoke:**

- Contracts between operator and participating merchants
- Operator must be **appointed as agent**
- Timing of payment collapsed
- Destination of funds constrained
- Use of regulated banking system for settlement flow
- All must be in place **before the first card is sold**

**Federal recognition:** FinCEN recognizes a federal version through the payment processor exemption (FIN-2013-R002 and FIN-2014-R009). Several states have codified explicit agent-of-the-payee exemptions (e.g., Texas Finance Code).

### 4.5 State Money Transmission vs. Prepaid Access

| Framework | Focus | Key Question |
|-----------|-------|--------------|
| **Federal (FinCEN)** | Prepaid access as a regulated activity | Is the instrument a regulated prepaid access product? |
| **State money transmission** | Fund transmission as a licensed activity | Is the operator transmitting funds? |
| **Agent-of-payee** | Exemption from money transmission | Is the operator acting as the merchant's agent? |

---

## 5. Federal Prudential Regulators

### 5.1 Office of the Comptroller of the Currency (OCC)

The OCC charters and supervises national banks, federal savings associations, and federal branches/agencies of foreign banks.

**National Trust Bank Charter:**

On February 27, 2026, the OCC issued a final rule amending 12 CFR 5.20 to clarify that national trust banks are **not limited to fiduciary activities**.

Key changes:

- Replaces "fiduciary activities" with "operations of a trust company and activities related thereto"
- Confirms national trust banks may engage in **non-fiduciary activities** including custody and safekeeping
- Effective April 1, 2026
- The "core banking functions" requirement (receiving deposits, paying checks, lending money) applies only to special purpose banks not operating as trust companies

**Chartering activity:** The OCC received 18 bank charter applications in 2025 — equal to the prior four years combined. Comptroller Gould has stated the agency evaluates applications against a statutory standard of "a reasonable chance of success."

**Why fintechs seek national charters:**

- Federal preemption of most state trust and custody laws
- Single federal supervisory relationship replacing 50-state patchwork
- Uniform rulebook for accounts, payments, and custody services

**Trade-offs:**

- Capital commitments
- BSA/AML compliance program satisfying OCC examination standards
- Potential constraints on affiliate activities

### 5.2 Federal Reserve Board

The Federal Reserve supervises state-chartered banks that are members of the Federal Reserve System, bank holding companies, and certain non-bank financial institutions.

**Regulation II enforcement:** The Fed enforces Regulation II with respect to state member banks.

**FedNow Service:** Launched July 2023, providing real-time payment clearing and settlement infrastructure.

### 5.3 Federal Deposit Insurance Corporation (FDIC)

The FDIC supervises state-chartered banks that are not members of the Federal Reserve System (state nonmember banks) and state-chartered thrifts.

**Regulation II enforcement:** The FDIC enforces Regulation II with respect to state nonmember banks and state-chartered thrifts.

### 5.4 National Credit Union Administration (NCUA)

The NCUA charters and supervises federal credit unions.

**Chartering requirements:** The NCUA Chartering and Field of Membership Manual incorporates current chartering requirements for federal credit unions. IRPS 10-1 was rescinded effective September 8, 2026, to reduce burden by limiting sources FCUs must check for compliance.

**Field of Membership:** Federal credit unions must define their field of membership in their charter. Occupational common bond requirements, trade, industry, or profession (TIP) designations, and geographic limitations are governed by 12 CFR Part 701 Appendix B.

**Regulation II enforcement:** The NCUA enforces Regulation II with respect to federally insured credit unions.

### 5.5 Federal Trade Commission (FTC)

The FTC enforces Regulation II with respect to entities not covered by the federal banking regulators (OCC, Fed, FDIC, NCUA).

---

## 6. Sources & Citations

- **Regulation E / EFTA:** 12 CFR Part 1005
- **NACHA 2026 Rules:** Capitol Federal summary; Stampli analysis; NACHA Operating Rules
- **BIN Sponsorship:** Windsor Drake analysis; Codego guide
- **Prepaid Access:** 31 CFR 1010.100
- **Multi-Merchant Gift Card Trap:** ABA Business Law Today
- **OCC Chartering:** FinTech Law; PYMNTS; Global Fintech & Digital Assets Blog
- **Regulation II:** Federal Reserve Board; Federal Reserve data collections
- **NCUA Chartering:** GovInfo; eCFR.io
- **FedNow:** SEC filing reference

---

*This guide is for informational purposes only and does not constitute legal advice. Requirements are subject to change. Consult qualified counsel for specific compliance obligations.*
