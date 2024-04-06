# CISSP Study Notes

## Think Like a Manager

- Due Diligence (think BEFORE you act) - praciticing the activites that maintain the due care effort
  - Examples: Knowledge and Research of Laws and Regulations, Industry Standards, Best Practices
- Due Care (ACTIONS speak louder than words) - doing what a reasonable person would do in a given situation. It is sometimes called the "prudent man" rule
  - Delivery or Execution including: Reporting security incidents, Security awareness training, Disabling access in a timely way
- Know your Priorities
  - CISO - Strategic (long-term)
  - IT Directory or Manager - Tactical (Midrange)
  - IT Engineer - Operational (Short Term)

## Domain 1: Security and Risk Management

- CIA 
  - Confidentiality - Access controls help ensure that only authorized subjects can access objects
  - Integrity - Ensures that data or system configurations are not modified without authorization
  - Availability - Authorized requests for objects must be granted to subjects within a reasonable amount of time
- ISC2 Code of Ethics
  - Protect society, the commonwealth, and the infrastructure 
  - Act honorably, honestly, justly, responsibly, and legally
  - Provide diligent and competent service to principals
  - Advance and protect the profession
- 4 levels of security policy development
  1. Security procedures - detailed step-by-step
  2. Security guidelines - offer recommendations
  3. Security baselines - "define minimum levels"
  4. Acceptable use policy - assign roles and responsibilities 
- Risk Categories (Group of potential causes of risk)
  - Damage
  - Disclosure
  - Losses
- Risk Factors (Somethings that increases risk)
  - Physical damage
  - Malfunctions
  - Attacks
  - Human Errors
  - Application Erros
- Security Planning
  - Strategic - Long term (5 yr)
  - Tactical - Mid term (1 yr)
  - Operational - Short term (monthly, quarterly)
- Response to Risk
  - Risk Acceptance - accept the risk
  - Risk Mitigation - implement countermeasure and accept residual risk
  - Risk Assignment - transfer risk to 3rd party
  - Risk Avoidance - costs of mitigating or accepting are higher than benefits of the serivce
  - Risk Deterrence - Implementing deterrents to would-be violators
  - Risk Rejection - reject or ignore risk
- 7 Steps of NIST 800-37 Risk Management Framework (People can see I always am monitoring)
  1. Prepare to execute the RMF
  2. Categorize information systems
  3. Select security controls
  4. Implement security controls
  5. Assess the security controls
  6. Authorize the system
  7. Monitor security controls
- Not all risk can be mitigated
- It is managements job to decide how that risk is handled
- When multiple priorities present, human safety is most important
- When legal issues are involved, "call an attorney" is a valid choice
- Types of Risk
  - Residual Risk - The risk that remains even with all conceivable safeguards in place
  - Inherent Risk - The amount of risk that exists in the absence of controls
  - Total Risk - The amount of risk an organization would face if no safeguards were implemented
- Total Risk = Threats * Vulnerabilities * Asset Value
- Risk = Threat * Vulnerability
- Risk Analysis 
  - Quantitative - assigns a dollar value to evaluate effectiveness of countermeasures
  - Qualitative - uses a scoring system to rank threats and effectiveness of countermeasures
- Quantitative Risk Analysis Steps
  1. Inventory assets and assign a value (asset value, AV)
  2. Identify threats and produce a list of all possible threats of each asset (calculate EF and SLE)
  3. Perform a threat analysis to calculate the likelihood of each threat being realized within a single year (ARO)
  4. Estimate the potential loss by calculating the annualized loss expectancy (ALE)
  5. Research countermeasures for each threat, and then calculate the changes to ARO and ALE based on an applied countermeasure
  6. Perform a cost/benefit analysis of each countermeasure for each threat for each asset
- Deplhi Technique
  - an anonymous feedback-and-response process used to arrive at a consensus
- Loss potential 
  - what would be lost if the threat agent is successful in exploiting a vulnerability
- Delayed loss 
  - this is the amount of loss that can occur
- Threat agents 
  - what cause the threats by exploiting vulnerabilites
- Terms and Formulas
  - Exposure Factor (EF)
    - Percentage of loss that an organization would experience if a specific asset were violated by a realized risk
  - Single Loss Expectancy (SLE)
    - Represents the cost associated with a single realized risk against a specific asset
    - SLE = Asset Value (AV) * Exposure Factor (EF)
  - Annualized Rate of Occurance (ARO)
    - Expected frequency with which a specific threat or risk will occur within a single year
  - Annualized Loss Expectancy (ALE)
    - Possible yearly cost of all instances of a specific realized threat against a specific asset
    - ALE = Single Loss Expectancy (SLE) * Annualized Rate of Occurance (ARO)
  - Safeguard Evaulation
    - Good security controls mitigate risk, are transparent to users, difficult to bypass, and are cost effective
    - Value of Safeguard = ALE before safeguard - ALE after safeguard - Annual cost of Safeguard
    - Value of Safeguard = ALE1 - ALE2 - ACS
  - Controls Gap
    - The amount of risk reducted by implementing safeguards
    - Total Risk - Controls Gap = Residual Risk
  - Supply Chain
    - Most services are delivered through a chain of multiple entities
    - A secure supply chain includes vendors who are secure, reliable, trustworthy, reputable
- Supply Chain Evaluation
  - On-Site Assessment
  - Document Exchange and Review
  - Process/Policy Review
  - Third-Party Audit
- Threat Modeling
  - Can be proactive or reactive, but in either case, goal is to eliminate or reduce threats
- 3 Approaches to Threat Modeling
  - Focused on Assets
  - Focused on Attackers
  - FOcused on Software
- STRIDE (Threat Modeling Framework developed by Microsoft)
  - Spoofing
  - Tampering
  - Repudiation
  - Information Disclosure
  - Denial of Service
  - Elevation of Privilege
- PASTA (Threat Modeling focuses on developing coutnermeasures based on asset value)
  - Definition of Objectives
  - Definition of Technical Scope
  - App Decomposition & Analysis
  - Threat Analysis
  - Weak & Vulnerability Analysis
  - Attack Modeling & Simulation
  - Risk Analysis & Management
- VAST (Threat Modeling based on Agile PM principles)
  - Visual
  - Agile
  - Simple
  - Threat
- DREAD (Threat Modeling based on answer to 5 questions)
  - Damage Potential
  - Reproducibility
  - Exploitability
  - Affected Users
  - Discoverability
- TRIKE (Threat Modeling focused on "acceptable risk")
  - An open-source threat modeling process that implements a requirements model
  - Ensures the assigned level of risk for each asset is "acceptable" to stakeholders
- COBIT ("Control Objectives for Information Technology" security control framework)
    1. Meeting Stakeholder needs
    2. Convering the Enterprise End-to-End
    3. Applying a Single, Integrated Framework
    4. Enabling a Holistic Approach
    5. Separating Governance from Management
- Diagramming Potential Attacks for Threat Modeling
  - Determining potential attack concepts is often achieved through diagramming
- Reduction Analysis
  - Trust Boundaries - Any location where the level of trust or security changes
  - Data Flow Paths - The movement of data between locations
  - Input Points - Locations where external input is received
  - Privileged Operations - Any activity that requires greater privileges than of a standard user account
  - Details about Security Stance and Approach - Declaration of security policy, security foundations, and security assumptions
- Security Controls
  - Security measures for countering and minimizing loss or unavailability of services or apps due to vulnerabilities 
  - Safeguard are proactive
  - Countermeasures are reactive
- Security Control Categories
  - Technical - "logical" involves the hardware or software mechanisms used to manage access
  - Administrative - Policies and procedures defined by org's security policy, other regulations and requirements
  - Physical - Are items you can physically touch
- Security Control Types
  - Deterrent - Deployed to discourage violation of security policies
  - Preventive - Deployed to thwart or stop unwanted or unauthorized activity from occuring
  - Detective - Deployed to discover or detect unwanted or unauthorized activity
  - Compensating - Provides options to other existing controls to aid in enforcement of security policies
  - Corrective - modifies the environment to return systems to normal after an unwanted or unauthorized activity has occured
  - Recovery - an extension of corrective controls but have more advanced or complex abilities
  - Directive - direct, confine, or control the actions of subjects to force or encourage compliance with security policies
- Types of Law
  - Criminal Law - contains prohibitions against acts such as murder, assault, etc ...
  - Civil Law - include contract disputes, real estate transactions, employment, estate, and probate
  - Administrative Law - Government agencies have some leeway to enact administrative law
- Laws
  - Computer Fraud and Abuse Act (CFAA) - The first major piece of US cybercrime-specific legislation
  - Federal Sentencing Guidelines - Provided punishment guideliens to help federal judges interpret computer crime laws
  - Federal Information Security Management (FISMA) - Required a formal infosec operations for federal government
  - Copyright and the Digital Millennium Copyright Act - Covers literary, musical, and dramatic works
- IP and Licensing 
  - Trademarks - covers words, slogans, and logos used to identify a company and its products or services
  - Patents - patents protect the intellectual property of inventors
  - Trade Secrets - intellectual property that is absolutely critical to their business and must not be discolsed
  - Licensing - 4 types; contractual, shrink-wrap, click-through, and cloud services
- Encryption and Privacy
  - Computer Export Controls - US companies cant export to Cuba, Iran, North Korea, Sudan, and Syria
  - Encryption Export Controls - Dept of Commerce details limitations on export of encryption products outside the US ..
  - Privacy (US) - The basis for privacy rights is in the 4th amendment to the US Constitution
  - Privacy (EU) - General Data Protection Regulation (GDPR) is not a US law, but very likely to be mentioned
- Other US Privacy Laws
  - HIPAA (Health Insurance Portability and Accountability Act)
  - HITECH (Health Information Technology for Economic and Clinical Health)
  - Gramm-Leach-Bliley Act (financial instituations)
  - Children's Online Privacy Protection Act (COPPA)
  - Electronic Communications Privacy Act (ECPA)
  - Communicatioons Assistance for Law Enforcement Act (CALEA)
- Business Continuity Planning Issues
    1. Strategy development
    2. Provisions and proceses
    3. Plan approval
    4. Plan implementation
    5. Training and education
- BCP Definitions
  - BCP - Overall organizational plan for "how-to" continue business
  - DRP (Disaster Recovery Plan) - plan for recovering from a disaster impacting IT and returning the IT infrastructure to operation
  - COOP (Continuity of Operations Plan) - plan for continuing to do business until the IT infrastructure can be restored
- BCP vs DRP
  - BCP focuses on the whole business
  - DRP focuses more on the technical aspects of recovery
  - BCP will cover communications and process more broadly
  - BCP is an umbrella policy and DRP is a part of it
- User Education
  - Methods and techniques to present awareness and training
  - Periodic content reviews
  - Program effectiveness evuluation
- Consequences of privacy and data breaches
  - Reputational Damage (effects may last for years)
  - Identity theft - involves someone using a persons private info to impersonate that individual usually for financial gain
  - Intellectual Property (IP) theft - might quickly cost customers, credit ratings, and branch reputation, loss of profitability, etc ...
  - Fines (may lead to lawsuits) - failing to report a breach can result in fines that cna reach into the millions of dollars
  - Any company with a customer in the EU is subject to GDPR
- Notifications of Breaches
  - EU sets their standard GDPR and notifitcations of data breaches must be reported within 72 hours
  - Escalations to external sources like law enforcement or outside experts to stop/investigate breach
  - Other coutnries have their own reporting timescale
  - Delays sometimes allowed for criminal investigation
- Data Security Controls
  - Marking, Labeling, Handling, Classification - Classification is the most important
  - Data handling - Shippping, Chain of Custody, Dont open boxes
  - Data destruction - Erasing, Clearing (overwriting w/ unclassified data)
  - Record retention - If the retention policy is 1 year it should be destroyed when it ages out
  - Tape Backup Security - Secure facility, tapes labeled ensures all understand the classification of the data


## Domain 2: Asset Security

- Data Lifecycle
  - There isnt a consistent standard used to identify each stage or phase of a data lifecycle
- Data Destruction Methods
  - Erasing - performing a delete operation against a file, files, or media. data is typically recoverable
  - Clearing (overwriting) - preparing media for reuse and ensuring data cannot be recovered using traditional recovery tools
  - Purging - a more intense form of clearing that prepares media for reuse in less secure environment
  - Degaussing - creates a strong magnetic field that erases data on some media
  - Destruction - the final stage in the lifecycle of media and is the most secure method of sanitizing media
- Security Control Baseline
  - Provides a listing of controls that an organization can apply as a baseline
- Keeping data longer than necessary presents unnecessary legal issues
- Data protection
  - Confidentiality is often protected through encryption (at rest and in transport)
- Data Classification
  - Class 0 - Unclassified no damage - Public no damage
  - Class 1 - Confidential damage - Sensitive damage
  - Class 2 - Secret serious damage - private serious damage
  - Class 3 - Top secret exceptionally grave damage - Confidential/Proprietary exceptionally grave damage
- Asset Classification - asset classifications should match the data classifications
- Defining Sensitive data
  - Sensitive data is any information isnt public or unclassified
  - Personally Identifiable Information (PII) - any information that can identify an individual
  - Protected Health Information (PHI) - any health-related information that can be related to a specific person
- Data Ownership
  - Data Owner - Usually a member of senior management. CAN DELEGATE some day-to-day duties. Cannot delegate total responsibility
  - Data Custodian - Usually someone in the IT department. DOES NOT DECIDE what controls are needed, but does implement controls for data owner
  - Data Administrators - responsible for granting appropriate access to personnel (often via RBAC)
  - User - any person who ACCESSES data via a computing system to accomplish work tasks
  - Business/Mission Owners - Can overlap with the responsibilities of the system owner or be same role
  - Asset Owners - owns asset or system that processes sensitive data and associated security plans
