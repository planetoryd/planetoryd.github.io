---
title: Problems with blockchain and WoT
date: 2021-02-20 14:32:04
tags:
    - trust
    - blockchain
---


# The inherent centralization of blockchain

> Sybil attack: basically, the attack that tries to break a reputation system with fake identities.

Blockchain is known by its trustless pattern. To prevent some common problems, like sybil attck, they use 'value' or stake as the way to keep the system working. Whether some coin uses proof of work, or proof of stake, one's influence on the network is always proportional to his wealthiness. The word 'influence' stands for the probability someone is chosen to add blocks. The rich, as a whole, usually have more probability than attackers overall. PoW uses a method of hash brute forcing to allocate probability of being permitted to add a new block to the chain, among miners. The more hashing power, the richer a miner is, more precisely, the more money thrown into mining. **There is no difference between PoW and PoS, except that PoW consumes more energy and distributes wealth more easily when starting a coin.** Mining on PoW, the miners burn the money, rather than stake like PoS, because hashing always costs money. Supposing hashing doesn't cost money, it has no effect, obviously. As a result, the network naturally centralizes. The validators that maintain the network are the minority, while the system can't sustain without them. The special characteristic of PoW is that it burns real money, in contrast to proof of burn. IOTA, which claims to be decentralized, uses a DAG instead of a blockchain. It requires every node to validate other two transactions when doing a transaction. Actually I think IOTA is a scam, and is vulnerable to sybil attack, as it has a coordinator node, ie. single point of failure. I also have a similar idea of using a DAG. They introduced PoW to solve those problems, which I think is non-sense. A feasible way is probably to associate the weight of a node in a DAG with the wealthiness of the transaction sender. Thus, the system sustains itself trustlessly, as the rich always have more influence and are willing to keep the existing order, the distribution of wealth. So, this approach still favors the rich, centralizing the network, which is meaningless for me. Is there any way without letting the rich have more influence to build a crypto-currency ? I don't know, but surely without such a system dominated by the rich, no one would agree to keep that distribution of value, or wealth.

You may argue that blockchain isn't necessarily to be used as some crypto-currency. The fact is that there's no way to reach a consensus without such a capitalistic algorithm, in a decentralized way. As I've said above, PoW is equivalent to PoS, and PoA isn't decentralized in the first place. However, blockchain isn't the only option towards a decentralized network. Years before blockchain, there had already been many networks for sharing files, some of which implemented Web of Trust to prevent spam. **Web of trust is also used in GPG or PGP**, with tens of thousands of users. Trust is a natural way how people organize together, since the appearance of human being. Accordingly, blockchain is capitalistic, which establishes consensus via private ownership. It is like a coincidence how these networks organize like a real world society. The nature of WoT is that everyone has the freedom to trust others at one's own will, which is truly decentralized. Moreover, consensus, in the a broader sense, is not achievable for people having different belief. WoT respects the freedom of not achieving a consensus, for anyone. The 'consensus' here means the single source of truth. It can be the distribution of wealth, the allocation of domain names, and so on. That's the consensus. I agree with the idea of 'blocklist' in ZeroNet. A blocklist is subjective. Nobody's freedom or opinion is ever compromised. A notable difference is that trust is a kind of value that is not tradable. Tradability creates unequal value distribution. Unequal distribution gives us the opportunity to establish consensus. Trust is static and subjective, implying it is naturally censorship-resistant and scalable. Nothing would happen even if half of the network is banned, which is common in some censored countries. The same thing would cause a hard fork on a blockchain.

I didn't say blockchain is bad, but undoubtedly blockchain is full of scams and even claimed to be so-called 'Web3.0'. That's just hilarious, for some capitalists and even some scammers among them to be the inventor of that thing. They also set up some DNS services like 'Unstoppable Domain' and ENS. Imagine how they sit at home, collecting money every time a new domain is sold. Decentralized web should be censorship-resistant, first of all, thus isn't a sub-project of Ethereum or anything else.


# Does blockchain really incentivize creations

> Steemit is a blockchain that rewards writers based on readers' responses, which is often seen as a new way of 'incentivizing creation'.

