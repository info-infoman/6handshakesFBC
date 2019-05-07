# 6 handshakes FBC
protocol 6 handshakes for FeedBackCoin
![Six_degrees_of_separation](https://upload.wikimedia.org/wikipedia/commons/9/94/Six_degrees_of_separation.png)

In general, the essence is this: according to the theory of 6 handshakes, each person is connected through his relatives and friends with all people on earth through 6 levels.
https://en.wikipedia.org/wiki/Six_degrees_of_separation

This theory can be applied for the exchange of transactions within a peer-to-peer network based on the account tree of the XCN and FeedBackCoin cryptocurrency proposed in the protocol.
It sounds tempting if you imagine that you can do without the use of mining, commissions and blocks to transfer transactions.

Important this is not Ripple, credit lines are used in the Ripple, here only the transfer of transactions and synchronization

# Primary coin distribution:
I think the optimal distribution in this system will be the same principle - through friends. Suppose you are a developer and initially all the coins you have. Then you agreed with your friend that you are organizing such a network, then you and your friend agree on a deal, and give him a part of the coins in exchange for the goods. Then you attract other friends to the network, and your friends to other friends, and thus your coins are gradually distributed over the network in exchange for real goods. At the beginning, the cost of coins can be low since there are only two people in the network, but later, due to the increase in the number of friends and friends, the price will inevitably increase as the amount of coins initially limited.

# Sending positive transactions through friends, friends of friends, friends of friends, etc ...
Alice sends 6 friends her transaction to Bob, her friends send this transaction further through 6 levels. In the end, if the network trusts in 51% of Alice’s transactions, then 4 out of 6 Bob’s friends will send Bob this transaction and Bob will know that Alice has paid
Of course, this is a purely sociological graph theory. As far as I know, Microsoft and Facebook successfully tested it.
here you can only trust your close friends and relatives

For you to be deceived, the malefactor must deceive your friends and friends of their friends and the friends of their friends and friends of their friends and friends of their friends. Total if you believe  theory  about 7,000 close friends.
This will remind you of a neural network where a node can adjust the weight of messages for its various friends

# Negative transactions(in FeedBackCoin)
Negative transactions should  destroy coins on the principle of 6 handshakes too: Alice sends a negative transaction to Bob, this is a multitransaction where Alice puts an input: The number of Alice’s coins sent to Bob, and the outputs: 0) Bob’s address that debits coins and exits (in equal proportions ) for charges of debited coins where Alice indicates the accounts that she has in the account tree(XCN). If Alice has fairly drawn up accrual exits, the network will accept this transaction and the transaction will reach Bob.

# Information transactions
The physical exchange of information about transactions between trusted nodes can be performed without direct physical communication between nodes and without prior exchange of secret keys. It is enough to introduce the concept of an information transaction between close nodes, for example: Alice wants to inform friends about new transactions that came from a friend of Bob, while she is not physically connected to her friends, for this she sends a special transaction (information) to the network. In the inside of an informational transaction, Alice packs information about the transactions that Bob gave her. Nodes that are not Alice's friends, but who are directly connected to her, can transfer this transaction further across the network (without applying the contents of the transaction to their account tree). Having received such an informational transaction, Alice's friends will understand that the informational transaction has been transmitted from Alice and will apply the transactions that are contained within this informational transaction. Thus close friends can exchange messages without direct contact, indirectly
This will create some noise on the network. But will not allow scammers to fake messages between Alice and her friends, as Alice's friends, it's enough to know Alice's public key.

# Decentralized automatic software update(https://github.com/info-infoman/Android_AUW_launcher)
In the same way, through information transactions, you can organize the exchange of automatic software updates. If 6 friends tell you that they are now using this version of the software, and you are financially connected with the rest of the world only through these 6 friends, then there is no point in resisting and not applying this update.