- GDPR Terms and Requirements
  - Data Processor - natural or legal person, public authority, agency, or other body, which processes personal data soley on behalf of the data controller
  - Data Controller - the person or entity that controls processing of the data
  - Data Transfer - GDPR restricts data transfers to countries outside the EU
- Reducing GDPR Exposure
  - Anonymization - process of removing all relevant data so that is impossible to identify original subject or person
    - Good only if you dont need the data
  - Pseudonymization - process of using pseudonyms (aliases) to represent other data
    - Can result in less stringent requirements that would otherwise apply under the GDPR
    - Use if you need data and want to reduce exposure
  - Notification of GDPR data breach must be made within 72 hours

## Domain 3 Security Architecture and Engineering

- Zero Trust Security
  - addresses the limitations of the legacy network perimeter-based security model
  - treats user identity as the control plane
  - Assumes compromise/breach in verifying every request. no entity is trusted by default
- Secure Design principles
  - Secure defaults - default configuration reflects a restrictive and conservative enforcement of security policy
  - Fail securely - indicates that components should fail in a state that denies rather than grants access
  - Trust but verify - depended on an initial authentication process to gain access to the internal "secured" environment then relied on generic access control methods
  - Privacy by design
    1. Proactive and not a reactive approach
    2. Privacy as the default setting
    3. Privacy must be embedded in the design
    4. Privacy should be a positive-sum approach and not a zero-sum approach
    5. End to end full lifecycle data protection
    6. Visibility and transparency
    7. Keep privacy user-centric
  - Keep it simple 
    - Complexity is the worst enemy of security
    - Best-in-suite over best-in-breed solutions are on approach 
    - Simplicity also helps to avoid configuration mistakes
- Security-aas - Cloud provider concept in which security is provided to an organization through or by an online entity
- Internet of things - class of devices connected to the internet in order to provide automation, remote control, or AI processing in a home/business setting
- Smart devices - Mobile devices that offer customization options, typically through installing apps, and may use on-device or in-the-cloud AI processing
- SIEM Security Information Event Management (often use AI, ML, and threat intelligence)
  - System that collects data from many other sources within the network
  - Provides real-time monitoring, traffic analysis, and notification of potential attacks
- SOAR Security Orchestration Automation & Response (often use AI, ML, and threat intelligence)
  - Centralized alert and response automation with threat-specific playboks
  - Response may be fully automated or single-click
- Modern Compute & Security
  - SOA is creation of discrete services that may be accessed by users in a black box fashion
  - Microservices are fine-grained services with a discrete function
  - Code-level vulnerabilities should be identified early in the development lifecycle
  - Static code analysis and dynamic testing incorporated early in the CI/CD process can identify deficiencies before release
- Containerization
  - Lightweight granular and portable way to package applications for multiple platforms
  - Reduces overhead of server virtualization by enabling containerized apps to run on a shared OS kernel
    - containers dont have their own OS!
  - Share many concerns of server virtualization; isolation at host, process, network, and storage levels
- APIs (SOAP or REST)
  - Set of exposed interfaces that allow programmatic interaction between services
  - REST uses the HTTPS protocol for web communications to offer API end points
  - All communications between client and server should be encrypted and access limited with API keys
- Embedded Systems
  - Technology component of an IOT device is often referred to as an embedded system
  - Full computer system embedded inside of another larger system
  - Examples: hosts of embedded systems include printers, GPS, drones, semi-auto vechicles
- High Performance Computing
  - An alternative to client-server computing model for compute-intensive operations with large data sets
  - For problems that require the use of extremely large data sets and large-scale parallel processing 
  - Grid computing employs a centralized controller that makes computing assignments to grid members
- Edge Computing
  - Some compute operations require processing activities to occur locally, far from the cloud
  - common in various Internet-of-things scenarios, like agricultural, science/space, military
  - Fog computing places gateway devices in the field to collect and correlate data centrally at the edge
- Cloud Models & Services
  - IAAS (example: Azure Virutal Machines and Amazon EC2)
    - CSP rovides building blocks, like networking, storage and compute
    - CSP manages staff, HW, and datacenter
  - PAAS (Azure App Service, API Management, Azure SQL Database)
    - Customer is responsible for deployment and management of apps
    - CSP manages provisiong configuration, hardware, and OS
  - SAAS (Software as a service) (example: Office365 and ServiceNow)
    - Customer just configure features
    - CSP is responsible for management, operation, and service availability
- Cloud Models
  - Public Cloud 
    - Advantages include scalability, agility, pay-as-you-go, no maintenace, and low skills
  - Private Cloud
    - A cloud environment in your own datacenter
    - Advantages include legacy support, control, and compliance
  - Hybrid
    - Combines public and private clouds, allowing you to run your apps in the right location
    - Advantages include flexibility in legacy, compliance, and scalability scenarios
- Cloud Access Security Broker (CASB) (Solves problem of Shadow IT)
  - Is a security policy enforcement solution that may be isntalled on-premises or in the cloud
- Post-quantum cryptography
  - Development of new kinds of cryptographic approaches that can be implemented using today's conventional computers
  - .... but will be resistant to attacks from tommorrow's quantum computers
- How well do current encryption algorithms hold up to the power of quantum computing? (Quantum resistant)
  - Lattice 
    - Based on different types of problems; shortest vector problem and the closest vector problem
    - Potentially enables us to replace essentially all of our currently endangered schemes
    - Lattice-based cryptographic schemes make up the lion's share of scientific publications on post-quantum cryptography
- Cryptography
  - Code
    - Cryptographic systems of symbols that operate on words or phrases and are sometimes secret but dont always provide confidentiality
  - Ciphers 
    - Ciphers, are always meant to hide the true meaning of a message
- Cryptography - Types of Ciphers
  - Stream cipher 
    - SYMMETRIC key cipher where plaintext digits are combined with a pseudorandom cipher digit stream
    - Each plaintext digit is encrypted one at a time with the corresponding digit of the keystream to give a digit of the ciphertext stream
  - Block cipher
    - Method of encrypting text in which a cryptographic key and algorithm are applied to a block of data at once as a group rather than one bit at a time
  - Substitution cipher
    - Use the encryption algorithm to replace each character or bit of the plaintext message with a different character
  - Transposition
    - Uses an encryption algorithm to rearrange the letters of a plaintext message, forming the ciphertext message
  - Initialization vector (IV)
    - Random bit string (nonce) that is XORed with the message, reducing predicatability and repeatability
    - Size of the IV varies by algorithm but is normally the same length as the block size of the cipher
  - Ceasar, Vigenere, One-time Pad
    - Three very similar stream ciphers. The main difference between these ciphers is key length
- One-Time Pad success factors
  - Key must be generated randomly without any known pattern
  - At least as long as the message to be encrypted
  - Pads must be protected against physical disclosure
  - Each pad must be used only one time and then discarded
- Zero-knowledge proof
  - Enables one to prove knowledge of a fact to another individual without revealing the fact itself
- Split knowledge
  - The information or privilege required to perform an operation is divided among multiple users
- Work function or Work factor
  - Way to measure the strength of a cryptography system by measuring the effort in terms of cost and/or time to decrypt messages
  - Security and protection offered by a cryptosystem is directly proportional to value of its work function/factor
- Symmetric vs Asymmetric 
  - Symmetric 
    - relies on the use of a shared secret key
    - Lacks support for scalability, easy key distribution, and nonrepudiation
  - Asymmetric
    - Public-private key pairs for communication between parties
    - Supports scalability, easy key distribution, and nonrepudiation
- Confidentiality, Integrity, and Nonrepudiation
  - Confidentiality - secrecy of data 
  - Integrity - provides the recipient of a message with the assurance that data was altered
  - Nonrepudiation - provides undeniable proof that the sender of a message actually authored it
- DES and 3DES Modes
  - Electronic Codebook Mode (ECB)
    - Simpletest and least secure mode
    - If same block encountered multiple times, same encrypted block is produced. Process 64 bit blocks
  - Cipher Block Chaining (CBC)
    - Each block of unencrypted text is XORed with block of ciphertext IMMEDIATELY PRECEDING
  - Cipher Feedback (CFB)
    - Streaming version of Cipher block chaining (CBC)
    - Works on data in real time
    - Uses chaining, so errors propagate
  - Output Feedback (OFB)
    - Operates similar to CFB, but XORs the plaintext with a seed value
    - No chaining, no errors
  - Counter (CTR)
    - Uses an incrementing coutner instead of a seed
    - No errors
- XOR
  - Binary values match = 0, otherwise cipher value is 1
- Key Clustering
  - A weakness in cryptography where a plain-text message generates identical ciphertext messages using the same algorithm but using different keys
- Asymmetric key types
  - Public keys are shared among communicating parties
  - Private keys are kept secret 
  - To encrypt a message use the recipients public key
  - To decrypt a message use your own private key
  - To sign a message use your own private key
  - To validate a signature use the sender's public key
- Hash Function requirements
  1. They must allow input of any length
  2. Provide fixed-length output
  3. Make it relatively easy to compute hash for any input
  4. Provide one-way functionality
  5. Must be collision free
- Cryptographic Salts
  - Attackers may use rainbow tables of precomputed values to identify commonly used passwords
  - Salt is random data that is used as an additional input to a one-way function that hashes data
  - Salts reduce the effectiveness of rainbow table attacks
- Digital Signature Standard (DSS)
  - Standard uses the SHA-1, SHA-2, and SHA-3 message digest functions ...
  - Works in conjunction with one of the three encryption algorithms
    - Digital Signature Algorithm (DSA)
    - Rivest, Shamir, Adleman (RSA) algorithm
    - Elliptic Curve DSA (ECDSA) algorithm
- Public Key Infrastructure (PKI)
  - Certificate authorities (CAs) generate digital certificates containing the public keys of system users
  - Users then distribute certificates to people with whom they want to communicate
  - Certificate recipients verify a certificate using the CAs public key
- Securing Traffic
  - Email
    - Standards for encrypted messages include S/MIME and Pretty Good Privacy (PGP)
  - Web
    - The de facto standard for secure web traffic is the use of HTTPS
  - Network
    - IPsec protocol standard provides a common framework for encrypting network traffic and is built into many common Operating Systems
- IPsec
  - security architecture framework that supports secure communication over IP
  - Establishes a secure channel in either transport mode or tunnel mode
  - Can be used to establish direct communication between computers or over a VPN connection
  - Uses 2 protocols; Authentication Header (AH) and Encapsulating Security Payload (ESP)
- Cryptographic attacks
  - Brute-force attacks
  - Meet-in-the-middle attacks
    - exploits protocols that use 2 rounds of encryption
  - Man-in-the-middle attack
    - fools both parties into communicating with the attacker instead of directly with each other
  - Birthday attack
    - attempt to find collisions in hash functions
  - Replay attack 
    - attempt to reuse authentication requests
- Digital Rights Management (DRM)
  - Allow content owners to enforce restrictions on the use of their content by others
  - Commonly protect entertainment content such as music and movies
- 3 Major Public Key Cryptosystems
  - RSA - prime numbers in 1977
  - El Gamal - less common and modular arithmetic
  - Elliptic curve - depends on elliptic curve discrete log problem more security. meant for keys of the same length
- Digital signatures
  - Rely on public key cryptography and hashing functions
  - 3 Approved Algorithms
    - DSA
    - RSA
    - Elliptic Curve DSA (ECDSA)
- TODO: Go review Encryption algorithms and key sizes
- Security Model
  - Security models are used to determine how security will be implemented, what subjects can access the system, and what objects they will have access to
  - They are a way to formalize security policy
  - Typically implemented by enforcing integrity, confidentiality, or other controls
  - Each of these models lays out broad guidelines and is not specific in nature
  - Up to the developer to decide how these models are integrated
- State Machine Model
  - Describes a system that is always secure no matter what state it is in
  - A state is a snapshot of a system at a specific moment in time. All state transitions must be evaluated
  - If each possible state transition results in another secure state, the system can be called a secure state machine
- Information Flow Model
  - Focuses on the flow of information
  - Information flow models are basd on a state machine model
  - Biba and Bell-LaPadula are both information flow models
  - Bell-LaPadula 
    - Preventing information from high security level to a low security level
  - Biba
    - Focuses on flow from low to high security level
- Non-Interference Model
  - Loosely based on the information flow model
  - Concerned with how actions of a subject at a higher security level affect the system state or the actions of a subject at a lower security level
  - Ensures that the actions of different objects and subjects arent seen by other objects and subjects on the same system
- Lattice-based Model
  - Based on the interaction between any combination of:
  - objects (such as resources, computers, and applications)
  - subjects (such as individuals, groups, or organizations)
- Security Models
  - Simple security property - describes rules for read
  - Star * security property - describes rules for write
  - Invocation property - rules around invocations (calls) such as to subjects
- Security Models
  - Integrity
    - Biba
      - No read down, no write up
    - Clark-Wilson
      - Access control triple
    - Goguen-Meseguer
      - THE noninterference model
    - Sutherland
      - Preventing interference (information flow and SMM)
  - Confidentiality
    - Bell-LaPadula
      - No read up, no write down
    - Brewer and Nash
      - aka "Chinese Wall"
    - Take Grant 
      - Employs a "directed graph"
- Bell LaPadula (No Running Under Nets With Dingos)
  - State machine model enforces confidentiality
  - Uses Mandatory access control (MAC) to enforce the DoD multilevel security policy
  - Simple security property - no read up
  - Star * security property - no write down