**Steemit** is a typical example among such blockchains, which rewards the writers every time they got a like. As everyone knows, the coin market has to have people buying it to have value. They faced some financial difficulties as written in their wikipedia page, which is what I expected before reading. To make the whole 'incentivizing' system work, they have several choices: do nothing and wait the capital to run out, start a **Ponzi scheme**, or let the loser writers to pay the winners who got more likes, or the most common one, **run ads** just like what centralized web does. They have probably chosen the last two options. The former is a **zero-sum game**, which doesn't generate any value unless the readers pay. Similarly, the latter is actually paying by the advertisement companies, which makes no difference from large corporations such as Google. As we know, the ad-driven business is broken, so the whole blockchain becomes nonsensical.

Donations ? But, **why donations with extra steps** ? The business model driven by donations does work, which is also what I recommend to do instead of running such a blockchain. Even if they set a paywall, the quality will be soon shared on another decentralized network, inevitably. This is why I didn't mention the method of paying by readers, because it doesn't work, even without a dweb. Therefore they didn't use a paywall, and the sole purpose of the blockchain is all about paying with a bunch of complicated steps, redistributing a part of the money to the writers, another part of money to the investors, and the final portion becoming the revenue of the Steemit corporation. None of the ways runs the so-called economy (except for donation which doesn't need a monopolized blockchain payment method). The blockchain only blinds your eyes and **cuts down the rewards of writers**.

What shall we do with blockchain ? Blockchain does create an economy if used properly. The works of writers can be copied, and should be copied, which is not a proper target of incentivizing. However, there're things that can't be copied, such as transfering data, FileCoin. Those are mostly **services, where blockchain really suits**. Other tasks like searching have already been tried and implemented with Web of Trust in last 20 years. WoT is more decentralized and more tolerant to network failures, as I wrote before, but it is relatively small-scale and community-driven. Today, things powered by money run faster. According to my observation, there is a such blockchain. I believe it won't work currently, since they don't even have a dweb with enough content.

# Co-existence of blockchain and WoT

The network can't be totally trustless or moneyless; it has to be like a reality society. Trust is what we get from near friends, which is long-term and limited to a few people. Every individual is responsible for its own ledger of trust, while a blockchain is a global shared ledger. People do need some group to represent the will of the majority, in contrast to the anarchy of a pure WoT. It is also similar to the governance of a site which has a group of people owning and maintaining the site. The reason why I was against blockchain is that it was overrated. When the management of a site goes off, we can simply purge that site and adopt one of its competitors. There's no cost in setting up a site and advertising for it in dweb. The recommending algorithm naturally promotes the truly quality content, or sites. Finally, we don't have scaling issues whenever a site goes viral, even without extra maintenance. The competing environment makes such "centralization" acceptable.

However, the reality is that many users and investors are still undereducated, fooled by fancy whitepapers from blockchain companies, which isn't a good atmosphere where the blockchains compete for governance. In the future, the project will probably take over blockchains in most fields where we don't need a global consensus, destroying the dominance of dweb by a single blockchain. Those blockchains aren't really needed by users, but they hyped and created that non-existent demand. They do know the demand doesn't exist and the users are tricked, so their sole purpose is to get money out of the market sooner or later, which is the bad competition environment I said. Solutions without a blockchain are generally more efficient, for like a decentralized forum, social network, and even name service, as they don't have to get a consensus. As developers in this field, they do know these solutions. For the sake of profit, they "discover" every possible area that might be related to blockchain and create nonsensical blockchains, along with fancy websites and shiny whitepapers.

# The evolution of trust

> What is the fundamental difference of the trust-based decentralized web ?

