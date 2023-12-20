# Table of content
* About
* Diagram Types
* Installation
* Release
* Security and safe diagrams
* Reporting vulnerabilities

# About 
Mermaid is a diagramming and charting tool built on JavaScript, designed to simplify the creation and modification of intricate diagrams using Markdown-inspired text definitions and a dedicated renderer. Its primary objective is to bridge the gap between development and documentation.

The challenge known as "Doc-Rot," a situation where documentation becomes outdated due to the time and effort required for diagramming and documentation, is effectively addressed by Mermaid. The dilemma arises because creating and updating diagrams is time-consuming, yet the absence of accurate diagrams and documentation can hinder productivity and impede organizational learning.

# Diagram Types
Below are various examples showcasing the types of diagrams, charts, and graphs that can be created using Mermaid.

### Flowchart [[docs - live editor]](https://mermaid.live/edit#pako:eNpVUDtPwzAQ_ivWTSClVVo7DzIg0RS6FIEoE0mGU-LWVhs7clyVkuS_4yYL3HT6Xnf6Oih1xSGB_UlfSoHGku1HroibpywVRra2xrYgs9ljv-GW1Frxa09WdxtNWqGbRqrD_aRf3UQk7bY3GSdWSHUcJiod_W-K92SdbbGxuin-Mp8X3ZPnTL4LF_-fEYY710u2x2SPsxINSdEU4EHNTY2ycq93N0MOVvCa55C4tUJzzCFXg9Ph2erdVZWQWHPmHpybCi1fSzwYrMGFnlqHNqgg6eAbkgWL5oz5QRRGlC395SLw4Opg6uCF_-AHjEZRHCzp4MGP1i7Cn4fMD-OYhiFlYRzQeMz7GsnpKK-k1eZ1qnpsfPgFT5xy7A)
```
flowchart LR
    A[Christmas] -->|Get money| B(Go shopping)
    B --> C{Let me think}
    C -->|One| D[Laptop]
    C -->|Two| E[iPhone]
    C -->|Three| F[fa:fa-car Car]
```
<img width="1000" alt="Screenshot 2023-12-20 at 2 40 09 PM" src="https://github.com/Rockship-Tech/Rockship_wiki/assets/27566944/99cde4bb-531e-4688-b09d-18019601be64">

### Sequence diagram [[docs - live editor]](https://mermaid.live/edit#pako:eNptkMFOhDAQhl-lO1cLocWlpYc1Jh5cE0_eDJcGZhcitGstUSS8u6W4t53TZOb7_mRmhto2CAq-8HNEU-NTp89OD5UhoR77rsbkcLh7sa1R5Bn73pK1p6S130Q7JJMdH27CG1ZrsyKkRe3IgP_ouksCmkQnBHebTckxGpEO2u42fiQnxJ6cHWq_AwoDukF3TbhiXoUKfIsDVqBC22j3UUFllsDp0du3ydSgvBuRwnhptL9efB1etAE1ww8oxlMmypxxnpd7we4zTmECxVmZSiYzIcQ-k4yLYqHwa21IyNJyq6JkuZSyEDHvPS63eGw6b93r9vT4--UP2bZ12A)
```
sequenceDiagram
    Alice->>+John: Hello John, how are you?
    Alice->>+John: John, can you hear me?
    John-->>-Alice: Hi Alice, I can hear you!
    John-->>-Alice: I feel great!
```
<p align="center">
 <img width="647" alt="Screenshot 2023-12-20 at 2 51 48 PM" src="https://github.com/Rockship-Tech/Rockship_wiki/assets/27566944/013a043b-f0f8-4d01-8319-6c940b5cdc41">
</p>

### Gantt diagram [[docs - live editor]](https://mermaid.live/edit#pako:eNpdUE2LwjAQ_SvDnFtoqqfchLJ76kkvSi5DM-sGt4nE6UHE_77JJiruEEjmffDIu-EULKPGI3kR4yGNOPlh2MBnhmBwdIw0F8qS8EeIMwnAPk07ju0wFO7Ck7jgYVvuAm5A6HKC12hSDfSdWredSqeBVWer1Af55vgyaPqStJMCyBb7HlPlBdxlj_OZrDGPCNVnt-qrm_6HgIZ-bbHBmdO3nE1V3LLUYNLNbFCnp6V4Mmj8PelokbC9-gm1xIUbXM65lNrSAzyTP4TwXNk6CXEsTf8Vfv8FrNxv6w)
```
gantt
    title A Gantt Diagram
    dateFormat  YYYY-MM-DD
    section Section
    A task           :a1, 2014-01-01, 30d
    Another task     :after a1  , 20d
    section Another
    Task in sec      :2014-01-12  , 12d
    another task      : 24d
```
<p align="center">
 <img width="1000" alt="Screenshot 2023-12-20 at 3 31 14 PM" src="https://github.com/Rockship-Tech/Rockship_wiki/assets/27566944/312af8c5-a924-4597-9be4-b25694acf364">
</p>