- Bell
  - Lattice-based model developed to address concerns of integrity
  - Simple integrity property - no read down
  - Star * integrity property - no write up
  - Invocation property - prohibits a subject at one level of integrity from invoking a subject at a higher level of integrity
- Clark-Wilson
  - Uses security labels to grant access to objects
  - constrained data item (CDI) - any data item whose integrity is protected by the security model
  - unconstrained data item (UDI) - any data item that is not controlled by the security model
  - integrity verification procedure (IVP) - procedure that scans data items and confirms their integrity
  - transformation procedures (TPs) - are the only procedures that are allowed to modify a CDI
  - What is the access control triple (triplet)
    - Relationship between; Authenticated Principal (user) -> Programs (transformation procedures) -> Data Items (UDIs and CDIs)
- Take Grant Model
  - Another confidentiality-based model that supports four basic operations; take, grant, create, and revoke
- Brewer and Nash Model
  - aka "Chinese Wall model". It was developed to prevent conflict of interest problems (confidentiality based)
- Graham-Denning model
  - Model uses a formal set of protection rules for which each object has an owner and controller
  - Focused on the secure creation and deletion of both subjects and objects
  - Collection of eight primary protection rules or actions that define the boundaries of certain secure actions
    1. Securely create an object
    2. Securely create a subject
    3. Securely delete an object
    4. Securely delete a subject
    5. Securely provide the read access right
    6. Securely provide the grant access right
    7. Securely provide the delete access right
    8. Securely proivde the transfer access right
- Security Modes
  - Dedicated Mode 
    - Security clearance that permits access to ALL info processed by system, approval for ALL info
    - processed by system, valid need-to-know for ALL info processed by system
  - Multilevel Mode
    - Can process information at different levels even when all system users do not have the required 
    - security clearance to access all information processed by the system
  - System High Mode
    - Each user must have valid security clearance, access approval for ALL info processed by system, and valid need-to-know
    - for at least SOME info on the system. Offers most granular control over resources and users of these models
  - Compartmented Mode
    - Goes one step further than System High. Each user must have valid security clearance, access approval
    - for ALL INFO processed by system, but requires valid need-to-know for ALL INFO they will have access to on the system
- State Machine Model
  - Describes a system that is always secure no matter what state it is in
  - Based on the computer science definition of a finite state machine (FSM)
  - A state is a snapshot of a system at a specific momemnt in time. All state transitions must be evaluated
  - If each possible state transition resutls in another secure state, the system can be called a secure state machine
- Information Flow Model
  - Focuses on the flow of information
  - Information flow models are based on a state machine model
  - Biba and Bell-LaPadula are both information flow models
  - Bell-LaPadula preventing information flow from a high security level to a low security level
  - Biba focuses on flow from low to high security level
- Trusted Computing Base (TCB)
  - TCB is a combination of hardware, software and controls that work together to form a "trusted base" to enforce your security policy
  - Is a subset of the complete information system. Is the only portion that can be trusted to adhere to and enforce your security policy
  - Security Perimeter
    - Imaginary boundary that separates TCB from the rest of the system
  - TCB must create secure channels (aka "trusted paths") to communicate with the ret of the system
  - Protects users (aka subjects) from compromise as a result of TCB interchange
  - Reference Monitor (enforces access control)
    - Logical part of the TCB that confirms whether a subject has the right to use a resource prior to granting access
  - Security kernel (implements access control)
    - Collection of the TCB components that implement the functionality of the reference monitor
- TCSEC, ITSEC, and Common Criteria
  - Common Criteria (ISO-IEC 15408)
    - Common Criteria enable an objective evaluation to validate that a particular product or system satisfies a defined set of security requirements
    1. Description of Assets
    2. Identification of Threats
    3. Analysis & Rating of Threats
    4. Determination of Security Objectives
    5. Selection of Security Functional Requirements
  - TCSEC (Trusted Computer System Evaluation Criteria)
    - Structured set of criteria for evaluation computer security within products and systems
  - ITSEC (Information Technology Security Evaluation Criteria)
    - ITSEC represents an initial attempt to create security evaluation criteria in Europe
    - ITSEC uses 2 scales to rate functionality and assurance
  - 2 flavors
    - community Protection Profile (cpp) - black box
    - Evaluation Assurance Level (EAL) - white box
- Common Criteria Security Evaluation Standards
  - CC Level  Description
  - EAL0,EAL1 Functionally Tested
  - EAL2      Structurally Tested
  - EAL3      Methodically Tested & Checked
  - EAL4      Methodically Designed, Tested, and Reviewed
  - EAL5      Semi-Formally Designed and Tested
  - EAL6      Semi-Formally Verified Design and Tested
  - EAL7      Formally Verified Design and Tested
- Covert Channels
  - A method that is used to pass information over a path that is not normally used for communication
  - Because it's not normally used, it may not be protected by the system's normal security controls
  - 2 types
    - Covert timing
    - Covert storage
- Trusted Platform Module
  - A chip that resides on the motherboard of a device
  - Multi-purpose, like storage and management of keys used for full disk encryption (FDE) solutions
  - Provides the operating system with access to keys, but prevents drive removal and data access
- Types of Access Control
  - Mandatory Access Control
    - Enforces an access policy that is determined by the system, not the object owner
    - Relies on classification labels that are representative of security domains and realms
  - Discretionary Access Control
    - Permits the owner or creator of an object to control and define its accessibility, because the owner has full control by default
  - Non-Discretionary Access Control
    - Enables the enforcement of system-wide restrictions that override object-specific access control
  - Rule-based Access Control
    - Defines specific functions for access to requested objects
    - Commonly found in firewall systems
- Role-Based Access Control
  - Uses a well-defined collection of named job roles to endow each one with specific permissions
    , thereby seeking to ensure that users who occupy such roles can access what they need to get their jobs done
- MAC Model Classifications
  - Hierarchical environment
    - Various classification labels are assigned in an ORDERED structure from low security -> medium security -> high security
  - Compartmentalized environment 
    - Requires specific SECURITY CLEARANCES over compartments or domains instead of objects
  - Hybrid environment
    - Contains levels with compartments that are isolated from the rest of the security domain. Contains both hierarchical
    - and compartmentalized environments so that security levels have subcompartments
  - Key point about the MAC model is that every object and every subject has one or more labels
    These lables are predefined, and the system determines access based on assigned labels
- Certification 
  - The technical evaluation of each part of a computer system to assess its concordance with security standards
- Accreditation
  - The process of formal acceptance of a certified configuration from a designated authority
- Open system
  - Are designed using industry standards and are usually easy to integrate with other open systems
- Closed system
  - Are generally proprietary hardware and/or software. Their specifications are not normally published, and they are 
    usually harder to integrate with other systems
- Techniques for ensuring CIA ...
  - Confinement 
    - Restricts a process to reading from and writing to certain memory locations
  - Bounds 
    - Are the limits of memory a process cannot exceed when reading or writing
  - Isolation
    - Is the mode a process runs in when it is confined through the use of memory bounds
- Factors of Authentication
  - Something you know (pin or password)
  - Something you have (trusted device)
  - Something you are (biometric)
- Authentication & Authorization
  - Authentication (AuthN)
    - Process of proving that you are who you say you are
  - Authorization (AuthZ) 
    - Act of granting an authenticated party permission to do something
  - Authentication can be achieved with both symmetric and asymmetric cryptosystems
- Multitasking and Multithreading
  - Multitasking
    - Simultaneous execution of more than one application on a computer and is managed by the operating system
  - Multithreading
    - Permits multiple concurrent tasks to be performed within a single process
- Multiprocessing and Multiprogramming
  - Multiprocessing
    - The use of more than one processor to increase computing power
  - Multiprogramming 
    - Similar to multitasking but takes place on mainframe systems and requires specific programming
- Single-State and Multistate processors
  - Single-state processors are capabile of operating at only one security level at a time, whereas multistate can simultaneously
    operate at multiple security levels
- Processor Operating Modes
  - User
    - Applications operate in a limited instruction set environment known as user mode
  - Privileged
    - Controlled operations are performed in privileged mode, also known as system
      mode, kernel mode, and supervisory mode
- Memory Types
  - Read-only Memory (ROM)
    - Read-only. Contents burned in at factory
  - RAM
    - Static RAM (SRAM) uses flip-flops, dynamic RAM (DRAM) uses capacitors
  - PROM
    - Programmable chips similar to ROM, with several sub-types 
  - EPROM
    - Erasing, Clearing (overwriting w/ unclassified data)
    - Ultraviolet EPROM (UVEPROM)
      - chips have a small window that, when illuminated with a special ultraviolet light, erases contents
    - Electronically Erasable PROM (EEPROM)
      - Uses electric voltages delivered to the pins of the chip to force erasure
    - Flash Memory
      - Derivative concept from EEPROM. Nonvolatile, can be electronically erased and rewritten
- Security Issues with Storage
  - Primary storage is the same as memory
  - Secondary storage consists of magnetic, flash, and optical media that must be first read into 
    primary memory before the CPU can use the data
  - Random access storage devices can be read at any point
  - Sequential access storage devices require scanning through all the data physically stored before the desired location
  - 3 Main security issues surrounding secondary storage devices:
    1. Removable media can be used to steal data
    2. Access controls and encryption must be applied to protect data
    3. Data can remain on the media even after file deletion or media formatting
- Security Risk of Input & Output Devices
  - Subject to eavesdropping and tapping, used to smuggle data out of an organization, or used to 
    create unauthorized, insecure points of entry into an organization's systems and networks
- The purpose of Firmware
  - Software stored on a ROM chip, containing basic instructions needed to start a computer
  - Also used to provide operation instructions in peripheral devices such as printers
- Vulnerabilities, Threats, and Countermeasures
  - Process Isolation
    - Ensures that individual processes can access only their own data
  - Layering
    - Creates different realms of security within a process and limits communication between them
  - Abstraction
    - Creates "black-box" interfaces for programmers to use without requiring knowledge of an algorithms or devices inner workings
  - Data hiding
    - Prevents information from being read from a different security level
    - Hardware segmentation enforces process isolation with physical controls
- The role of Security Policy
  - The role is to inform and guide the design, development, implementation, testing, 
    and maintenance of some particular system
- Cloud computing
  - The concept of computing where processing and storage are performed elsewhere over a network connection rather than locally
  - Eg... Azure, Amazon, GCP
- Hypervisors
  - Hypervisor, also known as a virtual machine monitor (VMM), is the component of virtualization
    that creates, manages, and operates the virtual machines (VMs)
  - Type 1 hypervisor
    - A native or bare-metal hypervisor
    - There is no host OS. Instead the hypervisor installs directly onto the hardware where the host OS would normally reside
  - Type 2 hypervisor
    - A hosted hypervisor
    - A standard regular OS is present on the hardware, and the hypervisor is then installed as another software application
- Cloud Access Security Broker (CASB)
  - A cloud access security broker (CASB) is a security policy enforcement solution
    that may be installed on-premises or in the cloud
- Security-aas
  - A cloud provider concept in which security is provided to an organization through or by an online entity
- Smart devices
  - Mobile devices that offer customization options, typically through installing apps, and
    may use on-device or in-the-cloud artificial intelligence (AI) processing
- Internet of things 
  - class of devices connected to the internet in order to provide automation, remote control, or AI processing in a home/business setting
- Mobile device and mobile app security
  - Mobile device security
    - the range of potential security options or features that may be available for a mobile device
    - Security features include full device encryption, remote wiping, lockout, screen locks, GPS, application control, etc...
  - Understand mobile application security
    - the applications and functions used on a mobile device need to be secured
    - Related concepts include key management, credential management, authentication, geotagging, encryption, application whitelisting
      and transitive trust/authentication
  - Bring your own device (BYOD)
    - A policy that allows employees to use their own personal mobile devices to work to access business information and resources
    - May imporove employee morale and job satisfaction, but it increases security risks to the organization
- Embedded systems & Static environments 
  - Embedded system
    - Typically designed around a limited set of specific functions in relation to the larger product of which its a component
  - Static environments
    - Are applications, OSs, hardware sets, or networks that are configured for a specific need, capability, or function,
      and then set to remain unaltered
- Privilege & Accountability
  - Principle of Least Privilege
    - Ensures that only a minimum number of processes are authorized to run in supervisory mode
  - Separation of Privilege
    - Increases the granularity of secure operations
  - Accountability ensures that an audit trail exists to trace operations back to their source
- Common flaws & vulnerabilities
  - Buffer overflow
    - Occurs when the programmer fails to check the size of input data prior to writing the data
      into a specific memory location
  - In addition, programmers can leave back doors and privileged programs on a system after it is deployed
  - Even well-written systems can be susceptible to time-of-check-to-time-of-use (TOCTOU) attacks.
    Any state change presents an opportunity for an attacker to compromise a system
- Functional Order of Security Controls
  - Deterrence -> Denial -> Detection -> Delay (-> Determine -> Decide)
- Physical Security Controls
  - Administrative
    - Also known as management controls and include policies and procedures, like site management, personnel controls, awareness training
      , and emergency response and procedures
  - Logical
    - Also known as technical controls and are implemented through technology like access controls, intrusion detection, alarms
      CCTV, monitoring, HVAC, power supplies, and fire detection and suppression
  - Physical
    - Use physical means to protect objects and includes fencing, lighting, lock, construction materials,
      mantraps, dogs, and guards
  - Without control over the physical environment, no amount of administrative or technical/logical access controls can provide adequate security
  - Fence
    - 3-4 feet - deters casual trespasser
    - 6-7 feet - too hard to climb easily
    - 8 feet (w/ barbed wire) - will deter intruders
  - Temp
    - Humidity: 40% - 60% ideal
    - Temps: for computers 60-75f (15-23C), damage at 175F. Manage storage devices damaged at 100F
  - Electrical Impacts
    - Blackout: prolonged loss of power
    - Brownout: prolonged low voltage
    - Fault: short loss of power
    - Surge: prolonged high voltage
    - Spike: temp high voltage
    - Sag: temp low voltage
  - Lights
    - 8 feet high with 2 feet candle power
