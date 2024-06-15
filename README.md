# Zksync-rat-barn

First, before discussing, let’s review the officially released NFT (LIBERTAS OMNIBUS).

Twitter: https://x.com/zksync/status/1691808445224087555

Eligibility criteria for NFTs:
Eligible addresses include those that interacted with at least 100 ZKSYNC NFT collections prior to mainnet launch and before July 12.

------------------------------------------------

This group of front-running involves official members using contract privileges to mint NFTs to their own addresses.

These addresses do not meet the officially announced criteria:
Addresses should have interacted with at least 150 ZKSYNC NFT collections before July 12. However, these addresses did not conduct any NFT transactions before July 12 and directly minted NFTs instead.
(LIBERTAS OMNIBUS) Contract Address: 0xd07180c423f9b8cf84012aa28cc174f3c433ee29


![dc](https://github.com/Easy8866/Zksync-rat-barn/assets/109504013/f9eb9add-2fd9-4d3e-b831-b4839a1d3626)

**Group A**

This group of addresses utilized contract privileges to add themselves to a whitelist. These addresses were directly added to the contract and proceeded to mint NFTs without meeting the minting criteria.

The following addresses were identified through a Dune query, and there might be a few false positives among them: https://dune.com/queries/3113136. The logic used was to identify addresses that had not conducted any NFT transactions before July 12 but still minted NFTs (LIBERTAS OMNIBUS).


![1](https://github.com/Easy8866/Zksync-rat-barn/assets/109504013/a54a0e53-ce85-4629-afe0-a1503f86c83c)
![3](https://github.com/Easy8866/Zksync-rat-barn/assets/109504013/f5d50013-ef20-44e5-94fa-2ee6f1a2f28f)
![5](https://github.com/Easy8866/Zksync-rat-barn/assets/109504013/0edf5e86-fd09-4eb8-8559-2128717bed9b)



**After minting the NFTs, 270 addresses sold them on Element to make a profit.**


![2](https://github.com/Easy8866/Zksync-rat-barn/assets/109504013/edd60a4e-f33f-4819-95dc-cf90dc646d07)
![4](https://github.com/Easy8866/Zksync-rat-barn/assets/109504013/18bb19c0-6d68-466c-8a3b-c58f27654304)
![6](https://github.com/Easy8866/Zksync-rat-barn/assets/109504013/22566115-589e-4e34-8559-a21f6559ca6e)

https://docs.google.com/spreadsheets/d/1x0S87uF6nS8ftrPFHkfaYqqaE0x6ekUNiwv5SL-S63I/edit?usp=sharing

Among them, 79 addresses received a total of 740,000 ZK tokens as an airdrop.

-------------------------------------------------------------------

**Group B**

This group of addresses used contract privileges to mint NFTs through the contract creator's address and subsequently received an airdrop. 

The address that created the (LIBERTAS OMNIBUS) NFT contract is 0x526a599f58f1e5ba4a1c5c14c723698b2a7b0791. This address used contract privileges such as `batchMint` and `safeMint` to mint a large number of NFTs to various addresses it controls. I have categorized these addresses into two groups.

![合约batchMint](https://github.com/Easy8866/Zksync-rat-barn/assets/109504013/053a41a8-b34c-42c8-b272-d01635d68330)
![合约safeMint](https://github.com/Easy8866/Zksync-rat-barn/assets/109504013/5b21e1f8-2d94-4f66-b329-a954242dde72)


**B1 safeMint**

![合约batchMint 01](https://github.com/Easy8866/Zksync-rat-barn/assets/109504013/962d9a5d-99bb-439c-8ce4-6ce5461f65ab)
![合约batchMint 02](https://github.com/Easy8866/Zksync-rat-barn/assets/109504013/63da8efa-a03f-4d53-ad1b-3195f4a9125b)


https://docs.google.com/spreadsheets/d/1ppjwUBEA7E5R_MJ5NoON9OneTpjQUEtYDwSvXwtvO5o/edit?usp=sharing

**After minting the NFTs, 65 addresses sold them on Element to make a profit.**

```
0xf173be26aeb4c89a535d18eba85fd3eb093a3677
0x0fbfc1e4d011707e7b9f5f1125b3773454dfcaf2
0xa38e67f8251e69e6911029e23498b33150d33331
0x25b691a40f8d349385fe8e21d01a384542803389
0x1481589fe956da324063917cd08f94118b4b4216
0xb453bbaa43ba0358a9fe54da72006f9def83815e
0xf2863ed6a38614688a4d96cf2b6a2f58dfbaf216
0x5a8429cb0688a7c79880d304ef6ed59a028cc7a2
0xdace1776c22f3589686934fffd9adfb62ffc3eb6
0x75ef817c63d4e468323db2178480e9405ededeec
0x09a001705065a5b991cc806948300b115266836c
0x04128317261b5ab669372f990580fac7e5c3937e
0xbf09d4e2bf1cc4a3090ff10a1c4f70bdc21047fa
0xce37e163e966dc88228006e84bf2cd07124441c7
0x717a922742294081bfe09b5e849696de04b5e89e
0xc479b19f7b4e979d863c1e1738e4ac1b666fc998
0x3c0df91b1fab35453589275fd66b3a3d82262dce
0xada1c4aeb897658dae86f9e3dd371ec5e573f19e
0x99c08388c474c10b06574bd0be8e1656a1d25c6e
0xd6f29c10900fab7898d7f7f565f3f1b9dc8e60f5
0xa0d4dbe68a73b222ba34bb663d34960b11c0b8c7
0xe417c2de10d4d49bc80203882b48227cffa709dd
0x85bdb156b8126458a2e9101d150a75c1c156f460
0x46d71cdaec30e0ee6c79fc98b7695bfab17e27d5
0x641d8d0caffca8151cc765ecb7d405483071038a
0x21c6a44c4b92e40100df57b8ce21ea75a6b9cb98
0x4b01f6ef1cbaeb523e3aa92f218fcb2fc6a0f9c3
0x029e262645642f047f98317a4fe7710e3466b0dc
0xd942f09e3309465d6243acda952a5705c07c0416
0x86d294bc324bde8cd74b84bec960c3e57f632955
0x7c8068adfffb5c19e57825a05c9498f68a9b7d02
0xa9df2c70e34328f4badc91537cca5fdcc9ad101a
0xabe95ae9c57169e6edcd8e1680599ff76f956ad9
0x747a35410291837da25b76d92983f28e238a011a
0x079ae366983c33c3a36a62f20fba6ddf1b410be2
0x1ee214fb3320e26e497c548977b0246de2611492
0x45a6404060de393322ff0be4120a6d4f0397a048
0xbc154765f9c50d54871fd672ebbb7fb72824e702
0x5418ef18d35df0df5bf53c64509d21eed2f80d04
0x5c183ff412016d51e66071bdcb8057821feee035
0xfe393bb8185c35824bbf9e741760e6c87915cb83
0x136c28ceb02a3e6919a6f86b7556d98de2d70212
0xf9230b76f62c627e7d1545922ace104f89c90687
0x08d9be8b19219b10b85005423ea6f9217af9712c
0xa75bb3b7c8b67866700b74163e5c1bec188bb54c
0xf264dc653e5d0d048fbc7c6e16412f539aec7f4a
0xd1a230cf58b12c5b5093d8ec083275d1fcf8aaca
0x311efddb09719abc088f876723ee3b730cbdbfed
0x15343468b7e670fd0f9736c11eefa202ed978dba
0xef45c077d0fef073062f843f4f96f2ed35ae273d
0xbcd8ece7efd05d940b6f73c33b77779d185f2897
0xd637a55cee087de583a91ceba69902c872aa98da
0xc403ffeff26fe3dd2c9f0e74ec5869c58b29cf4c
0x45f78881976f28af8f430e715a4d827834590198
0x23a501684de7aaef8cf63e28b579c5a9aa88bc22
0xe34e54cbd99f14e211f7a5d01eae81b8adbca2f3
0x0b635d49fbf2abe8e689388339a3117e7061b239
0x1ca538794482cff268f65c7dd6f85d1831996457
0x5fb034eb49e27c936d5dcebdaed7301c3c161eae
0x93ccc63a61329fcc3de1e0099349b375a60bdbb2
0x9d4e353574758d7c03396425b2e2f0a4b8ef7258
0x392222fc1585e8a414bf9540fb25fb5eec5e874f
0x9cd128494352cb1378e8d2eabf98539beaea24cc
0xe66b4e91cbaf9f318351f34dbb29fbea9f29d669
0x9fdf89c95d8db7754a916b519771c69d67eefc4c
```

**22 addresses received a total of 412,738 $ZK tokens as an airdrop.**

```
Address	                                   zk Amount
0x1b6aa23a4de4cf66303386de2dfcdae29c7a43da	8141
0x69a54cf9acadab098c35f6b0020a606a528cf663	3237
0xd6762af75b32d487dcb68f29ea802a4ea586497e	1532
0xc7be722a0227511769e683c4db5c511e8f38e2d8	36859
0x232cd218b462bd9496e0cf4e7b02eb30cf0f71ea	1022
0xb81e594cf546360dbcca737c2ca01ff9b3f3461b	1371
0xad24ff5b503be5b6dd3936f842a252b0843ab808	1054
0x416188cb4623cc6d2204b79442d44b72a997c4e1	1748
0x04128317261b5ab669372f990580fac7e5c3937e	4003
0x96e6dafdf012b9ede6ad50c7d8ee1e656a85dd60	100000
0x591943d3f9a0aeb3e349d386aa7a87a2f6556a1b	5570
0xbf09d4e2bf1cc4a3090ff10a1c4f70bdc21047fa	8550
0xbffdf4ec5baf9ab4ad9574ae643be98aa8dd4cb7	1351
0x0090c1b80986f514020e8592d5a9ba04ac1d7049	1293
0x1654dda0ad1e0f0db485e1815c707ba8530e715c	943
0x3429a18d911d528b035a768e0ecf66f3d7f8deac	6906
0xeae5a1314509d4e1fb0066e7b87df8092fe073b3	76934
0x82d313f325b3c9b63502bffe9c01361037086e99	100000
0x5464912b966384bf6fb4222a6eca6013d99d6341	35038
0x614cd70186e1131a7e93a39cf7a61df99e63e8b3	3726
0x9fdf89c95d8db7754a916b519771c69d67eefc4c	10614
0xad75835a3581046e639bd19e98011736df4de861	2846
```

**B2 batchMint**

![合约safeMint 01](https://github.com/Easy8866/Zksync-rat-barn/assets/109504013/5019bd0a-1825-4c29-9fcc-860bc5ee2108)
![合约safeMint 02](https://github.com/Easy8866/Zksync-rat-barn/assets/109504013/459a8359-4bc6-4789-b605-b339a9dcf917)
![合约safeMint 03](https://github.com/Easy8866/Zksync-rat-barn/assets/109504013/e09ae4f3-37d7-4549-a557-da81991048ac)


This group of addresses is very large, and I have placed all the data into a Google spreadsheet.

https://docs.google.com/spreadsheets/d/1TnaSdzl6No_HinEZrSpBdZ_gqO-4esjV-EhGszj_XxY/edit?usp=sharing

*The NFT contract creator used contract privileges to `batchMint` a large number of (LIBERTAS OMNIBUS) NFTs to 9,871 addresses. Out of these, 4,685 addresses received a total of **43 million ZK tokens** as an airdrop. Even more concerning is that 109 addresses each received the maximum of 100,000 ZK tokens. This is a significant case of internal abuse for acquiring tokens, allowing the team to profit early without waiting for the unlock period.*

These 9,871 addresses undoubtedly sold NFTs on the market to seek profit. I will skip the data filtering process for this stage due to its complexity.


-------------------------------------------------------
The following addresses are associated with official members.

ozhar
Address	  ZK Amount


0xaafcf96120956faf6b702fba6d3a732576c6247f	76179

0x204495da23507be4e1281c32fb1b82d9d4289826	79861

0x75a58B772178F933C3597AA170fbAF7717456683	52816

0xc40fb1572f6112522ef238e8958631651a9b2f1e	18858

0x842054ead81735295b89e2af48387659fe2ed6de	1509

The following addresses have funds originating from the aforementioned addresses and are their affiliated addresses. They all possess (LIBERTAS OMNIBUS) NFTs, and they did not meet the airdrop conditions but were added to the whitelist to mint NFTs.

0x3830254cd76c134f436fe09af83b39baac0e1b03

0xb6dec9a24a6294121a152810fecbe6b334a26b27

0x2dcd860489cd099fb966d1729f890b8c5c997908

0xb435a754363d2807aa8addddb44f758b5a76a71f

0x2dcd860489cd099fb966d1729f890b8c5c997908

---------------------------------------------------
Bxpana
0x09d8270a1de38b53df1f47dec27f377ce145115c

Subaddress
0x7ffbda77afc7d11f5d14201faaf10d12cc94ff08

0x5a930b098ed8d58dd4590577af85a8e864a8f6fe


albicodes
0x158d6919f02657c2d19041693cb58daaa201f367

These two addresses also belong to official members. They possess (LIBERTAS OMNIBUS) NFTs and did not meet the airdrop conditions but were added to the whitelist to mint NFTs. I won't list the remaining official members' addresses and their affiliated addresses.

---------------------------------------------------

# Based on the above evidence, it is evident that the ZKSync project is plagued by internal corruption among team members. The core issue behind the uproar caused by this airdrop is the lack of transparency in the airdrop rules. To cover up the internal cheating addresses, many legitimate users were sacrificed. In December 2023, I disclosed a scandal involving a former employee, Seb, who was the DeFi ecosystem head, and the ecosystem project Syncus DAO. Seb promised large ecosystem airdrops in exchange for returning some of the tokens to him: https://x.com/Easy17182589/status/1730980103361077391

