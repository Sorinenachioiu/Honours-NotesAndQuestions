# Questions

## Querry sharing 
- What happens when there is an error in one of the queries? - what block do we have then ? 
- How can Research Groups do queries if they do not know anything about the database? Should there be an extra step before the query in which the Hospitals send to the Research Group the database schema? What alternatives would there be?
- Is the querry going to be automatically run on the Hospitals's part? (Is this a good idea? What if the query is malicious or might break the database?) -> Seems like this is not the case
- If not, then are the Hospitals going to receive a query/ file/ folder with the contents of what to run on their part and then run it? (This would mean that the system can be generalized to run anything from querries to maybe a federated learning system, by just dockerizing what to run) 
- Would docker mean that the system is less prone to attacks? How can attacks be performed while using docker ? 

## Threat models
    "On the other hand, we assume some or all research groups to be a malicious adversary. The protocol should retain trustworthiness even when research groups actively try to increase the system. In this way, valid transcripts of data transfers can prove the legitimacy of research performed and aid in the repeatability and transparency of research. Research groups may actively try to gain information shared in data transfers where they are not the intended recipient."
- What does "research groups actively try to increase the system" mean? -> ddos? 

## Blockchain organisation
- Only Board members keep all the blocks in the blockchain? -> Seems that everyone get all the blocks
- Consensus is achieved between Board members ? -> Seems like so.

## Descentralization achieval
- Is the system really descentralized if the Board Members still have so much power?

## Authorization
    "The board maintains the public ledger and authorizes H and R willing to join the ledger."
- How are H and R selected ? How can we be sure that they do not have any malicious intent at all ?

## Encryption-wise
- Only the QUERY_KEY and RESPONSE_KEY are encrypted with the Board Member's public key ?