- Humidity and Static Electricity
  - Too much humidity can cause corrosion
  - Too little humidity causes static electricity. Even on nonstatic carpet, low humidity can generate 20k volt static discharge
- Fire and Suppression Agents
  - Class A (Ash)
    - Common combustibles such as wood, paper, etc.
    - Should be extinguished with water or soda acid
  - Class B (Boil)
    - Burning alcohol, oil, and other petroleum products such as gasoline
    - Extinguished with gas or soda acid. NEVER use water
  - Class C (Conductive)
    - Electrical fires which are fed by electricity and may occur in equipment or wiring
    - Electrical fires are conductive fires and extinguished by any type of gas non conductive
  - Class D (Dilythium)
    - Burning metals and are extinguished with dry powder 
  - Class K (Kitchen)
    - Kitchen fires, such as burning oil and grease
    - Wet chemicals are used to extinguish class K fires
- Fire Detection Systems
  - Smoke sensing
  - Flame sensing
  - Heat sensing
- Fire Extinguisher and Suppression agents
  - Class   Type                  Suppression Material
  - A       Common combustibles   Water, soda acid (a dry powder or liquid chemical)
  - B       Liquids               CO2, halon, soda acid
  - C       Electrical            CO2, halon
  - D       Metal                 Dry powder
  - K       Kitchen               Wet chemicals
- Voltage and Noise
  - Electromagnetic Interference
    - Common mode noise
      - Generated by the difference in power between the HOT and GROUND wires of a power source operating electrical equipment
    - Traverse mode noise
      - Generated by a difference in power in the HOT and NEUTRAL wires of a power source operating electrical equipment
  - Radio Frequency Interference (RFI)
    - Source of interference that is generated by electrical applications, light sources, eletrical cables and circuits, and so on
  - Static Voltage      Possible Damage
  - 40                  Destruction of sensitive circuits and other components
  - 1,000               Scrambling of monitor displays
  - 1,500               Destruction of hard drive data
  - 2,000               Abrupt system shutdown
  - 4,000               Printer jam or component damage
  - 17,000              Permanent circuit damage
- Damage from Fire and Fire Supression
  - Smoke is damaging to most storage devices
  - Heat can damage any electronic or computer component
  - Suppression mediums can cause short circuits, initiate corrosion, or otherwise render equipment useless
- Water Suppression Systems
  - Preaction systems
    - Use closed sprinkler heads and the pipe is charged with compressed air instead of water. Water held in check by an electrically operated sprinkler valve
  - Wet pipe systems
    - Filled with water contain compressed air until fire suppression systems are triggered and then pipe is filled with water
  - Dry pipe systems
    - Closed sprinkler heads 
    - Water is held back by a valve that remains closed as long as sufficient air pressure remains in the pipes
  - Deluge systems
    - Similar to dry pipes except the sprinkler heads are open and larger
- Gas Discharge systems
  - More effective than water systems but shouldnt be used near people because oxygen is removed
  - Halon is effective but bad for environment
  - Suiteable replacements
    - FM-200, CEA-410, Argon, Argonite, Inergen, Aero-k, NAF-S-111, FE-13
- Lock Types
  - Electronic Combination Locks
    - aka Cipher Lock - Something you know
  - Key Card Systems
    - Something you have
  - Biometric Systems
    - Something you are
  - Conventional Locks
    - Easily picked/bumped and keys easily duplicated
  - Pick-and-Bump Resistant Locks
    - Expensive, harder to pick & keys not easily duplicated
- Site Selection & Facility Design
  - Site Selection
    - Visibility, Composition of the surrounding area, area accessibility, and the effects of natural disasters
  - Facility Design
    - Understanding the level of security needed by your organization and planning for it before construction begins
- Secure Work Area Design and Configuration
  - There should not be equal access to all locations within a facility
  - Areas with high-value assets require restricted access
  - Valuable and confidential assets should be located in the heart or center of protection provided by a facility
  - Centralized server or computer rooms need not be human compatible
- Threats to Physical Access Controls
  - Abuses of physical access control include propping open secured doors and bypassing locks or access controls
  - Masquerading is using someone else's security ID to gain entry to a facility
  - Piggybacking is following someone through a secured gate or doorway without being identified or authorized personally
- Securing a Wiring closet
  - Where the networking cables for a floor or even a whole building are conencted
  - Most security focuses on preventing physical unauthorized access
- Physical Security Requirements
  - A facility employs restricted areas to control physical security
  - Often an escort is assigned to visitors and they are monitored closely
  - Tracking actions of outsiders when they are granted access to prevent malicious activity against the most protected assets
  - Understand the needs for media storage
  - Media storage facilities should be designed to securely store blank, reusable, and installation media
    - Concerns include theft, corruption, data remnant recovery
  - Media storage facility protections include;
    - Locked cabinets or safes
    - Using a librarian/custodian
    - Implementing a check-in/check-out process
    - Using media sanitization
  - Evidence Storage
    - Used to retain logs, drive images, virtual machine snapshots, and other datasets for recovery, internal
      investigations, and forensic investigations
    - Protections for evicdence storage
      - Locked cabinets or safes
      - Dedicated/isolated storage facilities
      - Offline storage
      - Access restrictions and activity tracking
      - Hash management and encryption
- Audit trails and Access logs
  - Audit trails and access logs are useful tools for managing for physical access control
  - Creation 
    - may need to be created manually by security guards or may generated automatically with the right equipment
  - Monitoring 
    - You should also consider monitoring entry points with CCTV
- The Need for Clean Power
  - Power supplied by electric companies is not always consistent and clean
  - Most electronic equipment requires clean power in order to function properly and avoid damage
  - A UPS is a type of self-charging battery that can be used to
    - supply consistent, clean power to sensitive equipment
    - supply power for minutes or hours (depending on its size) in the event of power failure

## Domain 4 Communication and Network Security

- Network Architectures
  - VXLAN (Virtual Extensible LAN)
    - Network virtualization enabling network segmentation at high scale
    - Overcomes VLAN scale limitations - limit is 4096 VLANs versus millions of VXLANS
    - tunneling protocol that encapsulates an Ethernet frame (layer 2) in a UDP packet
  - Software Defined Networks (SDN)
    - A network architecture approach that enables the network to be intelligently and centrally controlled or programmed using software
    - Has capacity to reprogram the data plane at any time
    - Use cases include SD-LAN and SD-WAN
    - Separating the control plane from the data plane opens up a number of security challenges
  - Software Defined Wide-Area Networks
    - enables users in branch offices to remotely connect to an enterprises network
    - Enalbes use of many network services - LTE, broadband iternet, MPLS, etc ...
    - Security is based largely on IP security (IPsec), VPN tunnels, next-gen firewalls (NGFWs), and the micro-segmentation of app traffic
  - Lifi
    - Uses the modulation of light intensity to transmit data (uses LED)
    - Can safely function in areas otherwise susceptible to eletromagnetic interference
    - LiFi only requires working LED lights
  - Zigbee Personal Area Network (PAN) IoT smart home hub
    - Short-range wireless PAN (personal area network) technology developed to support automation,
      machine-to-machine communication, remote control and monitoring of IoT devices
    - Suports both centralized and distributed security models, and mesh topology
    - Assumes that symmetric keys used are transmitted securely (encrypted in-transit)
- Cellular Networking
  - 5G
    - Faster speeds and lower latency
    - Unlike 4G, 5G doesnt identify each user through their SIM card. Can assign identities to each device
    - Some air interface threats such as session hijackings are dealt with in 5G
    - Standalone (SA) version of 5G will be more secure than the non-standalone (NSA) version
    - Diameter protocol, which provides authentication, authorization, and accounting (AAA) will be a target
    - Because 5G has to work alongside older tech (3G/4G), old vulnerabilities may be targeted 
    - Because scale of IoT endpoint counts on 5G is exponentially greater, DDos is a concern
- Content Delivery Networks (CDN)
  - A geographically distributed network of proxy servers and their data centers
  - Goal is fast and highly available content delivery by distributing content spatially relative (close to) users
  - CDN networks serving JavaScript have been targeted to inject malicious content into pages
  - Vendors offer DDos protection and WAF
- The OSI Model
  - All Presidents Since Truman Never Did Pot
  - Application
    - SSH, HTTP, FTP, SMTP, IMAP, SNMP
  - Presentation
    - Encryption protocols and format types such as ASCII, JPEG
  - Session
    - SMB, RPC, NFS, SQL
  - Transport
    - TCP, UDP
  - Network
    - ICMP, IP, IPSec, NAT
  - Data Link
    - ARP, PPP, SLIP, ISDN
  - Physical
    - WIFI, Ethernet, Bluetooth
  - Common TCP/UDP Ports
  - Protocol                        TCP/UDP         Port
  - --------------------------------------------------------
  - File Transfer Protocol (FTP)    TCP             20/21
  - Secure Shell (SSH)              TCP             22
  - Telnet                          TCP             23
  - Simple Mail Transfer P. (SMTP)  TCP             25
  - Domain Name System (DNS)        TCP/UDP         53
  - Dynamic Host .. (DHCP)          UDP             67/68
  - Trivial File Transfer P. (TFTP) UDP             69
  - Hypertext Transfer P. (HTTP)    TCP             80
  - Post Office Protocol (POP3)     TCP             110
  - Network Time Protocol (NTP)     UDP             123
  - NetBIOS                         TCP/UDP         137/138/139
  - Internet Message Access P(IMAP) TCP             143
  - Simple Network Mgmt P. (SNMP)   TCP/UDP         161/162
  - Border Gateway Protocol (BGP)   TCP             179
  - Lightweight Directory .. (LDAP) TCP/UDP         389
  - HTTP over TLS (HTTPS)           TCP             443
  - LDAP over TLS                   TCP/UDP         636
  - FTP over TLS                    TCP             989/990
- TCP vs UDP
  - No      TCP                               UDP
  - 1       Connection oriented               Connection-less protocol
  - 2       Byte stream                       Message stream
  - 3       No support for multi/broadcasting Supports multicasting/broadcasting
  - 4       Supports full duplex transmission Doesnt support full duplex
  - 5       Reliable service of data trans.   Unreliable service of data transmission
  - 6       Packet is called segment          Packet is called datagram
  - 7       Error detection and flow control  No support for error detection and flow control
- Cabling Types and Throughput
  - UTP Category   Data Rate        Max Length   Cable Type    Application
  - CAT5           Up to 100 Mbps   100m         Twisted Pair  Eternet, FastEthernet, Token Ring
  - CAT5e          Up to 1 Gbps     100m         Twisted Pair  Eternet, FastEthernet, Gigabit Ethernet
  - CAT6           Up to 10 Gbps    100m         Twisted Pair  Gigabit Ethernet, 10G Ethernet (55 meters)
  - CAT6e          Up to 10 Gbps    100m         Twisted Pair  Gigabit Ethernet, 10G Ethernet (55 meters)
  - UTP = Unshield Twisted Pair
  - TODO: Review Graphs of Cabling Types of 10Bae2 to Fiber Optic
- Standard Network Topologies
  - STAR
    - Employs a centralized connection device
    - Can be a simple hub or switch
    - Each system is connected to the central hub by a dedicated segment
  - MESH
    - Connects systems to all other systems using numerous paths
    - A partial mesh topology connects many systems to many other systems
    - Provides redundant connections to systems, allowing multiple segment failures without 
      seriously affecting connectivity
  - RING 
    - Connects each system as points on a circle
    - The connection medium acts as a unidirectional transmission loop
    - Only 1 system can transmit data at a time
    - Traffic management is performed by a token
  - BUS (Ethernet is a bus network)
    - Connects each system to a trunk or backbone cable
    - All systems on the bus can transmit data simultaneously which can result in collisions
    - A collision occurs when two systems transmit data at the same time; the signsl interfere with each other
- Analog vs Digital
  - Analog
    - Communications occur with a continous signal that varies in frequency, amplitude, phase,
      voltage, and so on
    - The variances in the continous signal produce a wave shape (as opposed to the square shape of a digital signal)
    - The actual communication becomes altered and corrupted because of attenuation over long distances and interference
  - Digital
    - Communications occur through the use of a discontinuous electrical signal and a state change or on-off pulses
    - More reliable than analog signals over long distances or when interference is present because of a digital signal's
      definitive information storage method
    - Uses current voltage where voltage on represents a value of 1 and voltage off represents a value of 0
    - These on-off pulses create a stream of binary data
- Synchronous vs Asynchronous
  - Synchronous
    - Communications rely on a timing or clocking mechanism based on either and independent clock
      or a time stamp embedded in the data stream
    - Are typically able to support very high rates of data transfer (example networking)
  - Asynchronous
    - Communications rely on a stop and start delimiter bit to manage the transmission of data
    - Best suited for smaller amounts of data (example public switched telephone network modelms)
