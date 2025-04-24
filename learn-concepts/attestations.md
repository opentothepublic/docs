# Attestations

With OTTP, all attestations are linked to your OTTP ID, instead of an individual wallet. This allows you to update your account or remove compromised wallets while maintaining the integrity of your attestations.\
\
Your OTTP ID can then be publicly linked to any number of things (wallets, Farcaster, Lens, etc.)\


In case of compromised accounts, all attestations made with OTTP are revocable using your recovery method, allowing you to remove attestations after you have regained control of your account. (note: there will still be a record of these attestations, but they will be marked as “revoked”)

\


#### Types of onchain attestations

* Projects - Create a project to which you and others can contribute
* Proposals - Propose a set of future work, allowing others to give feedback, show support, and contribute to.
* Contribution - Any discrete segment of work.
* Verification - Saying “true” about any other user’s attestation.



#### Linking

Below are some examples of how linking can be used within attestations.



**Contribution attestations** can link to **other attestations.** Linking:

* a project, to show it is adding a part of this project&#x20;
* a proposal, to show it is fulfilling this set of proposed work.
* another contribution, to show what it is building off of.



**Contribution attestations** can link to **other users:**

* Naming a series of collaborators on a contribution.
* Naming an organization you did the work for.



**Verification attestations** can link to other **other attestations** to say “true.” They will often be used as a “digital handshake” to agree to a user’s link to themselves, such as:

* A user confirming you collaborated on this contribution together.
* An organization confirming you did the work for them.



#### Social / Commenting

By default, comments will be offchain attestations, and/or will be connected to the protocol through DeSoc protocols (like Lens and Farcaster).

For comments that prove to be very useful/important for a project, you will be able to push them onchain through an attestation.

\
