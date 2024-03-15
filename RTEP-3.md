|RTEP: 3|Transition from Avatar Burning to Reselling|
|-:|:---|
|__Type:__|Upgrade|
|__Authors:__|Mick van Dijke|
|__Version:__|0.0.1|
|__Status:__|Draft|
|__Created:__|2024-03-15|
|__Updated:__||
|__Resolution:__||

## Abstract

This proposal outlines a modification to the RCAX smart contract to transition from burning received Reddit avatars to holding and selling them through the smart contract.

## Motivation

Address the diminished effectiveness of reducing avatar supply due to Reddit's frequent avatar releases, encourage the use of RCAX tokens, reduce the total supply of RCAX.

## Specification

Instead of burning, the smart contract will hold and automatically list received avatars for sale. Avatars will be initially priced at their corresponding burn reward in RCAX plus a 20% markup. The price will half every 3 months (in blocks) from the date the avatar was listed. Proceeds from sales are burned, reducing the total RCAX supply. Avatars will be listed and purchased directly through the RCAX smart contract.  

## Rationale

The rationale behind the proposed modifications to the RCAX smart contract is multifaceted.

***Diminished Effectiveness of Avatar Burning***

The initial mechanism of burning received Reddit avatars to reduce their supply and thereby increase scarcity and value has been challenged by Reddit's frequent releases of new avatars. This has led to a situation where the intended scarcity is not achieved, as the continuous influx of new avatars dilutes the overall impact of the burning process.

***Encouragement of RCAX Token Utilization***

By listing the avatars for sale in exchange for RCAX tokens, the proposal directly incentivizes the use and circulation of RCAX within the ecosystem. This is expected to increase demand for RCAX tokens as users seek to purchase avatars, thereby contributing to the token's utility and value.

***Reduction of Total RCAX Supply***

The proposal specifies that proceeds from the avatar sales are to be burned, thereby reducing the total supply of RCAX tokens. This mechanism serves as an indirect but effective method of reducing token supply, which can contribute to an increase in the token's value.
