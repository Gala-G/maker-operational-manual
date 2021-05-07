---
title: Risk
order: 3
hideLanguageSelector: true
keywords: "format, event, events, meetup, meetups, guide, agenda"
description: "This page describes the types of risk associated with owning a Vault and provides common practices for mitigating them."
---

# Vault Risk

<Callout icon="warning">


Owning a Vault is inherently risky.

</Callout>


This page describes the types of risk associated with owning a Vault and provides common practices for mitigating those risks. There are four major categories of risks to consider when creating a Vault: Market Risks, User Risks, Systemic Risks, and Parameter Variability Risk.

---

<Indent pad={2}>


## Market Risks

<Indent pad={3}>


Using a Vault involves generating Dai and transferring ownership of your assets to a smart-contract that can sell your assets in the event of a market downturn. Any Vault with Generated Dai has a Liquidation Price, the price of the underlying asset at which one's Vault would be liquidated. Using a Vault for leverage introduces additional risk. The potential for reward is higher through leverage, but the potential for loss is magnified as well.

_It is a common practice among users to maintain a high Collateralization Ratio to protect from Market Risks and thereby Liquidation._

</Indent>


## User Risks

<Indent pad={3}>


This type of risk is associated with user error. MakerDAO can NOT reverse transactions or recover funds sent to incorrect addresses or contracts.

</Indent>


## Systemic Risks

<Indent pad={3}>


Systemic risks associated with operation of the Maker Protocol include, but are not limited to:

Malicious hacks attack against the smart-contract infrastructure.

Black Swan events involving one or more collateral assets.

Failure of centralized infrastructure. For example, failed internet connections, MetaMask bugs, etc.

</Indent>


## Parameter Variability Risk

<Indent pad={3}>


**It's important to note that Vault owners are subject to changes in the Risk Parameters that govern the system. This equates to financial risk for the Vault owner. Below is a partial list of parameters that are subject to change:**

<List>


[Stability Fees](/learn/vaults/stability-fees/)

[Debt Ceiling](/faqs/makerdao-mcd-faqs/glossary/)

[Liquidation Penalty](/learn/vaults/liquidation/)

</List>


</Indent>


</Indent>


<Column>


<Box>


## Mitigating Risk

**Common practices for mitigating the risks associated with owning a Vault include:**

<Box>


Using price alerts and/or notifications to monitor Vaults

Increasing the collateralization ratio of a Vault

Maintaining enough liquidity outside of your Vault to pay back Dai generated by the Vault or add to its deposited collateral

</Box>


</Box>


</Column>