- Baseband vs Broadband
  - Baseband
    - Support only a single communication channel
    - Uses a direct current applied to the cable. A current that is at a higher level represents the binary
      signal of 1, and a lower level is binary signal of 0
    - Is a form of digital signal (Example ethernet)
  - Broadband
  - Support multiple simultaneous signals
  - Uses frequency modulation to support numerous channels, each supporting a distinct communication session. Suitable for
    high throughput rates, especially when several channels are multiplexed
  - Is a form of analog signal (Example TV and cable modem)
- Broadcast, Multicast, Unicast
  - Broadcast
    - Supports communications to all possible recipients
  - Multicast 
    - Supports communications to multiple specific recipients
  - Unicast
    - Supports only a single communication to a specific recipient
- CSMA, CSMA/CA, CSMA/CD
  - Carrier Sense Multiple Access (CSMA)
    - Developed to decrease the changes of collisions when two or more stations start sending their signals over the datalink layer
    - Requires that each station first check the state of the medium before sending
  - CSMA variations and collisions
    - CSMA
      - Does not directly address collisions
    - CSMA/CA (collision avoidance)
      - Attempts to avoid collisions by granting only a single permission to communicate at any given time
    - CSMA/CD (collision detection)
      - Responds to collisions by having each member of the collision domain wait for a short but random 
        period of time before starting the process over
  - TODO: Collision chart CSMA
- Token Passing, Polling
  - Token passing (prevents collisions in ring networks)
    - Performs communications using a digital token. Once its transmission is complete, it 
      releases the token to the next system
  - Polling 
    - Performs communications using a master-slave configuration. The primary system polls each
      secondary system in turn whether they have a need to transmit data
- Network Segmentation
  - Intranet 
    - A private network that is designed to host the same information services found on the internet
  - Extranet (cross between internet & intranet)
    - Section of an organization's network that has been sectioned off to act as an intranet for the 
      private network but also serves information to the public internet
  - DMZ (perimeter)
    - An extranet for public consumption is typically labeled a demilitarized zone (DMZ) or perimeter network
  - Reasons for segmentation
    - Boosting Performance
    - Reducing Communication Problems
    - Providing Security
- Bluetooth
  - Bluetooth, or IEEE 802.15, personal area networks (PANs) are another area of wireless security concern
  - Connects headsets for cell phones, mice, keyboards, GPS, and other devices
  - Connections are set up using pairing, where primary device scans the 2.4 Ghz radio frequencies for available devices
- Mobile System Attacks
  - BLUEJACKING 
    - Savy pranksters push unsolicited messages to engage or annoy other nearby Bluetooth users by taking advantage in 
      the technology's messaging options
  - BLUESNARFING (data theft)
    - Thieves wirelessly connect to some early Bluetooth-enabled mobile devices without the owner's knowledge to download and/or 
      alter phonebooks, calendars, or worse
  - BLUEBUGGING
    - An attack that grants hackers remote control over the feature and functions of a Bluetooth device. This could include the 
      ability to turn on the microphone to use the phone as an audio bug
  - TODO: Wireless Technologies chart for Version 802.11 speed and frequency
- SSID Broadcast
  - Wireless networks traditionally announce their SSID on a regular basis with a beacon frame
  - When the SSID is broadcast, any device with automatic detect and connect to the network
  - Hiding the SSID is considered "security through obscurity" - its detectable through client traffic
- Temporal Key Integrity Protocol (TKIP)
  - Designed as the replacement for WEP without the need to replace legacy hardware
  - Implemented into 802.11 wireless networking under the name WPA (WiFi Protected Access)
- CCMP (Counter Mode with Cipher Block Chaining Message Authentication Code Protocol)
  - Created to replace WEP and TKIP/WPA
  - Uses AES with a 128-bit key
  - Used with WPA2
- WPA2
  - A new encryption scheme known as the CCMP
  - CCMP is based on the AES encryption scheme
- Fibre Channel & FCoE
  - Fibre channel
    - Form of network data storage solution (ie SAN or NAS) that allows for high-speed file transfer
  - Understand FCoE
    - FCoE (Fibre Channel over Ethernet) is used to encapsulate Fibre channel communications over Ethernet networks
- iSCSI
  - iSCSI (Internet Small Computer System Interface) is a networking storage standard based on IP
- Site Survey 
  - Usually involves walking around with a portable wireless device, taking note of the wirelss signal strength
    , and mapping this on a plot or schematic of the building
- EAP, PEAP, LEAP
  - EAP (Extensible Authentication Protocol)
    - An authentication framework 
    - Allows for new authentication technologies to be compatible with existing wireless or point-to-point connection technologies
  - PEAP (Protected EAP)
    - Encapsulates EAP methods within a TLS tunnel that provides authentication and potentially encryption
  - LEAP (Lightweight EAP)
    - A Cisco proprietary alternative to TKIP for WPA
    - Developed to address deficiencies in TKIP before the 802.11i/WPA2 system was ratified as a standard
- MAC Filtering 
  - A list of authorized wireless client interface MAC addresses
  - Used by a wireless access point to block access to all nonauthorized devices
- Captive Portals
  - Portal is an authentication technique that redirects a newly connected wireless web client to a portal access control page
- Antenna Types
  - Loop
    - Omnidirectional, reaches multiple frequencies and used for TV and RFID systems
    - Horizontall mounted
  - Monopole
    - An omnidirectional antenna that can send and receive signals in all directions perpendicular 
      to the line of the antenna itself
  - Dipole
    - An omnidirectional antenna essentially composed two monopoles
    - Generate powerful signals in retricted space
  - Panel
    - Flat devices that focus from only one side of the panel
    - Focused one side
  - Parabolic
    - Used to focus signals from very long distances or weak sources
    - Very directional
  - Yagi
    - Crafted from a straight bar with cross sections to catch specific radio frequencies in
      the direction of the main bar
  - Cantenna
    - Constructed from tubes with one sealed end
    - Focus along the direction of the open end of the tube
- Network devices
  - Firewalls
    - Essential tools in managing and controlling network traffic
    - A firewall is a network device used to filter traffic 
  - Switch (layer 2/3)
    - Repeats traffic only out of the port on which the destination is known to exist
    - Switches offer greater efficiency for traffic delivery, create separate collision domains, 
      and improve the overall throughput of data
  - Routers (layer 3)
    - Used to control traffic flow on networks and are often used to connect similar networks and control traffic flow between the two
    - Can function using statically defined routing tables or they can employ a dynamic routing system
  - Gateways (layer 3)
    - Gateway connects networks that are using different network protocols
    - Known as protocol translators, can be stand-alone hardware devices or a software service
  - Repeaters, Concentrators, and Amplifiers (layer 1)
    - Used to strengthen the communication signal over a cable segment as well as connect
      network segments that use the same protocol
  - Bridges (layer 2)
    - Used to connect two networks (even networks of different topologies, cabling types
      and speeds) in order to connect network segments that use the same protocol
  - Hubs (layer 1)
    - Used to connect multiple systems and connect network segments that use the same protocol
  - LAN Extenders
    - Remote access, multilayer switch used to connect distant networks over WAN links
- LAN & WAN Technlogies
  - WAN connections and communication links can include private circuit technologies and packet-switching technologies
  - Private circuit technologies use dedicated physical circuits
    - Dedicated or leased lines
    - PPP (point-to-point protocol)
    - SLIP (Serial line internet protocol)
    - ISDN (Integrated services digital network)
    - DSL (Digital subscriber line)
  - Packet-switching technologies use virtual circuits instead of dedicated physical circuits
    - X.25, Frame Relay
    - Asynchronous transfer mode (ATM)
    - Synchronous Data Link Control (SDLC)
    - High-Level Data Link Control (HDLC)
- Firewalls
  - Static Packet-Filtering Firewalls (operate at layer 3 and up)
    - filters traffic by examining data from a message header
  - Application-Level Firewalls (operate at layer 7 of OSI model)
    - filters traffic on a single internet service, protocol, or application
  - Circuit-Level Firewalls (example SOCKS)
    - Used to establish communication sessions between trusted partners
    - They operate at the Session Layer (layer 5) of the OSI model
  - Stateful Inspection Firewalls
    - Evaluate the state, session, or the context of network traffic
  - Deep packet Inspection Firewalls
    - A filtering mechanism that operates typically at the application layer in order to filter
      the payload contents of a communication rather than only on the header values
- Firewall and State
  - Stateless
    - Watch network traffic and restrict or block packets based on source/destination addresses or other static values
    - Not 'aware' of traffic patterns or data flows
    - Typically, faster and perform better under heavier traffic loads
  - Stateful
    - Can watch traffic streams from end to end
    - Are aware of communication paths and can implement various IP security functions such as tunnels and encryption
    - Better at identifying unauthorized and forged communications
- Modern Firewalls
  - Firewalls Web Application aka WAF
    - Protect web applications by filtering and monitoring HTTP traffic between a web application and the Internet
    - Typically protects web applications from common attacks like XSS, CSRF, and SQLI
  - Firewalls Next Generation aka NGFW
    - A deep-packet inspection firewall that moves beyond port/protocol inspection and blocking
    - Adds application-level inspection, intrusion prevention, and brings intelligence from outside the firewall
- Types of Firewalls
  - Deep packet inspection
    - Packet inspection inspects and filters both the header and payload of a packet that is
      transmitted through an inspection point
  - Unified Threat Management aka UTM
    - A multifunction device (MFD) composed of several security features in addition to a firewall
    - May include IDS, IPS, a TLS/SSL proxy, web filtering, QoS management, bandwidth throttling, NAT,
      VPN anchoring, and antivirus
  - NAT Network Address Translation Gateway
    - Allows private subnets to communicate with other cloud services and the Internet
      but hides the internal network from Internet users
    - The NAT gateway has the Network Access Control List (NACL) for the private subnets
  - Content/URL filter
    - Looks at the content on the requested web page and blocks request depending on filters
    - Used to block inappropriate content in the context of the situation
- Open-Source vs Proprietary Firewalls
  - Open-Source
    - One in which the vendor makes the license free and allows access to the source code, though it might ask for a donation
    - There is no vendor support with open source, so you might pay a 3rd party to support in a production environment
    - Open source firewalls such as pfsense
  - Proprietary
    - More expensive but tend to provide more/better protection and more functionality and support (at a cost)
    - Many vendors in this space such as Cisco, Checkpoint, Palo Alto, etc..
- Hardware vs Software
  - Hardware
    - Piece of purpose-built network hardware
    - May offer more configurable support for LAN and WAN connections
    - Often has superior throughput versus software because it is hardware designed for the
      speeds and connections common to an enterprise network
  - Software
    - Software based firewalls that you might install on your hardware
    - Provide flexibility to place firewalls anywhere you would like in your organization
    - On servers and workstations, you can run a host-based firewall
- Application vs Host-Based vs Virtual
  - Application
    - Typically catered specifically to application communications
    - Often that is HTTP or Web traffic
    - An example is Next Gen Firewall (NGFW)
  - Host-based
    - An application isntalled on a hsot OS, such as Windows or Linux, both client and server operating systems
  - Virtual
    - In the cloud, firewalls are implemented as virtual network appliances (VNA)
    - Available from both the CSP directly and 3rd party partners
- IDS and IPS
  - IDS (alerts)
    - analyzes whole packets, both header and payload, looking for known events
    - When a known event is detected, a log message is generated
  - IPS (takes action)
    - analyzes whole packets, both header and payload, looking for known events
    - When a known event is detected, packet is rejected
- Types of IDS systems
  - Behavior based
    - Creates a baseline of activity to identify normal behavior and then measures system performance
      against the baseline to detect abnormal behavior
  - Knownledge based
    - Uses signatures similar to the signature definitions used by anti-malware software
  - Both host-based (HIDS) and network-based (NIDS) systems can be knowledge/behavior based or both
- Host-based IDS and IPS
  - Host-based Intrusion Detection System (HIDS)
    - Analyzes whole packets, both header and payload, looking for known events
    - When a known event is detected, a log message is generated
  - Host-based Intrustion Prevention System (HIPS)
    - Analyzes whole packets, both header and payload, looking for known events
    - When a known event is detected, packet is rejected
  - Network-based Intrusion Detection System (NIDS)
    - Analyzes whole packets, both header and payload, looking for known events
    - When a known event is detected, a log message is generated
  - Network-based Intrustion Prevention System (NIPS)
    - Analyzes whole packets, both header and payload, looking for known events
    - When a known event is detected, packet is rejected
- Modes of Operation
  - Inline aka "In-band"
    - NIDS/NIPS placed on or near the firewall as an additional layer of security
  - Passive aka "out-of-band"
    - Traffic does not go through the NIPS/NIDS
    - Sensors and collectors forward alerts to the NIDS
- Network Appliances
  - Sensors and Collectors
    - Can be placed on a network to alert NIDS of any changes in traffic patterns on the network
    - If you place a sensor on the Internet side of the network, it can scan all of the traffic from the Internet
- Secure Network Design
  - Bastion Host (hardened)
    - Computer or appliance that is exposed on the Internet and has been hardened by removing all 
      unnecessary elements, such as services, programs, protocols, and ports
  - Screened Host (most secure)
    - Is a firewall-protected system logically positioned just inside a private network
  - Screened Subnet
    - Similar to the screened host in concept, except a subnet is placed between two routers or firewalls and
      the bastion host(s) is located within that subnet
  - Honeypot
    - Only ENTICE, not ENTRAP
    - For example, allowing download of a fake payroll file would be entrapment
    - Goal is to distract form real assets and isolate in a padded cell
