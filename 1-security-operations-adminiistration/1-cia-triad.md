# Security Operations and Administration

## CIA Triad

- Confidentiality
    - Pretection of information from unauthorized disclosure
    - Privacy
        - Protection of user data (GDPR)
    - Secrecy
        - Goverment information

- Integrity
    - Protection of information and infomration process flows from improper or unauthorized modifications

- Availability
    - Data and systems are available when required
        - Network
        - Applications
        - Hardware

- Sensitivity and criticality
    - Enforcement of CIA triad is based on the requirements to protect sensitivity and criticality
        - Sensitivity
            - How much could an organization or persom be harmmed by a loss of confidentiality or integrity
        - Criticality
            - How much could an organization or person be harmed by loss of availability

## Enforcement of CIA triad
    - Reasons for confidentiality
        - Laws and regulations
            - Personally Identifiable Information (PII)
            - Protected Health Information (PHI)
        - Competitive Advantage
            - Research
            - Trade Secrets
            - Contracts and agreements
                - NDA
                - Customer expectations
    - Enforce Confidentiality
        - Access Controls
            - Encryption
            - Principle of least privilege
            - Need to know
        - Masking data inputs
        - Obfuscation
        - Bit Splitting
        
    - Reasons for Availability
        - Ensure information and systems are accessible when required
            - Health and safety
            - Industrial operations
                - Industrial control systems
        - Meet contractual obligations
        - Ensure customer trust
    - Enforce Availability
        - Backups
            - Full, incremental, and differential
            - Journal/logging
            - Transactions, applications, operating systems, etc.
            - RAID
            - Clusters
            - Replication
                - Equipment
                - Networks
                - Personnel
                - Facilities
                - Supply chain - more than on supplier
                - Cloud providers
    - Enforce Integrity
        - Regulations
            - Financial transacitons
            - Healthcare
        - Customer Trust
        - Accountability
        - Checksum
        - Check Digits
        - Parity bits
        - Message Authentication Codes (MAC)
        - Hash/digest algorihms
        - Header and trailer records
        - Data encryption

        - Seperation/segregation of Duties
            - Dividing a process into seperate parts. Each part completed by a different entity or person
            - No one controls the entire transaction

    - Non-repudiation
        - Sender is provided proof of delivery
        - Recipient is provided proof of sender identity
        - Neither party can deny having processed information

        - Digital Signature
        - Public Key Infrastructure
        

            










