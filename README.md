# Informal Notes on Expected Changes in OCTO-039 and OCTO-040 for Version 2

[OCTO-039, Introduction to Blockchain Name System Technologies](https://www.icann.org/octo-039-en.pdf) and [OCTO-040, Introduction to Blockchain Technologies](https://www.icann.org/octo-040-en.pdf) will both be updated to version 2 in approximately April 2025.
In order to meet this deadline, all changes must be accepted by mid-March, 2025.

The notes are meant to help track the expected changes to the two documents.
The originals for the two documents are in Microsoft Word; this makes commenting and tracking in the originals difficult.
Thus, this repo is used for noting changes and getting external comments on them.

All questions about this should be sent to [Paul Hoffman](paul.hoffman@icann.org).


## 1. OCTO-039

### 1.1 To Do and/or Think About

Section 4: Add a pointer to a new document that describes a public ledger that is not a blockchain that can hold inventory such as name system data like ownership, delegation, DNSSEC keys, and so on.

Add much more emphasis that, because the public interfaces with resolvers and not to blockchains, the operation of the resolver is more important than the blockchain contents.

Replace the current appendix with a longer one that lists features for a handful of blockchain name systems to help readers compare them.

### 1.2 Already Done

Section 2: Answer the question "Why do some people think there are benefits to blockchain name systems, and what are those benefits?" a bit in Section 2, for readers who wonder why we're talking about them at all. (_done_)

Add pointer to SAC123, SSAC Report on the Evolution of Internet Name Resolution. (_done_)


## 2. OCTO-040

### 2.1 To Do and/or Think About

Add a section on blockchain standards that originate from recognized SDOs such as ISO, ITU-x, and IEEE.

Add an appendix on chain-specific specs such as BIPs and ERCs. Maybe Enterprise Ethereum Alliance. Maybe mention CASA and Chain Agnostic Improvement Proposals.

Add an appendix that lists features for a handful of blockchains to help readers compare them.

### 2.2 Already Done

Items in this section have already been entered in the Word file for the upcoming v2 document.

Section 6, paragraph 3 (before the bulleted list): remove "that you can fully trust that the transactions in the blockchain, and" because it is redundant. (_done_)

Section 8, paragraph 3: replace *sidechain* with *independent chain* (three times).
Apparently the blockchain ecosystem does agree on a single definition for "sidechain", but generally agrees that an "independent chain" is one that has no relationship with any other blockchain. (_done_)

Briefly talk about how some blockchains reuse or expand earlier blockchains' VMs. (_done_)

Clarify that accounts must have unique identifiers on them. (_done_)