Today, before our dweb have been developed, we still use those services from large corporations, Google and Baidu, playing the most significant roles in the internet of the world and within China. Both have been criticized a lot till now, and kept going well with their business for they have already monopolized the market. After some incidents, a few started to use alternatives, which usually lasted only for a couple of months, and the majority forgot what the corporations have done to them. The logic behind the scene is simple, few alternative search engine survive for the lack of capital as the advertisers tend to cooperate with those existing winners. Baidu is actually worse than Google. Its cloud storage service (**Baiduyun**) was thought to be overpriced and moreover they have attracted many people to upload their own files, but afterwards, they are required to purchase premium plan, or they will be throttled to a unreasonably low download speed. The anger of people soon emerged and lasted for a long time. They didn't do anything until the public opinion heated again and again. In the end, the speed limit is raised from 2KB/s to 100KB/s, which almost succeeded in silencing the majority. The majority has no weapon to defend unless the situation is critical, their files are almost hijacked, and they have to use it for other people, relatives, friends, and the company they work for use it. The better one, Google, is actually bad for the adoption of their future competitors, the dwebs, on the other hand. The cost to use an alternative is too high, and the cost and risk of running an alternative sustainably is not affordable for the investors. The true demand of people is the files on the cloud which the company has successfully monopolized. Under such circumstance, a new company who wants to challenge Baidu in the field of cloud storage has firstly to get enormous capital which is hardly possible， secondly to advertise which is even more unlikely since Baidu has no reason to support its competitor. Many brands are trying to offer cloud services along with their hardware products. This works, but only in a small scale, unless they can conquer the market like how Baidu did in a short time. Baidu did that by asking the government to ban Google.

What does 'trust' mean here ? 'Trust' means to trust something and start using it, as a process. The process of 'trust' also comes with risk and cost which includes the loss of the chance to use other products and resource and the convenience of migrating to another product. When you start to use Google, you trust it, and the cost of trusting that is almost zero for it is shipped as the default search engine together with nearly every device. The time you realizes the flaws of Google and tries to find a new alternative on it, the search results will soon cool you down, because it takes time to check every new search engine and you are also anxious whether it will last or just disappear days later. In the end, the users are simply afraid of trusting new things.

An easy solution is to have a **federated** architecture to solve such trust issue, lowering the cost of deploying and adopting new entities of some service, and the cost of being trusted. Typical examples are Mastodon, and Matrix network. The networks are formed through the connections of users, and the data is exchanged within the network of friends. From the perspective of result, they haven't gained sufficient users they deserve. Because they can't compete with the centralized monopolies without overthrowing the broken advertisement economy. The abolishment of ad economy can only take place when the network itself is appealing enough for the users, in the first place. Federation of applications is like running multiple Googles, and keep them in fair competition because we have an shared entrance where users can choose one of them freely. Each service provider in a federation follows the same protocol, so that the behavior and whether it acts maliciously can be automatically examined by the software which doesn't cost users' efforts. Hence the cost of trusting is reduced, with federation.

When trusting takes near-zero cost, the competition mechanism truly works. In The Network, we have the **WoT**, which is further optimized with automated trust, requiring no user interaction. Therefore, the cost of trust in WoT is relatively low. The sites, and blockchains are the things that cost much to be replaced with alternatives. Although things should differ from the centralized web for the withdrawal of ad-economy, whenever a site's management is corrupted or hacked, it takes time to move onto a new site. A solution is introduced for sites that are more community-based, which is to give the power to the WoT. As a result, the site is less dependent on the development team, and as robust as the WoT. The evolution of trust is about the three stages mentioned above, from high-cost to low-cost, decreasing the difficulty of purging bad actors in the competition. The cost of trust lowers, and the trust itself decentralizes.

WoT is a 'federation' of users, and the entities are smaller. The services in such federation are all provided by users themselves, on each device of them. The difference is that WoT forms a network, while federation is only a list. A friend of your friend is probably also trustworthy, so 'trust' forms a network. Once again, it reduces the cost trusting, because we don't need to trust more people manually since our friends have already done this for us.

Blockchain is a special kind of thing. The **blockchains** themselves are the entities to be trusted, and the smart contracts on the chains inherit the trust. So, blockchains can be trustless inside. Services other than Google, such as DNS, the authority of naming, becomes the authority as we trust them. Every browser or operating system has a default DNS server, which is also a part of the global hierarchical DNS system. Supposing someone replaces the DNS server with his own server and tries to advertise for his server, a few people may try it, but soon the attempt of taking over the authority will fail. The cost of trusting and using the new system is too high, which is modifying the settings of DNS server, what normal people won't bear the inconvenience to do. Also, people don't expect others to do the same thing for the same reason. Such an authority factually monopolizes, since it has created enormous cost of trusting others. The cost means the total price we need to replace this monopoly, which is obviously hard. In contrast, an authority in a positive competition environment may perform better and is unlikely to be evil. An authority doesn't necessarily monopoly, although most daily internet services are.

