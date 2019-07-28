# CodeFunDo-Marauders
Secure Electronic Voting using Azure Blockchain


Voter registration
Every voter has to enter the following things-
1. Aadhar Card Number- (same aadhar card not allowed again)
2. Name
3. Current Address
4. Preferred constituency- (use nearest to current address if not specified)
5. Phone Number- for sending link
6. Security Question


Algorithm
Each block contains- hash based on Aadhar card number (to avoid matches), voted party (initialised to none), next block hash, vote count.

Every link works only until the voted party receives one response; new link (also means block or block override) generation is allowed only after permission from the constituency officer approval. (Basically Digital Signature)

Each constituency receives the vote from the voter, with a unique link sent to that voter only and sent only from the that constituency. 
Hash key being related only to Aadhar card eliminates multiple voter ids of same person. Also, the link requires a security question saved at the time of voter registration (only required if voter opts for online option).
Each vote is sent to constituency add at the end of the said constituency voting the constituency gets declared as a party’s constituency-

Hence new block is added to the contesting party heads, parties contesting elections are declared as the headers, and the number of seats 
Each party is winning is a public key. 
 