### Class diagram [[docs - live editor]](https://mermaid.live/edit#pako:eNptkc9OwzAMxl8lygnE-gIVF8SYxGGn3aZIyE2szmrjjPzRBGPvTlLWMDZyif1zPuuLfZTaGZSt1COEsCToPVjFIp8nJgujePxqGrFMerilKwq7W7rFzsMf3IoH4iigx2u8iZ64Fz2yQX9ZLJKwBpvDu_urgoWIM5xsT_aOP0DUph3C8OxG52shHMjOwpy-J9DDnJ8u-5WP1X5N8R7oE195hRgr1sAvEP_VTyP4NdQ5NwoKbwcaTYU-cdXKhbToLZDJm5h0SsYdWlSyzaEBPyipuLyDFN3mg7Vso0-4kGlv8jjOi5vhHnjrXE3RUHR-fV50uU7fz5Oa9A)
```
classDiagram
    Animal <|-- Duck
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
      +String beakColor
      +swim()
      +quack()
    }
    class Fish{
      -int sizeInFeet
      -canEat()
    }
    class Zebra{
      +bool is_wild
      +run()
    }
```
<p align="center">
    <img width="646" alt="Screenshot 2023-12-20 at 3 33 28 PM" src="https://github.com/Rockship-Tech/Rockship_wiki/assets/27566944/81eadc51-0238-468c-9346-c19b81fe436f">
</p>

### State diagram [[docs - live editor]](https://mermaid.live/edit#pako:eNpdkD8PgjAQxb8KudEAEaX86eCiK5Ob1qGhjTRCa2ohKuG7W1uJxje9_O7u5e5GqBXjgOFmqOE7Qc-adtGwIjKwOi5OQRRtgr0RbeuRsw7a4j-q1CDk2VPv_8d_6FbTW-Ops3MohNBx3VHB7Frju4GAaXjHCWBrGdUXAkROto_2Ru0fsgZsdM9D6K_se8UMr1QCHuEOGGVxmpdJNqvIQngATlCMfpWupxCeStmEJF5-VOZpUaICubyDK_p4zoRRuvJfdM-cXpYMZBc)
```
stateDiagram-v2
    [*] --> Still
    Still --> [*]
    Still --> Moving
    Moving --> Still
    Moving --> Crash
    Crash --> [*]
```
<p align="center">
    <img width="373" alt="Screenshot 2023-12-20 at 3 36 04 PM" src="https://github.com/Rockship-Tech/Rockship_wiki/assets/27566944/8fb1448b-e5f8-4ebb-92d4-6e8d6820886f">
</p>

### Git graph [[docs - live editor]](https://mermaid.live/edit#pako:eNqFUL0KAjEMfpUj8z1BZ8HJyU26xDa05WxTQirIce9u9fQGRcz05fsJ4ZvBsScwEJLuBWu0ZejjOOek3_gsWFwcPF3pwvWlR3ITN_1gf1zY3BlTWalMEuhfGkbovh7y_dn5oVjQSJksmA49ymTBlqX7sCkfb8WBUWk0QqselXYJg2B-kxXLiXlbySdlOaxdPCtZ7v8PXqc)
```
gitGraph
    commit
    commit
    branch develop
    checkout develop
    commit
    commit
    checkout main
    merge develop
    commit
    commit
```
<p align="center">
    <img width="550" alt="Screenshot 2023-12-20 at 3 53 42 PM" src="https://github.com/Rockship-Tech/Rockship_wiki/assets/27566944/f154b022-e963-4d35-935f-d9bcebc1a023">

</p>

### Pie chart [[docs - live editor]](https://mermaid.live/edit#pako:eNo1kM1KxTAQhV8lzLqUxpifZuvdCqI7ySbeDNfgbVLSqVhL393Y0lkN35xzBs4K1xwQLIwRGUW6I3tBmpgPeSQM7GNh3_k-J0Isk0usjoNLvk0OmGXCqJM9eTqYkSd6PRGX0MCAZfAx1Ffrv8ABfeKADmxdgy9fDlzaqs7PlN-WdAVLZcYG5jF4wkv0t-KHE44-gV3hByznuhVcK22E1loq1cACtpK2k9IY3nd9Zx7U1sBvztXP2-4YyR-rS_RiT3vfj0c4hki5PB-97PVsf59KVzs)
```
pie title Pets adopted by volunteers
    "Dogs" : 386
    "Cats" : 85
    "Rats" : 15
```
<p align="center">
    <img width="393" alt="Screenshot 2023-12-20 at 3 55 38 PM" src="https://github.com/Rockship-Tech/Rockship_wiki/assets/27566944/10d442e7-b6f9-4caf-9503-04e7ae745bf9">

</p>

# Installation
```

git clone git@github.com:mermaid-js/mermaid.git
cd mermaid
npx pnpm install
pnpm test
```

# Release
```
npm publish
```

# Security and safe diagrams
Ensuring the security of public websites accepting user-generated Mermaid diagrams is crucial due to the risk of malicious scripts in user-submitted content. To address this, a new security level involves rendering Mermaid diagrams in a sandboxed iframe, preventing the execution of embedded JavaScript. While this enhances security, it may limit interactivity and block potential malicious code. Ongoing efforts aim to improve code sanitation but complete vulnerability elimination remains challenging.

# Reporting vulnerabilities
To report a vulnerability, email security@mermaid.live with details on the issue, steps to reproduce, affected versions, and any known mitigations.

