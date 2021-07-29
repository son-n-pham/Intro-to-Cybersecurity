# Intro-to-Cybersecurity

## Common Terms

CIA (Confidentiality, Integrity, Availability) Triad
![CIA_Triad](https://user-images.githubusercontent.com/79841341/126899291-d8a9110d-1ef8-4eea-89bf-d51c673fa714.png)

Information security is about protecting this information from "unthorized access, harm or misuse".

Cybersecurity is a subset of Information Security that concerns the digital realm.

Asset, vulnerability and threat:
- Asset: Anything of value to an organizsation whose loss, or degradation of function would cause the organisations economic loss.
- Vulnerability
- Threat

Risk, threat actors, threat actions, control

Risk responses

Subject and object

Confidentiality: The property of information security that information is not made available or disclosed to unauthorsed individuals, entities or precesses.

Keeping things confidential:
- Information classification
- Accession controls
- Encryption
- Information management
- Governance

Integrity:
- Protects the reliabilitya nd acorrectness of data
- Prevents unauthorized alterations of data
- Protection against errors as well as deliberate changes
- List of dependencies: Accuracy, thrthfulness, authenticity validity, ...

Non-repudiation:
- Stops a subect from claiming that an event or action did not occur
- Essential part of accountability
- Needs proof of identity
- Usually implemented through digital signatures

Avaliablity
- Authorized subjects get timely and uninterrupted access to objects (the data and information they need
- Threats to availability include: DEvice failures, software errors, environmental issue

Identity and Authentication
- Identify is to prove to a system that you are who you say you are 
- Authentication verifies the identity using authentication factors

Authorization
- Determines what action s a subject can carry out on an object.

Accountability
- To be able to identify all relevant inforation regarding actions in a system
- Relies on idenity and authorisation
- Imlemented with monitoring and logging
- May use machine learning to detect anomalous behaviours
- Carry out audits

## Lab 1:
- Reinstall WSL2 and Ubuntu
- Reinstall docker
  - sudo needs to be run with docker
- flag:
  - Location:

    ```bash
    root@94e4ddaed551:/# find / -iname 'flag.txt' -type f
    /root/flag.txt
    root@94e4ddaed551:/# cat $(find / -iname 'flag.txt' -type f)
    CITS1003{y0u_f0und_7h3_f1r57_fl46}
    ```
    
    
