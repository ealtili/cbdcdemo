# CBDC Demo
The CBDC Demo was created by Digital Asset using Daml, the smart contract language that simplifies multi-party workflows across infrastructures, the cloud, and multiple persistence layers. It was originally created for a forum of the Organisation for Economic Co-operation and Development (OECD) on central
bank digital currency (CBDC) in the fall of 2020.

The demo shows how Daml supports core features of CBDC, addressing these key requirements.
- Tracking: Daml supports auditing and tracking transactions and storing contracts along with the history of each transaction. Observers of a Daml contract can be customized to allow for more transparency and visibility.
- Controls: An authority controls who can own money at a programmatic level, for example, to comply with restricted lists (e.g., OFAC).
- Safety: For simple or complicated transactions, Daml can establish specific rules for money transfers that must be met atomically (e.g., all steps must be successful) for the transaction to occur.
- Interoperability: Daml would permit a CBDC system to bridge different ledgers and technologies.

Requirements are docker desktop and at least 8gb memory
Installing and Starting
Make sure docker is installed and then run
- docker run --rm -p 3000:3000 ealtili/ex-cbdc
