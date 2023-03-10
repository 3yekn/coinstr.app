---
title: "👨‍💻 Development Update"
date : 2023-02-14
tags : 
  - business
  - tech
author : Max Gravitt
---

Development on Coinstr is moving along. The focus has been on the CLI and glue that connects the various interdependencies together in a way that solves users' problems. 

The CLI allows users to inspect users, publish events, subscribe to events, and create spending policies.

Creating spending policies shows the tree of satisifiable conditions in the terminal. 

![coinstr-policy-simple.png](coinstr-policy-simple.png)

# Next Steps
- Construct transactions and the corresponding signature requests required for a spend
- Send these signature requests through Nostr
- Sign and return the signature requests
- Aggregate the signatures into a transaction and broadcast

# Non-tech Work
- Improve visual identity
- Develop crisp business plan to show the value proposition, TAM, and compare to competitors
- Establish the Go-to-Market plan

![coinstr-policy.png](coinstr-policy.png)

[View Coinstr on Github](https://github.com/3yekn/coinstr)

[Follow me on Nostr](https://snort.social/p/npub1ws2t95pdtpna4ps62rrz75mm6ujsudjv70yj2jk4wsqjhedlw22qsqwew9)