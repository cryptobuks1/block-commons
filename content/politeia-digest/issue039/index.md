---
title: 'Issue 39 - October 15 - November 16 2020'
subtitle: ''
summary: 
tags:
- Politeia
categories:
- Politeia Digest
date: "2020-11-16T12:10:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  placement: 3
  caption: 'Image credit: @sænder'
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: [Politeia Digest]
---

**Treasury balance: 643,095 DCR (approx +11,982 DCR/month) - $11.8 million (+$221k/month) based on $18.41 DCR price**

## New proposals

**[GoDCR: GoLang Native Desktop Wallet](https://proposals.decred.org/proposals/e5c8051)**

Published Nov 3 by raedah | edited Nov 5 |17 comments 

This proposal requests a budget of $60,000 for 6 months of development funding for this new desktop wallet written in Go using the Gio library for the interface. GoDCR first appeared in a [video](https://twitter.com/planetdecred/status/1290753362829352960) trailer on Twitter, and when current work on vspd staking is complete an initial release is planned. The GoDCR team has four members who would be funded to continue working on it (plus Sep/Oct in arrears), @oshorefueled, @sirmorrison, @song50119, and @codemaestro64. The proposal also includes $1,000/month sponsorship for Gio, reflecting the collaboration and benefits being derived from Gio by GoDCR, with the intention that GoDCR becomes a hero application for Gio. There is strong overlap between this and the mobile wallet proposal, as both rely on dcrlibwallet.

Comments are supportive of developing another desktop GUI wallet and appreciate the aim to be lightweight and not powered by Electron (which packages an entire browser stack into the app). There are some responses from Elias Naur, Gio lead, including a [description](https://proposals.decred.org/proposals/e5c8051d7426a754b3642aa2895839666a360abbdee3c1c1edd56ba152702875/comments/7) of a priority support relationship for GoDCR as a sponsor of Gio.

**[Mobile Wallets 2020-2021](https://proposals.decred.org/proposals/bc499c9)**

Published Nov 3 by raedah | edited Nov 16 | 20 comments 

This proposal requests a budget of $5,500/month for 8 months ($44,000 total) of continued work on the Android and iOS wallets - work on this had previously been covered by the Treasury as part of core development funding. The proposal recaps past progress towards initial releases in 2019 and v1.5 updates in 2020, and outlines a set of new features which are targets for the next six months if funded. These features include privacy support, staking support, coin control and UI improvements.

Comments are generally supportive of the proposal and the work on the mobile wallets to date.

On Nov 16 the proposal was edited to lower the cost to $5,500 (from $6,500) monthly, or $44,000 (from $52,000) total.

**[Decred Address Scanner](https://proposals.decred.org/proposals/3943bff)**

Published Nov 9 by joegruff | edited Nov 16 | 7 comments 

This proposal is for a lightweight address scanner app which can watch addresses and tickets, sending alerts when movements are detected. The app has been available for over a year with 500+ downloads, and the source code is already [available](https://github.com/JoeGruffins/dcraddrscanner) on GitHub. Payment in arrears of $3,000 for work already completed is requested, with a further $6,000 max for further development work. Planned work includes updating from Android 8.1 (API 27) to 10 (API 30) and replacing the QR code reader, and adding new features such as the ability to scan a ticket and be notified when it votes, estimated to be completed in four months.

Early comments concern adding extended public keys so that the app can watch all addresses associated with a wallet, but this is not a planned feature for the address scanner, which deliberately works at the level of individual addresses.

**[WhyDecred.com - A Marketing Initiative](https://proposals.decred.org/proposals/8a09324)**

Published Nov 9 by paris_smithson | edited Nov 16 | 16 comments 

This proposal requests a budget of $16,800 to produce 18 paintings and a [website](https://www.whydecred.com/why-decred) which showcases them along with information about Decred and a shop to sell merchandise with prints of the paintings. The original artworks would cost $900 each and be sold for $3,000+, profit from the sale of merchandise would be reinvested in a "profit sharing" initiative where the community can have input into how it is used to further promote the WhyDecred website. The proposal includes two lists of problems with money and Decred's advantages, with each artwork intended to support one of these points. If the proposal is funded, the 16 artworks will be produced (billing monthly as they are completed), and when they are in place a one month marketing budget of $2,400 will be used to promote the site. A second proposal would follow, with a report about the success of the marketing effort and request for more funds to do more marketing and produce more artworks. This proposal was previously discussed on [Reddit](https://www.reddit.com/r/decred/comments/jkmhbv/whydecredcom_proposal_open_talk/), and also involved a Twitter [poll](https://twitter.com/ParisSmithson/status/1323071532692897792) about the choice between cheaper and more expensive artwork.

Comments on the proposal appreciate the initiative that has been shown to put up the site and start producing art, but some take issue with the high number of pieces to be produced under the scope of a first proposal.

The proposal was edited shortly before press to reduce the requested amount by $10K, with that financing to be provided up front by @paris_smithson and reimbursement requested in a second proposal after the first one has been completed.

## Approved proposals

**[Decred Content and Asset Translation Proposal](https://proposals.decred.org/proposals/c093b8a)**

Published Oct 14 by kozel | edited Oct 25 | 22 comments (+15)

Final voting figures: 8,624 Yes votes, 2,930 No votes (75% Yes) - voter participation of 25%.

## Rejected proposals

All of the proposals for the decred.org messaging RFP were rejected:

- [D.R.E.A.M.](https://proposals.decred.org/proposals/4532397) - 48% approval, turnout of 29%
- ["Money Evolved"](https://proposals.decred.org/proposals/02d9fc2) tagline with minimal changes to the site - 25% approval, turnout of 25%
- Decred - Building Revolutionary [Infrastructure](https://proposals.decred.org/proposals/d6ff458) - 16% approval, turnout of 18%
- "Money Evolved" tagline - plus ["Fair"](https://proposals.decred.org/proposals/f0a00d5) box and page added to the site - 7% approval, turnout of 17%

## Other news

Politeia reached two years in operation on Oct 16, check out this [report](https://blockcommons.red/publication/politeia-at-2/) with stats for the second year.

## About this issue

Snapshot of Politeia data for this issue is based on this [commit](https://github.com/decred-proposals/mainnet/commit/d8266070d199dc4302235883bc33d4507010803c).

Content for this edition was authored by @richard-red with fixes from @bee.

Image credit: @sænder