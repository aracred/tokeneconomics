#Session 6

Discussions covered minimum viable institutional design pattern based on a rights, access control paradigm

- roles: bundles of rights determined by "the system state"
- methods: actions that can be taken, mutates "the system state" but access or effect may be dependent on roles
- state: all of the information (not limited to smart contract state)


lots of things can happen off chain, but for small communities we can still have maintainers, stewards or council members responsible for overseeing faithful execution of processes or parts of processes which are not automated. 

Output of session: Aracred Governance V0 based on the above

roles: 

- council
- token holder
- contributor
- timeout

council and token holder are pretty standard patterns in DAOs in the wild. 

contributor is defined based on sourcecred portion of the state, anyone who has any cred is a contributor because it means they have participated in the communities production of value according to how that community defines value. 

timeout is an interesting case because it directly recognizes the need for some form of sanctions to manage disputes. We kept it as simple as possible. it has magnitude precisely because sactions need to be graduated (see Ostrom). Furthermore, we noted that without a precedent for sanctions, the first dispite will quickly devolve into a dispute about disputes. Even if that process later changes its a better initial condition than "none" because its impossible to have a healthy discussion about dispute resolutions process in the context of resolving a particular dispute. Moderation policies are expected to evolve with the communities needs, but also new disputes should be arbitrated with the old process prior to reforming the process whenever possible. 

Moderation will be very community dependent so its important that this rights/access control paradigm by relative unopinionated about what rights modified by sanctions. We choosen to emphasize a case where no rights are lost permanently, but the period of the sanction is the magnitude of sanction. One could encode other sanction paradigms using special "negative roles" which are generalizations of blacklists. Positive roles can be thought of as generalizations of whitelists.