# Security Controls

- Controls are used to address risk
- Controls may be managerial, technical, or physical - often a combination of all three
- Risk identification justifies the implementation of security controls
- Assessment of controls should indicate their effectiveness in mitigating the identified risk
- Controls should be built into the business process

## Risk and Controls

- Threat source
  - Natural event
  - Internal or external party
  - Hardware Failure
  - Hacker
- Threat Event
  - Threat used by threat source
  - Threat event exploits a vulnerability
  - Different types of threat events exploit different types of vulnerabilities and have differing levels of impact
  - Malware
- Vulnerability
  - Weakness or gap that allows an attack against an asset
  - Unpatched system
- Asset
  - Business process

- These items make up the calculation of risk
- Unacceptable levels of risk require implementing a control

## Types of Controls

- Directive
  - Tells us what we can or can't do
- Deterrent
  - Discourage us from doing something
- Preventative
  - Stop us from doing something
- Detective
  - Detect if we have done something
- Corrective
  - Regain control in the event of an incident
- Recovery
  - Get back to normal

- ### Managerial/Administrative

  - Policies
    - Polices are 'what we want to do'
    - Driven by laws
    - Strategy - Influenced by risk
    - Based on strategy (is the business healthcare, retail, etc)
    - Endorsed by management
    - Aligned with organization culture
    - High level/non technical
    - Up to date and have an owner
    - Communicated
    - Allow for exceptions to policies
  
    - Functional polices
      - Technical - focused on a single topic
      - Changed/updated as required

  - Procedures
    - Procedures are 'how we do it'
    - Step by step action (how to setup a new user)
    - Ensure things are done in a repeatable and consistent way
  
  - Standards
    - 2 Types of standards
    - Based on a standards document
      - ISO/IEC 27001
    - May be standard for equipment
      - Consistency of training, better pricing, etc
        - Hardware standards - 'we use hardware from the company'
        - Software standards - 'we use this specific software'
  - Baselines
    - Configuration 
      - Mandated configuration
        - Password length
        - Hardware or software configuration
          - Operating software hardening
        - Virtual Machines
  - Asset Management
    - Information Classification

  - Directive
    - Policy
  - Deterrent
    - Disciplinary action
  - Preventative
    - Separation of duties
  - Detective
    - Audit
  - Corrective
    - Suspension or termination
  - Recovery
    - Awareness
  
- ### Technical/Logical Controls
  
  - Hardware 
    - Security features in a device
  - Software
    - Logging
    - Access Control
  - Technology Acquistion
    - Cost
    - Interoperability
    - Ease of use
    - Support
  - Technology Deployment
    - System architecture
    - Configuration
    - Patching
    - Maintenance
    - Monitoring
  - Examples
    - Session Management
      - MFA
      - Session timeouts
    - Passwords
      - Creation, storage, and expiration
  
  - Directive
    - Privacy notice
  - Deterrent
    - Use of monitoring
  - Preventative
    - Use of passwords
  - Detective
    - Intrusion detection system
  - Corrective
    - System isolation
  - Recovery
    - Restore from backups

- ### Physical/Environmental
  
  - Usually managed by facility or building management teams
    - Repairs and maintenance
    - Monitoring
  - Most obvious controls
    - Fences/bollards
    - Security Guards
    - Cameras
    - Locks
    - Motion Senors
    - Turnstiles/Mantrap
  - Power
    - Generators
    - Surge protectors
  - Fire 
    - Suppression systems
    - Smoke detectors
  - Water
    - Flooding
  - HVAC
    - Heating, ventilation, and air conditioning
  
  - Directive
    - Do not enter signage
  - Deterrent
    - Beware of dog signage
  - Preventative
    - Fence or bollards
  - Detective
    - Smoke detector
  - Corrective
    - Fire extinguisher
  - Recovery
    - Rebuild
  
- ### Compensating Controls

  - A control that addresses weakness or lack in other controls
    - Guard by a turnstile
    - Ability to reset a password
    - Multi-purpose control

## Defense in Depth

- Layered defense
- Avoid single point of failure
- Type of compensating control

- Vertical defense in depth
  - User
  - Application
    - Database
  - Guest OS
  - Hypervisor
  - Operating System
  - Hardware Security
  - Physical Security

## Impact of controls

- Disadvantages of controls
  - Can negatively impact user productivity
- Defeat controls
- Disabled controls
  - Logs
  - Alarms
- Lack of monitoring
- Lack of response

- Control Risk
  - The risk that a control did not effectively mitigate a risk