- Network attacks 
  - Teardrop attack
    - Is a denial-of-service (DoS) attack that involves sending fragmented packets to a target machine
  - Fraggle attack
    - Is a denial-of-service (DoS) attack that involves sending a large amount of spoofed UDP traffic to a routers 
      broadcast address within a network
  - Smurf attack
    - Is a denial-of-service (DoS) attack that involves sending a large amount of spoofed ICMP traffic to a routers 
      broadcast address within a network
  - Land attack
    - Layer 4 Denial of service (DoS) attack in which, the attacker sets the source and destination
      information of a TCP segment to be the same
  - Syn Flood
    - Is a form of denial-of-service attack in which an attacker sends a succession of SYN requests to a target's system in 
      an attempt to consume enough server resources to make the system unresponsive to legitimate traffic
  - Ping of Death
    - Employs an oversized ping packet. Max allowed ping packet size is 65,536 bytes

## Domain 5 Identity & Access Management

- Certificate-Based Authentication
  - Digital certificates may be used as an authentication technique for user. service, and device identities
  - certificates used in this process are similar to those that you use to secure websites
  - certificates have both a public and private key
  - certificates usually issued by a certification authority in a public key infrastructre (PKI)
- AAA Protocols
  - Several protocols provide centralized authentication, authorization, and accounting services
  - Network Access Server
    - Is a client to a RADIUS server, and the RADIUS server provides AAA services
  - RADIUS (remote access)
    - Uses UDP and encrypts the password only
  - TACACS+ (admin access to network devices)
    - Uses TCP and encrypts the entire session
  - Diameter (4G)
    - Based on RADIUS and improves many of the weaknesses of RADIUS, but Diameter is not compatible with RADIUS
  - Network access (or remote access) systems use AAA protocols
- Active Directory
  - Kerberos
    - Primary purpose is authentication as it allows users to prove their identity
    - Also provides a measure of confidentiality and integrity using symmetric key encryption, but these are
      not its primary purpose
    - Does not include logging capabilities so it does not provide accountability
    - Pass-the-hash = NTLM
    - Pass-the-ticket = Kerberos
- Authorization Mechanisms
  - Need to Know
    - Ensures that subjects are granted access only to what they need to know for works tasks
    - Subjects with clearance to access is only granted if they actually need it to perform a job
  - Least Privilege
    - Ensures that subjects are granted only the privileges they need to perform their work tasks
    - Also include rights to take action on a system
  - Separation of Duties and Responsibilities
    - Ensures that sensitive functions are split into tasks performed by 2 or more employees
    - Helps prevent fraud and error by creating a system of checks and balances
- Modern Approaches to Least Privilege
  - Just-in-time (JIT) (PIM, PAM)
    - Allows temporary elevation of privilege (usually time-limited) as its needed, revoking privilege at the end of the allowed window
    - Sometimes implemented through ephemeral accounts or a broker and remove access strategy
- Identification and Authentication
  - Identification
    - Subjects claim an identity such as a username
  - Authentication
    - Subjects prove their identity by providing authentication credentials such as the matching password for a username
- Authorization and Accountability
  - Authorization
    - After authenticating subjects, systems authorize access to objects based on their proven identity
  - Accountability
    - Auditing logs and audit trails record events including the identity of the subject that performed an action
- Primary Authentication Factors
  - Something you know (pin or password)
  - Something you have (trusted device)
  - Something you are (biometric)
  - Multifactor Authentication
    - Includes 2 or more authentication factors
    - More secure than using a single authentication factor
    - Password are the weakest form of authentication
    - Password policies help increase their security by enforcing complexity and history requirements
    - Smartcards include microprocessors and cryptgraphic certificates
    - Tokens create onetime passwords
    - Biometric methods identify users based on characteristics such as fingerprints
- Biometrics
  - A method of authentication using an individual's physical characteristics which are unique to the indivdual
  - Fingerprint Scanner
    - Fingerprint scanners are now very common, and used not only in MFA, but various travel, financial, and legal situations
  - Retina Scanner
    - With appropriate lighting, the retina can be accurately identified as the blood vessels of the retina
      absorb light more readily than the surrounding tissue
  - Iris Scanner
    - Confirms the identity of the user by scanning of their iris
  - Both retina and iris scanners are physical devices
  - Voice recognition
    - The voice patterns can be stored in a database and used for authentication
  - Facial Recognition
    - Looks at the shape of the face and characteristics such as mouth, jaw, cheekbone, and noes
    - Light and angle/direction can be a factor, especially in software
    - Microsoft facial recognition, called Windows Hello, was released with Windows 10
    - It uses a special USB infrared camera and as such is bettern than other facial recognition programs
      that can have problems with light
  - Vein
    - Using blood vessels in the palm can be used as a biometric factor of authentication
  - Gait Analysis
    - Gait is the way an individual walks
  - Crossover Error Rate
    - A false acceptance occurs when an invalid subject is authenticated
    - Or called False Positive (Type 2 Error)
    - A false rejection occurs when a valid subject is rejected
    - Or called False Negative (Type 1 Error)
    - FAR=false acceptance rate, FRR=false rejection rate
    - The crossover error rate (CER) identifies the accurancy of a biometric method
    - It shows where the false rejection rate is equal to the false acceptance rate
- Single Sign-On
  - Mechanism that allows subjects to authenticate once and access multiple objects without authenticating again
  - Common SSO methods/standards:
    - SAML
    - SESAME
    - KryptoKnight
    - Oauth
    - OpenID
- SAML, OAUTH, And OpenID
  - Security Assertion Markup Language (SAML)
    - An XML-based open-standard data format for exchanging authentication/authorization data between parties
      specifically between an identity provider and service provider
  - OAuth 2.0
    - An open standard for authorization, commonly used as a way for Internet users to log into 3rd party websites
      using their Microsoft, Google, Facebook, Twitter, etc. accounts without exposing their password
  - OpenID 
    - An open standard, it povides decentralized authentication, allowing users to log into multiple unrelated websites
      with one set of credentials maintained by a 3rd party service reffered to as an OpenID provider
- Access Control Models
  - Discretionary Access Control
    - A key characteristic of the Discretionary Access Control (DAC) model is that every object has
      an owner, and the owner can grant or deny access to any other subjects (Example NTFS)
  - Role Based Access Control
    - A key characteristic is the use of roles or groups
    - Instead of assigning permissions directly to user, user accounts are placed in roles and administrators assign privileges
    - Typically mapped to job roles
  - Rule-Based access control
    - Key characteristic is that it applies global rules that apply to all subjects
    - Rules within this model are sometimes referred to as restrictions or filters (Example firewall)
  - Attribute Based Access Control
    - Key Characteristic is its use of rules that can include multiple attributes
    - Alllows it to be much more flexible than a rule-based access control model (Example SDNs)
  - Mandatory Access Control
    - Key characteristic is the use of lables applied to both subjects and objects
    - For example, if a user has a label of top secret, the user can be granted access to a top-secret
      document. Both subject and object have same lables.
- Security Controls
  - 3 Primary control types are
    - Preventative
    - Detective
    - Corrective
  - Categories of Security Controls
    - Logical/Technical
      - Examples; enc ryption, smart cards, passwords, biometrics, access control lists, constrained interfaces, protocols,
        firewalls, routers, intrusion detection systems, and clipping levels
    - Physical
      - Examples; guards, fences, motion detectors, locked doors, sealed windows, lights, guard dogs, video cameras,
        mantraps, and alarms
    - Administrative
      - Examples; policies, procedures, hiring practices, background checks, data classification, security training, vacation history,
        reviews, work supervision, personnel controls, and testing
- Risk Elements
  - Risk
    - Possibility or likelihood that a threat can exploit a vulnerability and cause damage to assets
  - Asset valuation
    - Identifies value of assets, threat modeling identifies threats against these assets
  - Vulnerability analysis
    - Identifies weaknesses in an organizations valuable assets
- Access Control Attacks
  - Dictionary attacks
    - These are programs with built in dictionaries
    - They would use all dictionary words to attempt and find the correct password
  - Brute-force
    - Attempts to break the password by trying all possible words
  - Spoofed logon screens
    - Is to implement a fake logon screen, and when a user attempts to login, the logon screen will send the username
      and password to the hacker
  - Sniffer attack
    - Uses a packet capture tool such as Wireshark to capture, analyze, and read data sent over a network
    - Attackers can easily read data sent over a network in cleartext
  - Spoofing attack
    - Is pretending to be something or someone else, and it is used in many types of attacks, including access control attacks
    - Attackers often try to obtain the credentials of users so that they can spoof the user's identity
    - Spoofing attacks include email spoofing, phone number spoofing, and IP spoofing
  - Social Engineering 
    - An attempt by an attacker to convince someone to provide info or perform an action they wouldnt normally
      perform such as clicking on a malicious link    
    - Best defense is security awareness training
  - Phishing
    - Commonly used to try to trick users into giving up personal information (such as user accounts and passwords),
      click a malicious link, or open a malicious attachment
    - Spear phishing targets specific groups of users
    - Whaling targets high-level executives
    - Vishing uses VoIP technologies
  - Access aggregation
    - Type of attack that combines, or aggregates, non-sensitive information to learn sensitive information and is used in reconnaissance attacks
- Preventing Access Control Attacks
  - For spoofed logon screens - Best prevention is to have secure endpoints where fake logon screens cannot be implemented
- Other Attacks
  - Tempest 
    - Allows the electronic emanations that every monitor produces to be read from a distance (effective on CRT monitors)
    - Shoulder surfing for monitor displays
  - White Noise
    - Broadcasting false traffic at all times to mask and hide the presence of real emanations
- Asset Management
  - RFID, Barcoding, and Inventory
    - Represent the ability to prevent theft which reduces risk

## Domain 6 Security Assessment and Testing

- Security Assessment and Testing
  - Security assessment and testing programs
    - Provides a mechanism for validating the ongoing effectiveness of security controls, with a variety of 
      tools to validate controls
      - Vulnerability assessments
      - Penetration testing, Software testing
      - Audits
      - Security management tasks
    - Every org should have a security assessment and testing program defined and operational
  - Vulnerability assessments vs Penetration Tests
    - Vulnerability assessments
      - Use automated tools to search for known vulnerabilities in systems, applications, and networks
      - Flaws may include missing patches, misconfigurations, or faulty code that
        expose the organization to security risks
    - Penetration Tests
      - Uses these same tools but supplements them with attack techniques where an assessor attempts to exploit
        vulnerabilities and gain acccess to the system
      - Few strategies
        - War Dialing - Bank of Modems
        - Sniffing - Monitor the Nework
        - Eavesdropping - Listening
        - Dumpster diving - Just like it sounds
        - Social Engineering - Human manipulation
- Security Process Data
  - Employment Policies and Practices
    - Termination process and background checks
  - Roles and Responsibilities
    - Management sets the standard and verbalizes the policy
  - Security awareness training
    - Prevents Social Engineering, helps with phishing 
- Software Testing
  - Software Testing
    - Techniques verify that code functions as designed and does not contain security flaws
  - Code Review
    - Uses a peer review process to formally or informally validate code before deploying it in production
  - Interface Testing
    - Assesses the interactions between components and users with API testing, user interface testing,
      and physical interface testing
- Static vs Dynamic Testing
  - Static Software testing
    - Techniques include code reviews, evaluate the security of software WITHOUT running it by analyzing either the source
      code or the compiled application
  - Dynamic Software testing
    - Evaluates the security of software in a RUNTIME environment and is often the only option for organizations deploying appplications
      written by someone else
- Fuzzing
  - Uses modified inputs to test software performance under unexpected circumstances
  - Modifies known inputs to generate synthetic inputs that may trigger unexpected behavior
  - Generational fuzzing develops inputs based on models of expected inputs to perform same task
- Security Management Oversight
  - Security managers must perform a variety of activities to retain proper oversight of the information security program
  - Log reviews
    - Particularly for administrator activities, ensure that systems are not misused
  - Account management reviews
    - Ensure that only authorized users retain access to information systems
  - Backup verification (the most important)
    - Ensures that the organizations data protection process is functioning properly
  - Key performance and risk indicators
    - Provide a high-level view of security program effectiveness
- Internal and External Audits
  - Conduct or facilitate internal and 3rd party audits
  - Security audits
    - Occur when a 3rd party performs an assessment of the security controls protecting an organizations
      information assets
  - Internal audits
    - Performed by an organizations itnernal staff and are intended for management use
  - External audits are performed by a 3rd party audit firm and are generally intended for the organizations
    governing body

## Domain 7 Security Operations

- Intelligence in Threat Modeling
  - User and Entity Behavior Analytics (UEBA)
    - Entity behavior is collected and input into a threat model
    - Model establishes a baseline of "normal" based on historical data
    - Enables analysis to uncover more details around anomalous events
    - "Automated investigation" feature in some platforms
  - Threat Intelligence (Threat feeds)
    - Activities an organization undertakes to educate itself about changes in the threat landscape 
    - Often a feed containing malicious entities ingested by cybersecurity tools
    - A single feed may be compromised of many sources, including open-source intelligence
    - Entity = IP, website, threat actor, file hash, and more
- The Role of AI & ML
  - Analyzing and improving cybersecurity posture is no longer a human-scale problem
  - Artificial Intelligence (AI) based tools for cybersecurity have emerged to help information security
    teams reduce breach risk and improve their security posture efficiently and effectively
  - Along with AI, machine learning (ML) has become critical technologies in information security, in quickly analyzing millions of events and 
    identify many different types of threats
  - Know that AI and ML factor in anti-malware, SIEM, IPS/IDS, and IDaas, and more
- Limiting Access & Damage
  - Need-to-know and principle of least privilege are two standards
  - They limit access to data and systems 
  - They help prevent security incidents
  - They help limit the scope of incidents when they occur