In conclusion, the cost of trust is reduced with technologies by automation, through a better way of communication.

## Forking a site

Many sites are platforms, which have the characteristic of the heavy reliance on popularity. A platform site tends to form a monopoly after conquering the majority, and the competitors can't bear the cost of changing users' habit. Platforms, as the name implies, they hold items submitted by users which will then become their means of sustaining the monopoly. This is a kind of trust issue, because the migration of the items that have been submitted is part of the cost of trusting new entities. The monopoly has no excuse to give out their user data, which will never happen in the centralized web. How does the dweb solve this problem then ? We have the client for every user, and that's how we enforce sites to share data through **cross-site** interaction which allows us to build a new UI for an existing site, a new system of content promotion, or a totally new site, etc., with original user data untouched. This completely destroys the barrier of competition that almost exists everywhere.


## Web3.0

> What web1.0 and web2.0 are doesn't matter, and web2.0 should be what we are using right now.
> The term web3 has been used and defined by many, such as blockchains, but here we are to redefine it.

What should Web3.0 look like ? A market of data service, or a market platform of articles, or only blockchain itself with some shiny smart contracts ? The first item is FileCoin, a project based on IPFS. As said above, market, or blockchain causes centralization, which is not practical for a censorship-resistant network. Therefore, Web3.0 can't completely rely on FileCoin, which proves FileCoin itself can't be Web3.0. The second one is Steemit, a DPoS blockchain featuring its blogging platform, rewarding writers according to the upvotes from readers. The first thing I wondered was where the money came from. Most common business model is advertising, like what those big corporations do. Another tricky way is to let the speculators pay the bill, or to let the losers in the writing competition pay the winners. The former seems to work, as a Ponzi scheme, but it is uncertain to last long. The latter needs writers to 'invest' some money first, which is actually an option when you register an account on Steemit. Of course, you can also choose the manual review way, with some delay. There's no other way to keep the whole thing work, thus they must be advertising, making no difference to those big corporations. The third is Ethereum. Let's skip this, because, how can a blockchain be Web3.0.

### Capitalistic advertising

**Advertising, capitalistically, is evil**. An extreme example is in China. PuTian hospital, a private hospital who invest massive capital into advertising with Baidu, another dominating Chinese search engine who sorts the search result by bidding. There's no difference among those companies using advertising as their business model. Either show some annoying ads, or more implicitly, change the order of search result, favoring their sponsors. The whole system is capitalistic. The system inherently promotes those who are willing to spend money and more money on advertising, and drives out those who aren't. Other side problems, tracking, surveillance, etc. automatically emerge under this system. You might argue that, the advertisement payers enable us to use services freely, and support those content producers. People aren't satisfied to watch ads. How can it be a source of income for content producers. There shouldn't be ads in the first place. The more money an advertiser invest, the lower the product quality is, and you don't find a good solution when you search something, either. There can be good advertising under WoT with zero-cost.


### Domains

> Domain name, and this also applies to other names, like user name.

DNS is the centralization of naming, which is controlled by an organization. Each site has to afford the cost of maintaining one or more domains every year, and they have no choice for the absolute domination of DNS. People also buy domains that they don't really need, and speculate whenever others truly need them. Is this a good system ? Shall we sell domains ? Who should own some domains ? Instead of selling domains to who have the most money which supports the capitalistic advertising, the dweb will allocate domain names to those who need it, based on WoT, which means that if your friends and friends of friends trust you and believe you deserve the domain names, you will simply get them. The names should be given by its users themselves, but not by how much money and value the name holders *directly* produce. The blockchain name providers are like the DNS, acting as an authority, which has no difference from the centralized naming service. Therefore, blockchains in terms of naming can't be the Web3.

### Conclusion

The real world have been controlled by capitalists, the top elites. The internet should belong to its users, the proletarian. Whether for communist countries or western countries, the unbiased freedom of speech is always a driving force of innovation, and reformation of the society. The ranking algorithm can be biased by the rich with enough voting power, fundamentally. A blockchain has no way but to favor the rich in every aspect, including content ranking, or it would be vulnerable to sybil attack.

> We must seize the means of communication
> —— Edward Snowden