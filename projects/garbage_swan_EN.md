# 🗑 Swan Chain Exposed: Who’s Still Pretending Not to See? （Part One）

[中文版](./garbage_swan.md) | [English](./garbage_swan_EN.md)

<img width="958" height="957" alt="image" src="https://github.com/user-attachments/assets/7eab96f3-0ff0-4eec-a13e-1597d13f9210" />

---

## 1. Core Team Has Disappeared

* The current state of Swan Chain: the core team is gone, and the chain is being "kept alive by favors."
* Tech lead @xyznoise and operations lead @Knightly321 have vanished. No responses from the community, and they're nowhere to be found on Telegram or Discord. Who's left to run this thing? According to insiders, the engineers responsible for the chain left long ago—only a sysadmin is left to keep the servers alive. No backup, no high availability—if it crashes, it’s over.
* Look at their official on-chain snapshot updates—it hasn't been updated in over 6 months:
  [https://github.com/swanchain/swan-snapshots](https://github.com/swanchain/swan-snapshots)

<img width="941" height="587" alt="1" src="https://github.com/user-attachments/assets/d8541731-fc39-4dd1-ac39-0b5d250fdcfc" />

---

## 2. Token Unlock + Price Manipulation: Same Old Exit Scam

In June, nearly **100 million** tokens were unlocked. Look at this wallet:
[https://swanscan.io/address/0xFafA3bD66A9e5B6C813B83848121a08E0A61D453/tokentxns](https://swanscan.io/address/0xFafA3bD66A9e5B6C813B83848121a08E0A61D453/tokentxns)
Only **42,000,000** tokens were distributed—**52 million** remain in the original wallet. Guess who that belongs to?

<img width="941" height="333" alt="2" src="https://github.com/user-attachments/assets/398220bd-b4f1-4672-b7f1-c6b9ba76e9fc" />

Let’s see where those 42 million tokens went:
[https://swanscan.io/address/0x57aD6664FA329aB2bdB21Dc00F46323A2ee58480/tokentxns](https://swanscan.io/address/0x57aD6664FA329aB2bdB21Dc00F46323A2ee58480/tokentxns) <img width="941" height="460" alt="3" src="https://github.com/user-attachments/assets/51e1170a-55bc-4152-8089-dc3bc4f652ca" />

After being distributed to just **30 addresses**, 6.9 million tokens remain. That’s how concentrated the holdings are. <img width="941" height="452" alt="4" src="https://github.com/user-attachments/assets/93468857-58fc-43d7-97fa-f20fdd7ad727" />

**That wallet has recently moved funds. Curious where it went? Feel free to investigate.**
Then take a look at the price chart: pumped and dumped several times, each lower than the last. Clear exit moves: <img width="941" height="466" alt="5" src="https://github.com/user-attachments/assets/e51ee312-1bd6-4919-af8c-04b1c983244c" />

To make it clearer—MEXC has delisted Swan’s contract!
[https://www.mexc.com/zh-TW/support/articles/17827791525151](https://www.mexc.com/zh-TW/support/articles/17827791525151) <img width="941" height="550" alt="6" src="https://github.com/user-attachments/assets/7f8c844e-5d39-4ed8-a518-847fd1b2ad2e" />

Still want to hold? The market has already seen through it.

---

## 3. Fake Tasks and GPU Abuse Are Killing Miner Rewards

* Do miners really calculate their daily ROI?
* The team keeps pushing **“Hello World”-type** fake tasks just to inflate GPU usage across the network. With higher GPU occupancy, miners get a smaller cut of the UBI rewards. This is plain exploitation.
* They even used their own top-tier hardware—H100s and L40s—to run dummy jobs, inflate utilization, eat miner rewards, and destroy tokens in the process.
* Fake miners running these:

  * H100: [https://provider.swanchain.io/cp/0xEf675CA43Ce25b2594079caCE98C7362733E1F5B](https://provider.swanchain.io/cp/0xEf675CA43Ce25b2594079caCE98C7362733E1F5B)

     <img width="941" height="531" alt="7" src="https://github.com/user-attachments/assets/28d5ca60-17e0-4129-a9d5-515b29023dae" />
  * L40s: [https://provider.swanchain.io/cp/0xEcA0D885E8f0b451D4638f1a89148cCc50318d00](https://provider.swanchain.io/cp/0xEcA0D885E8f0b451D4638f1a89148cCc50318d00)

     <img width="941" height="545" alt="8" src="https://github.com/user-attachments/assets/1bfd678e-1e43-4713-8dea-3a9267e49557" />

From the official explorer: Only **29,000** tokens are issued to miners per day, but their two high-spec machines alone destroyed **13,000** tokens—**31%** of the total! For a worthless token, that's an insane amount of waste.

<img width="941" height="462" alt="9" src="https://github.com/user-attachments/assets/fb63cdac-9aeb-4d0f-a720-c9c3b3fab4c1" />

* **Fake Tasks**: By looping tokens between themselves, they reward their own machines while pretending to pay miners. These recycled tokens fund more fake jobs—**a zero-cost exploitation loop**.

### (1) Token Reflow for H100 Tasks (burning hundreds of thousands per run):

<img width="941" height="550" alt="10" src="https://github.com/user-attachments/assets/c6d119a4-a293-4db6-9e49-6ba1140b1af4" />

### (2) L40s Token Reflow:

<img width="941" height="502" alt="11" src="https://github.com/user-attachments/assets/6a7b9ee4-9017-4f99-9f2f-9c611c3fff5e" />

### (3) Example of a Fake Task (buried deeply but found):

[https://task-audit.swanchain.io/detail/d09bfdf4-7199-4c2e-af50-183eb486e668](https://task-audit.swanchain.io/detail/d09bfdf4-7199-4c2e-af50-183eb486e668) <img width="941" height="1118" alt="12" src="https://github.com/user-attachments/assets/15196084-8dc4-49ae-9c0c-d5f8fb1e6fc8" /> <img width="941" height="1247" alt="13" src="https://github.com/user-attachments/assets/ef60b73a-50fa-41f4-b63c-3bf6c27d1ac2" />

**Hello World Task:**
[https://github.com/swanchain/awesome-swanchain/tree/main/hello\_world](https://github.com/swanchain/awesome-swanchain/tree/main/hello_world)

**They literally used a 4-GPU L40s setup just to run “Hello World.” Why? Because they have unlimited tokens.**

More examples:

* [https://task-audit.swanchain.io/detail/da18b828-252a-45bf-9327-6201effe2257](https://task-audit.swanchain.io/detail/da18b828-252a-45bf-9327-6201effe2257)   (4×H100)
* [https://task-audit.swanchain.io/detail/3753dc7e-616c-425e-acdb-4387050bdf8c](https://task-audit.swanchain.io/detail/3753dc7e-616c-425e-acdb-4387050bdf8c)   (4×H100)
* [https://task-audit.swanchain.io/detail/aa2d45c4-db73-4f07-aea7-53ba4df28aa9](https://task-audit.swanchain.io/detail/aa2d45c4-db73-4f07-aea7-53ba4df28aa9)   (4×3090)
* [https://task-audit.swanchain.io/detail/7fcbd124-06f3-43ad-a6e5-57347a804890](https://task-audit.swanchain.io/detail/7fcbd124-06f3-43ad-a6e5-57347a804890)    (4×L40s)
* [https://task-audit.swanchain.io/detail/d57bdf17-6057-4c98-8c2e-ce3902b0f235](https://task-audit.swanchain.io/detail/d57bdf17-6057-4c98-8c2e-ce3902b0f235)    (4×L40s)

Want to dig deeper? Here's the smart contract managing all tasks:
[https://swanscan.io/address/0x88f0c31c2cD9d5382d870a417dA144bACd19f027](https://swanscan.io/address/0x88f0c31c2cD9d5382d870a417dA144bACd19f027) <img width="941" height="516" alt="17" src="https://github.com/user-attachments/assets/d83d6e3d-a071-421c-9839-90c213e3fd48" />

---

## 4. “Burned” Rewards Secretly Taken by the Team

The so-called “burned” rewards and slashed tokens were actually funneled into team-controlled wallets.

* Original burn wallet: \[0x4Fe7dbE3A40F62c0a4119bF7A9592Bfd7e7C6b32]
  [https://swanscan.io/tx/0x50a831f450fb528ebf7960092e1bd6c4cb31f49dab54a8d0e889b18073977bc5](https://swanscan.io/tx/0x50a831f450fb528ebf7960092e1bd6c4cb31f49dab54a8d0e889b18073977bc5)

  <img width="941" height="616" alt="18" src="https://github.com/user-attachments/assets/8d1b8d6e-f663-4ce8-b747-22637e6c3040" />

* Secretly replaced with a new wallet (no announcements): \[0x2d38CbeA73475a4c21948F19a319c932Bb02C75c]
  [https://swanscan.io/tx/0xb7531f6091a82c55302f1e66eecd8f3593ac623ce951436bff84093ff1baccd5](https://swanscan.io/tx/0xb7531f6091a82c55302f1e66eecd8f3593ac623ce951436bff84093ff1baccd5)

  <img width="941" height="470" alt="19" src="https://github.com/user-attachments/assets/bc20d29c-25d6-4e2f-b085-7c76e30df1e0" />

Current balance? Over 3.64 million tokens. <img width="941" height="625" alt="20" src="https://github.com/user-attachments/assets/aaa11b81-de3c-4ac1-b269-6261daff84c6" />

What about slashed collateral and miner task rewards? All went into a black box. No one knows where or how they’ll be used.

---

## 5. Governance Is a Joke: It's All Centralized

* The governance repo is empty. Only a few stale GitHub discussions remain—most are over 6 months old, and barely commented on.
* The team writes proposals, reviews them, and approves them—all by themselves.
* Zero community involvement.

Examples:

* [https://github.com/swanchain/governance/discussions/9](https://github.com/swanchain/governance/discussions/9)
* [https://github.com/swanchain/governance/discussions/10](https://github.com/swanchain/governance/discussions/10)
* [https://github.com/swanchain/governance/discussions/8](https://github.com/swanchain/governance/discussions/8)
* [https://github.com/swanchain/governance/discussions/2](https://github.com/swanchain/governance/discussions/2)

<img width="941" height="881" alt="21" src="https://github.com/user-attachments/assets/9fb5e4f3-2b83-49dd-b4e0-ef197910988e" />  
<img width="941" height="785" alt="22" src="https://github.com/user-attachments/assets/46a0a49d-98e7-4c71-a1ce-7fe4a62fed4b" />  
<img width="941" height="800" alt="23" src="https://github.com/user-attachments/assets/9586cf8a-2abf-4e90-b761-412833bfcda1" />  
<img width="941" height="750" alt="24" src="https://github.com/user-attachments/assets/6778750b-3e72-4c66-ba01-c8748c03a321" />

**This isn’t governance. It’s a bulletin board. Most discussions go nowhere, and rarely involve more than 2–3 people.**

---

## 6. Team Split, Project in Disarray

Originally a collaboration between Canadian and Shanghai teams—now:

* The Canadian side has moved on to build **Nebula Block**
* The Shanghai team fell apart—infighting, people fired, core members gone
* Miner community is dead. Rewards and tasks were offline for days. The team said it was an “upgrade,” but it turned into a “migration” with no end in sight.

<img width="1752" height="865" alt="image" src="https://github.com/user-attachments/assets/2368845f-81e9-46da-8350-08058994b295" />  
<img width="941" height="1125" alt="25" src="https://github.com/user-attachments/assets/78345dda-b750-4be8-a0bb-dd7103df2169" />  
<img width="941" height="1231" alt="26" src="https://github.com/user-attachments/assets/53c2f24f-c945-4315-a04a-3898f02a7830" />

No other chain breaks down for a week and calls it **“diagnosis + upgrade + migration”**. All talk, no delivery.

---

## 7. Codebase Dead: Swan Is Basically a Zombie Chain

Just look at their core GitHub repo:
[https://github.com/swanchain/go-computing-provider/tags](https://github.com/swanchain/go-computing-provider/tags) <img width="941" height="558" alt="27" src="https://github.com/user-attachments/assets/91a9d2bc-1db1-4b54-b545-87738819fa9b" /> <img width="1678" height="830" alt="image" src="https://github.com/user-attachments/assets/1857fad8-f29d-47ed-a04a-68be09268136" />

No updates in **over 6 months**. No devs. No commits. No reviews.
How is this still called a Layer 2? It’s basically museum material at this point.

---

## Final Words: Get Out While You Still Can

**The reality of Swan Chain today:**

* Core team is gone—only one sysadmin remains
* Economic model is a black box, reward logic unclear
* Pump-and-dump tactics after 100M token unlock
* Fake tasks inflate GPU usage, miners exploited
* “Burned” rewards secretly go to team wallets
* Governance is fake, community silenced
* GitHub hasn't moved in half a year

If you're considering entering—**think twice**.
If you're already in—**think fast**.
Don’t end up the last one holding the bag.