- Preventing Fraud and Collusion
  - Collusion
    - Is an agreement among multiple persons to perform some unauthorized or illegal actions
  - Separation of duties
    - Basic security principle that ensures that no single person can control all the elements of a
      critical function or system
  - Job rotation
    - Employees are rotated into different jobs, or tasks are assigned to different employees
  - Implementing these policies helps prevent fraud by limiting actions individuals can do without colluding with others
- Monitored Privileged Operations
  - Privileged entities are trusted, but they can abuse their privileges
  - Its important to monitor all assignment of privileges and the use of privileged operations
  - Goal - ensure that trusted employees do not abuse the special privileges they are granted
  - Monitoring these operations can detect many attacks also
- The inforation lifecycle
  - Creation
    - Can be created by user - user creates a file
    - Can be created by a system - a system logs access
  - Classification
    - To ensure that its handled properly its important to ensure data is classified ASAP
  - Storage
    - Data should be protected by adequate security controls based on its classification
  - Usage
    - Refers to anytime data is in use or in transit over a network
  - Archive
    - Archival is sometimes needed to comply with laws or regulations requiring the retentiion of data
  - Destruction
    - When data is no longer needed it should be destroyed in such a way that it is not readable
- Service-Level Agreements
  - Stipulate performance expectations such as maximum downtimes and often include penalties if 
    the vendor doesnt meet expectations
  - Generally used with vendors
- Secure Provisioning
  - Resources includes ensuring that resources are deployed in a secure manner and maintained in
    a secure manner throughout their lifecycles
  - example: deploy a PC from a secure image
- Virtual assets
  - Virtual assets include:
    - Virtual machines (VM)
    - Virtual Desktop Infrastructre (VDI)
    - Software-defined networks (SDN)
    - Virtual storage area networks (SAN)
  - Hypervisors are the primary component that manages virtual assets, but also provide attackers with an
    additional target
  - Both hypervisors and VMs need to be patched
  - Security issues with cloud-based assets
    - Shadow IT and CASB
    - Shared Responssibility Model
    - Cloud Service Provider (CSP) provies least amount of maintenance and good security
- Configuration and Change Management
  - Can prevent incidents and outages
  - Configuration Management
    - Ensures that systems are configured similarly, configurations are known and documentated
  - Baselining
    - Ensures that systems are deployed with a common baseline or starting point, and imaging
      is a common baselining method
  - Change Management
    - Helps reduce outages or weakened security from unauthorized changes
  - Versioning
    - Uses a labeling or numbering system to track changes in updated versions of software
  - Requires changes to be requested, approved, tested, and documented
- Patch Management aka Update Management
  - Ensures that systems are kept up-to-date with current security patches
  - will evaluate, test, approve, and deploy patches
  - system audits verify the deployment of approved patches to system
  - intertwined with change and configuration management to ensure that documentation reflects changes
  - Orgs without patch management will experience outages from known issues that could have been prevented
- Patch Management Program
  1. Evaluate Patches
  2. Test Patches
  3. Approve the Patches
  4. Deploy the Patches
  5. Verify the Patches are deployed
- Vulnerability Management
  - Vulnerability Management
    - Includes routine vulnerability sans and periodic vulnerability assessments
  - Vulnerability Scanners
    - Can detect known security vulnerabilities and weaknesses, absence of patches or weak passwords
  - Vulnerability Assessments
    - Extend beyond just technical scans and can include reviews and audits to detect vulnerabilities
- Managing Incident Response (DRMMRRRL)
  1. Detection - Monitoring tools, IPS, firewalls, users, notification to management and/or helpdesk
  2. Response - Triage (is it really an incident) - limiting damage
  3. Mitigation - First containment effort or step, create team - contain an incident
  4. Reporting - To relevant stakeholders (customers, vendors, law) 
  5. Recovery - Return to normal operations
  6. Remediation - Root cause is addressed
  7. Lessons Learned - Helps prevent recurrence, improve IR process
- Denial-Of-Service Attacks
  - SYN Flood attack
    - Disrupts the TCP three-way handshake
  - Smurf attack
    - Employs an amplification network to send numerous response packets to a victim
  - Ping-of-death attack
    - Send numerous oversized ping packets to the victim, cuasing victim to freeze, crash, or reboot
- Botnets, controllers, and bot herders
  - Botnet
    - A collection of compromised computing devices (often called bots or zombies)
  - Bot herder 
    - Criminal who uses a command-and-control server to remotely control the zombie
    - Often use the botnet to launch attacks on other systems, or to send spam or phishing emails
- Honeypot, padded cell, pseudo flaws
  - Honeypot
    - System that often has pseudo flaws and fake data to lure intruders (lures and distracts attacks)
    - As long as attackers are in the honeypot, they are not in the live network ... and admins can observe
    - Some IDSs have the ability to transfer attackers into a padded cell after detection
- Blocking Malicious Code
  - Anti-malware software
    - With up-to-date definitions installed on each system, at the boundary of the network
      , and on email servers
  - Policies
    - Enforce basic security principles, like principle of least privilege, prevent regular users
      from installing potentially malicious software
  - Education
    - Educating users about the risks and the methods attackers commonly use to spread viruses
      helps users understand and avoid dangerous behaviors
- Penetration Tests
  - Should not be done without express consents
  - Can result in damange so should be done on isolated systems
  - 3 types
    - Black box (zero knowledge)
    - White box (Full knowledge)
    - Gray box (partial knowledge)
- IDS vs IPS Response
  - IDS
    - Can respond passively by logging and sending notifications or actively by changing the environment
  - IPS
    - Is placed in line with the traffic and includes the ability to block malicious traffic before it reaches the target
- Types of IDS
  - HID
    - Monitor activity on single system only
    - Drawback is attackers can discover and disable them
  - NID
    - Monitor activity on a network
    - Isnt as visible to attackers
- Espionage & Sabotage
  - Espionage (external)
    - When a competitor tries to steal information, and they may use an internal employee
  - Sabotage (inside)
    - Malicious insiders can perform sabotage against an org if they become disgruntled for some reason
- Zero-day exploits
  - Basic security practices can often prevent
- Log Files
  - Data is recorded in databases and different types log files
  - Common log files:
    - Security logs
    - System logs
    - Application logs
    - Firewall logs
    - Proxy logs
  - Should be protected by centrally storing them and using permissions to restrict access
  - Archived logs should be set to read-only to prevent modifications
- Monitoring
  - A form of auditing that focuses on active review of the log file data
  - Used to hold subjects accountable for their actions
  - Also used to monitor system performance
  - Tools such as IDSs or SIEMs automate monitoring and provide real-time analysis of events
  - Audit trails
    - Records created by recording information about events and occurances into one or more databases or log files
  - Used to reconstruct an event, to extract information about an incident
  - Used to prove or disprove culpability
  - A passive form of detective security control
- Sampling
  - Sampling
    - The proces of extracting elements from a large body of data to contruct a meaningful 
      representation or summary of the whole
  - Statistical sampling
    - Uses precise mathematical functions to extract meaningful information from a large 
      volume of data
  - Clipping
    - Is a form of nonstatistical sampling that records only events that exceed a threshold
- Maintaining Accountability
  - Accountability
    - Maintained for individual subjects using auditing
    - Logs record user activities and users can be held accountable for their logged actions
    - Directly promotes good user behavior and compliance with the organizations security policy
- Security Audits and Reviews
  - Help ensure that management programs are effective and being followed
  - Commonly associated with account management practices to prevent violations with least privilege
    or need-to-know principles
  - Can also be performed to oversee many programs and processes
    - Patch management
    - Vulnerability management
    - Change management
    - Configuration managmenet
- Frequency of IT Security Audits
  - Auditing
    - A methodical examination of an environment to ensure compliance with regulations and to detect abnormalities
      , unauthorized occurrences, or outright crimes
    - Serves as a primary type of detective control
    - Frequency is based on risk
    - Degree of risk also affects how often an audit is performed
- Concept of Due Care
  - Auditing & Due Care
    - Security audits and effectiveness reviews are key elements in displaying due care
    - Without them, senior management will likely be held accountable and liable for any asset losses that occur
    - Act with common sense, prudent management, responsible action
- Controlling access to Audit Reports
  - Audit reports often contain sensitive information
  - Audit reports include
    - Purpose and scope of the audit
    - Results discovered or revealed
    - Sensitive information such as problems, standards, causes, and recommendations
  - Only people with sufficient privilege should have access
- User entitlements and Access Reviews
  - Access Review
    - Ensures that object access and account management practices support the security policy
  - User Entitilement Audit
    - Ensure that the principle of least privilege is followed and often focus on privileged accounts
- Audit Access Controls
  - Can track logon success and failure of any account
  - Can include resource (object) access and action performed on resources
  - Intrusion Detection Systems can monitor these logs and easily identify
    attacks and notify administrators
  - Often automated, auto-reporting, and supported by AI
- Security Operations
  - Computer Crime
    - A crime (or violation of a law or regulation) that is directed against, or directly involves, a computer
    - Categories of Computer Crime:
      - Military and Intelligence attacks
      - Business attacks
      - Financial attacks
      - Terrorist attacks
      - Grudge attacks
      - Thrill attacks
- Electronic Discovery
  - Organizations expecting lawsuit have a duty to preserve digital evidence in a process called eDiscovery
  - eDiscovery process includes:
    - Information identification and governance
    - Preservation and collection
    - Processing, review, analysis
    - Production, and presentation
  - Often uses tagging, classification, target specific custodian
- Gathering Info in Investigations
  - Gather sufficient information from the equipment, software, and data from equipment requires
  - Possession
    - Must have possession of equipment, software, or data to analyze it and use it as evidence
  - Modification
    - Must acquire the evidence without modifying it or allowing anyone else to modify it
  - Law enforcement establishes chain of evidence aka chain of custody to document all who handle it
- Alternatives to Confiscating Evidence
  - Voluntary surrender
    - Person who owns the evidence could voluntarily surrender it for investigation
  - Subpoena
    - Could be used to compel the subject to surrender the evidence
  - Search warrant
    - Most useful when you need to confiscate evidence without giving the subject an opportunity to alter it
- Retaining Investigatory Data
  - You will lose valuable evidence unless you ensure that critical log files are retained for a reasonable period of time
  - You can retain log files and system status information either in-place or in archives
  - Data retention should be defined in security policies
- Evidence
  - Best - Original
  - Secondary Evidence - Copy
  - Direct - Proves or disproves an act based on the five sense
  - Conclusive - Incontrovertible, overrides all other types
  - Circumstantial - Inference from other info
  - Corroborative - Supporting evidence but cannot stand on its own
  - Opinions - Expert and non-expert
  - Hearsay - Not based on first-hand knowledge
  - Evidence must be relevant, complete, sufficient, and reliable
- Evidence Admissibility
  - Real Evidence
    - Consists of actual objects that can be brought into the courtroom
  - Documentary Evidence
    - Consists of written documents that provide insight into the facts
  - Requirements for evidence to be Admissible:
    - Evidence must be relevant to a fact or issue in the case
    - The fact must be material to the case
    - The evidence must be competent or legally collected
    - Evidence is considered "competent" if it complies with certain traditional notions of reliability
- Important of collecting Evidence
  - As soon as you discover an incident ...
  - You must being to collect evidence and as much information about the incident as possible
  - Evidence can be used in a subsequent legal action or in finding attacker identify
  - Evidence can also assit you in determining the extent of damage
- Natural Disasters
  - Common types
    - Earthquakes
    - Floods
    - Storms
    - Tsunamis
    - Volcanic eruptions
- Man Made Disasters
  - Explosions
  - Electrical fires
  - Terrorist acts
  - Power outages
  - Other utility failures
- Recovery Site Types
  - Cold site
    - A "recovery" cold site is essentially just data center space, power, and network connectivity thats
      ready and waiting for whenever you might need it
    - If disaster stricks, your engineering and logistical support teams can readily help you move your hardware
      into the data center and get you back up and running
    - Cost = Low, Effort = High
  - Warm site
    - A "preventative" warm site allows you to pre-install your hardware and pre-configure your bandwidth needs
    - If disaster strikes, all you have to do is load your software and data to restore your business systems
    - cost = Medium, effort = Medium
  - Hot site
    - A "proactive" hot site allows you to keep servers and a live backup site up and running in the event
      of a disaster. You replicate your production environment in that data center
    - This allows for an immediate cutover in case of disaster at your primary site. A hot site
      is a must for mission critical sites
    - cost = High, effort = Low
  - Service Bureau
    - A company that leases computer time
    - Service bureaus own large server farms and often fields of workstations
    - May be onsite or remote
  - Mobile Site
    - Nonmainstream alternatives to traditional recovery sites
    - They typically consist of self-contained trailers or other easily relocated units
  - Multiple sites
    - May mix-and-match some combination of the aforementioned options
- RPO and RTO
  - Recovery Point Objective (RPO)
    - Is the age of files that must be recovered from backup storage for normal operations to resume if a
      system or network goes down
  - Recovery Time Objective (RTO)
    - Is the duration of time and a service level within which a business process must be restored after a disaster in 
      order to avoid unacceptable consequences associated with a break in continuity
- Mutual Assistance Agreements (MAAs)
  - Benefits of an MAA
    - Provide an inexpensive alternative to disaster recovery sites
  - Risk of an MAA
    - Organizations participating in an MAA may also be shut down by the same disaster, and
      MAAs raise confidentiality concerns
  - Why are MAAs uncommon
    - They are difficult to enforce
  - Business Continuity Planning (BCP)
    - 4 main steps
      - Project scope and planning
      - Business impact assessment
      - Continuity planning
      - Approval and implementation
    - Goal: Efficient response to enhance a companys ability to recover from a disruptive event promptly
