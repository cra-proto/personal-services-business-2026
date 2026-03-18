# personal-services-business-2026 COP

*description of the COP*

**COP timeframe** 2026-03-04 - 2026-06-10

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-proto.github.io/personal-services-business-2026](https://cra-proto.github.io/personal-services-business-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-03-18

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(Income tax)
    node4(Corporation income tax)
    node5(Corporations)
    node6(Corporation income tax return)
    node7(Worker who performs services on behalf of their own corporation #40;personal services business#41;)
    node8(Excise and specialty taxes)
    node9(Underused Housing Tax)
    node10(Underused Housing Tax #40;UHT#41; multimedia toolkit)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 --x node5
    node5 --> node6
    node6 --> node7
    node2 --> node8
    node8 --> node9
    node9 --> node10
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/services/taxes.html" _blank
    click node3 "https://www.canada.ca/en/services/taxes/income-tax.html" _blank
    click node4 "https://www.canada.ca/en/services/taxes/income-tax/corporation-income-tax.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/corporations.html" _blank
    click node6 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/corporations/corporation-income-tax-return.html" _blank
    click node7 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/corporations/corporation-income-tax-return/tax-implications-personal-services-business.html" _blank
    click node8 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies.html" _blank
    click node9 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies/underused-housing-tax.html" _blank
    click node10 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies/underused-housing-tax/underused-housing-tax-multimedia-toolkit.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4,node6,node7,node10 inscope
```