- BCP Definitions
  - BCP (Business Continuity Plan)
    - The overall organization plan for "how to" continue business
  - COOP (Continuity of Operations Plan)
    - Plan for continuing to do business until the IT infrastructure can be restored
  - DRP (Disaster Recovery Plan)
    - Plan for recovering from an IT disaster and having the IT infrastructure back in operation
  - BRP (Business Resumption Plan)
    - Plan to move from the disaster recovery site back to your business environment or back to normal operations
  - MTBF (Mean Time Between Failures)
    - A time determination for how long a piece of IT infrastructure will continue to work before it fails
  - MTTR (Mean Time To Repair)
    - A time determination for how long it will take to get a piece of hardware/software repaired and back on-line
  - MTD (Max Tolerable Downtime)
    - The amount of time we can be without the asset that is unavailable BEFORE we must declare a disaster and initiate
      our disaster recovery plan
- Goals of DR and BCP
  - Minimizing the effects of a disaster by:
    - Improving responsiveness by the employees in different situations
    - Easing confusion by providing written procedures and participation in drills
    - Helping make logical decisions during a crisis
- 5 types of Disaster Recovery Plan Tests
  - Read-Through
    - You distribute copies of disaster recovery plans to the members
      of the disaster recovery team for review
  - Structured Walk-through aka "table-top" exercise
    - Members of the disaster recovery team gather in a large conference room and role-play a disaster scenario
    - The exact scenario is known only to the test moderator, who presents the details to the team at the meeting
    - The team members refer to the document and discuss the appropriate responses to that particular type of disaster
  - Simulation Test
    - Similar to structured walk-through, except some of the response measures are then tested (on non-critical functions)
  - Parallel test
    - Involves relocating personnel to the alternate recovery site and implementing site activation procedures
    - The employees relocated to the site perform their disaster recovery responsibilities just as they 
      would for an actual disaster
  - Full interruption test
    - Like parallel tests but involves actually shutting down operations at the primary site and
      shifting them to the recovery site
  - Recovery Team (recover)
    - Used to get critical business functions running at the alternate site
  - Salvage Team (restore)
    - Used to return the primary site to normal processing conditions
- Backup Strategies
  - Electronic Vaulting
    - Used to transfer database backups to a remote site as part of a bulk transfer
  - Remote Journaling
    - Transmitting only the journal or transaction logs to the off-site facility 
      and not the actual files
  - Remote Mirroring
    - A live database server is mainted at the backup site
    - The most advanced database backup solution (and also tends to be the most expensive of these)
- Categories of Disruption
  - Non-Disaster
    - Disruption in service from device malfunction or user error
  - Disaster 
    - Entire facility unusable for a day or longer
  - Catastrophe
    - Major disruption that destroys the facility altogether
    - Requires a short term and long term solution

## Domain 8 Software Development Security

- Devops and Devsecops
  - Code Repos
    - Where source code and related artificats such as libraries are stored
      - Do not commit senstive information
      - Protect access to your code repos
      - Sign your work
      - Keep your development tools up-to-date
      - Git the worlds most widely used modern version control system
  - Code libraries
    - Code libraries for some important core fucntions and can improve application security and reduce risk
    - Certain languages are prone to certain types of attacks
    - In C use of safe memory allocation and string manipulation can reduce risk of buffer overflow
  - Runtime
    - Describes period of time during which a software program is running
    - Where DAST evaluates security of an application
    - Assessing software securtiy at runtime is generally the only option for purchased software
  - CICD 
    - Implementing identity and access management (including MFA)
    - Store secrets securely and scan code to ensure no hard-coded secrets
    - Implement role-based access control (and least privilege) to the environment
    - Automate vulnerability scanning in your CICD pipeline
    - Release versioning will improve recoverability and issues tracking
- Configuration Management
  - Software Configuration Management (SCM)
    - Baselining is an important component of configuration management
    - Baseline is a snapshot of a system or application at a given point in time
    - Should also create artifacts that may be used to help understand system configuration
    - System and component-level versioning
  - Static Application Security Testing (SAST)
    - Analysis of computer software performed without actually executing programs
    - Tester has access to the underlying framework, design, and implementation
    - Requires source code
  - Dynamic Application Security Testing (DAST)
    - A program which communicates with a web application (executes the application)
    - Tester has no knowledge of the technologies or frameworks
      that the application is build on
    - No source code required
- Relational Database MGMT Systems
  - Tables (relations)
    - Contains a number of attributes, or fields. Each attribute corresponds to a column in the table
  - Rows (records/tuples)
    - A data recod within a table. Each row, which represents a complete record of specific item data, holds different data within the same structure
  - Columns (fields/attributes)
    - A set of data values of a particular type, one value for each row of the database
  - Candidate Keys (one or more per table)
    - A subset of attributes that can be used to uniquely identify an record in a table
    - No 2 records in the same table will ever contain the same values for all attributes composing a candidate key
  - Primary Key
    - Selected from the set of candidate keys for a table to be used to uniquely identify the records in a table
    - Each table has only one primary key, selected by the database designed from the set of candidate keys
  - Foreign Key
    - Used to enforce relationships between two tables also known as referential integrity
    - Ensures that if one table contains a foreign key, it corresponds to a still existing
      primary key in the other table in the relationship
- RDBMS Threats
  - Aggregation
    - Ability to create sensitive information by COMBINING non-senstive data from separate sources
  - Inference
    - Ability to deduce or assume sensitive information from observing non-sensitive pieces of information
- Types of Storage
  - Primary (or RAM)  memory
    - Consists of the main memory resources directly available to a systems CPU
    - Normally consists of volatile RAM and is usually the most high-performance storage available
  - Secondary Storage
    - Consists of more inexpensive, nonvolatile storage resources available to a system for long term user
    - Include magnetic and optical media such as tapes, disks, hard drives, flash drives, and compact 
      disc/digital versatile disc (CD/DVD) storage
  - Virtual Memory
    - Allows a system to simulate additional primary memory resources through the use of secondary storage
  - Virtual Storage
    - Allows a system to simulate secondary storage resources through the use of primary storage
    - Most common example is RAM disk that presents itself to the OS as a secondary storage but is
      actually implemented in volatile RMA
    - Provides a very fast file system for apps but no recovery capability
  - Random access storage
    - Allows the OS to request contents from any point within the media
  - Sequential access storage (magnetic tape)
    - Requires scanning through the entire media from the beginning to reach a specific address
  - Volatile storage (RAM)
    - Loses its contents when power is removed from the resource
  - Nonvolatile storage (Magnetic/optical media and Nonvolatile RAM)
    - Does not depend upon the presence of power to maintain its contents
- Machine Learning and Neural Networks
  - Expert Systems
    - Consist of two main components: a knowledge base that contains a series of "if/then" rules
      and an inference engine that uses that information to draw a conclusion  about other data
  - Machine Learning
    - Techniques that attempt to algorithmically discover knowledge from datasets
  - Neural Networks
    - Simulate function of the human mind by arranging a series of layered calculations to solve problems 
    - Requires extensive training on a particular problem before they can offer solutions
- Systems Development Modules
  - Agile
    - Place an emphasis on the needs of the customer and quickly developing new functionality
      that meets those needs in an iterative fashion
    - Based on 4 principles
      - Individuals and interactions over processes and tools
      - Working software over comprehensive documentation
      - Customer collaboration over contract negotiation
      - Responding to change over following a plan
  - Waterfall 
    - Describes a sequential development process that results in the development of a finished product
    - 7 Steps
      - System Requirements
      - Software Requirements
      - Preliminary Design
      - Detailed Design
      - Code and Debug
      - Testing
      - Ops & Maintenance
  - Spiral
    - Uses several iterations of waterfall model to produce a number of fully specified 
      and tested prototypes
    - known as model of models
    - Each loop of the spiral results in the development of a new system prototype
    - Allows developers to return to the planning stages as demands change
- Software Development Maturity Models
  - Helps software organizations improve maturity and quality of their software processes by implementing an 
    evolutionary path from ad hoc, chaotic processes to mature, disciplined software processes
  - Know SW-CMM and IDEAL models
- Software Capability Maturity Model (SW-CMM)
  - 5 steps for measuring software development orgs
    1. Initial - No plan
    2. Repeatable - Basic lifecycle mgmt
    3. Defined - Formal, documented SW development processes
    4. Managed - Quantitative measures to gain detailed understanding
    5. Optimized - Continous development process w/ feedback loops
- IDEAL model
  - Initiating 
    - Business reasons outlined, support & infrastructure for initiative put in place
  - Diagnosing 
    - Engineers analyze current state of org & make recommendations for change
  - Establishing
    - Org takes recommendations & develops plan to achieve those changes
  - Acting
    - Plan put into action. Org develops solutions, tests, refines & implements
  - Learning 
    - Org continuously analyzes efforts and results, proposes new actions to drive better results
- Change and Configuration Management
  - Request Control
    - Provides an organizad framework within which users can request modifications, managers can conduct
      cost/benefit analysis, and developers can prioritize tasks
  - Change Control
    - Used by developers to re-create the situation encountered by the user and
      analyze the appropriate changes to remedy the situation
  - Release Control (changes = code changes)
    - Once the changes are finalized, they must be approved for release through the release control procedure
    - Should also include acceptance testing to ensure that any alterations are understood and functional
- Antivirus Software
  - Software Testing
    - Thoroughly test any software before distributing it internally (or releasing it to marktet)
    - The programming team should develop special data sets that exercise all paths of the software
      to the fullest extent possible
- Virus Propagation Techniques
  - File Infection (.exe and .com on Windows)
    - Infect different types of executable files and trigger when the OS attempts to execute them
  - Service injection
    - Escape detection by injecting themselves into trusted runtime processes of the
      OS, such as svchost.exe, winlogin.exe, and explorer.exe
  - Boot Sector Infection
    - Infect the legitmate boot sector and are loaded into memory during the OS 
      load process
  - Macro Infection
    - Infect and spread through code in macros (often using Visual Basic for Apps in MS office docs)
- Antivirus Software
  - Use signature-based detection algorithms to look for telltale patterns of known viruses
  - It is critical signatures are updated frequently
  - Today, many use behavior based detection monitoring target systems for unusual activity and either
    blocking it or flagging it, even if the software does not match a known malware signature
- Techniques to compromise password security
  - Password Crackers
    - Designed to take credential data stolen in a data breach or other hack and extract passwords from it
  - Dictionary attacks
    - Uses a large dictionary file with thousands of words and then runs an encryption function against all words to 
      obtain their encrypted equivalents
  - Social Engineering attacks
    - Consists of simply calling the user and asking for their password or posing as a technical support representative
      or other authority figure who needs information immediately
  - Rootkit (escalation of privilege)
    - Freely available on the internet, used as a 2nd step by attackers exploit known
      vulnerabilities in various OS enabling attackers to elevate privilege
- Application Attacks
  - Buffer overflow
    - Exist when a developer does not validate user input to ensure that it is an appropriate size
      (allows Input that is too large can "overflow" memory flow)
  - Back Door (often used during development and debugging)
    - Undocumented command sequences that allow individuals with knowledge
      of the back door to bypass normal access restrictions
  - Time-of-Check-to-Time-of-Use
    - A timing vulnerability that occurs when a program checks access
      permissions too far in advance of a resource request
- Web App Vulnerabilities
  - Cross-site scripting (XSS)
    - A type of injection, in which malicious scripts are injected into otherwise benign and trusted websites
    - Occur when an attacker uses a web application to send malicious code to a different end user
  - SQL Injection attacks
    - Use unexpected input to a web application to gain unauthorized 
      access to an underlying database
- Network Recon Techniques
  - IP Probes
    - Automated tools simply attempt to ping each address in a range
    - Systems that respond to the ping request are logged for further analysis
  - Port Scans
    - Scans a system for open/listening ports. Often, web servers, file servers, 
      and other servvers supporting critical operations are prime targets
  - Vulnerability scans
    - Used discover specific vulnerabilities ina system 
    - Popular tools for this purpose include Nessus, OpenVAS, Qualys, Core Impact
- Protection rings
  - Ring 0 - kernel
  - Ring 1 - Device drivers
  - Ring 2 - Device drivers
  - Ring 3 - Applications  
- The Software Development Lifecycle (Real Developers Ideas Take Effort)
  1. Requirements analysis
  2. Design
  3. Implementation 
  4. Testing
  5. Evolution
- Concentric Circle Security
  - Several mutually independent security applications, processes, or services that operate
    toward a single common goal
  - Avoids a monolithic security stance
  - Every individual security mechanism has a flaw or a workaround
  - Intelligent combination of countermeasures (layered defense/ defense in dpeth) will resist 
    significant and persistent attempts of compromise
- Acquired Software security impact
  - Operating system attacks
    - Attackers always try to search for operating system vulnerabilities like
      buffer overflow, OS bugs, unpatched OS
  - Application-level attacks
    - overflow, active content, cross-site script, denial of service, SQL Injection,
      session hijacking, phishing
  - Shrink Wrap Code attacks
    - An act of exploiting holes in unpatched or poorly configured software you
      buy and install
  - Misconfiguration attacks
    - Target poorly configured service or device, or one left in default confguration (like WIFI router left in default setting)




  





## Balh

- blah

## Blah 2

- blah 2

## Balh

- blah

## Blah 2

- blah 2

## Balh

- blah

## Blah 2

- blah 2

## Balh

- blah

## Blah 2

- blah 2

## Balh

- blah

## Blah 2

- blah 2