# w1 Infroduction to the course
    Subject - Object Reference Model
    Basic Operational Framework
    Adversary Types
    Vulnerability Types
    CIA
    Attack Lifecycle
    Worm
    Definitions of Computer Security
    Difference between threat vulnerability attack
    Types of Threats
# w2 Security Design Principles
    Fundamental Design Principles
        Open Design
        Sweeping simplifications
        Design for iteration
        Least Astonishment

    Principles of Secure Design
        minimizing secrets
        complete mediation
        fail-safe defaults
        least privilege
        simplicity of mechanism
        least common mechanism
    
    Ethics
    Legality
    Password

# w3 Threat Modeling
    Security Lift Cycle
    Threats, Vulnerabilities and Attacks
    Risk
    Threat Modeling
        Why
        Steps
        STRIDE Model
        Ranking Threats
    Attacks Trees
    Risk Assement and Management
    Information Security Risk
    IT Asset
    Quantitative Methodology
    Qualitative Approach

# w4 Security Policies
    Definition
        Secure States
        Security policy allow transit between secure states
        If we consider a computer system to be a finite state automaton with state transitions then:
            Security policy is a statement that partitions the states of a system into a set of authorized or secure states and a set of unauthorized or non-secure states.
            Secure system is a system that starts in an authorized state and cannot enter an unauthorized state.
            Breach of security occurs when a system enters an unauthorized state.
    
    Element of a Security Policy
        Confidentiality policy
        Integraty policy
        Availbility policy

        Security Mechanism:  things enforce policy
        Policy -> rules  Mechanism-> prevent from bypassing the policy
    Types of Security Policies
        Militrary Security Policy -> Confidentiality
        Commercial Security -> Integrity

    Security Models
        BLP Model confeidential  
            Star Property   1. They have to have a reason to read the info.They have to reader equal or lower privacy info
            Simple Security Property    2 They can write higher secuirty file.
            Compartmentalization
    Tranquility Principle : strong tranquility --> dont change privacy
        Principle of tranquility states that subjects and objects may not change their security level once instantiated.
        Principle of strong tranquility states that security levels do not change during the lifetime of the system.
        Principle of weak tranquility states that security levels do not change in a way that violates the rules of a given security policy.
 
    Biba Integrity Model contrary to BLM no write up
    
    Information Transfer Path

    Seperation of Duty / function 
    Chinese Wall Model
        Partys should not gain information from each other, they should find a third part.
        An example implementation of the Chinese Wall model could include the following items:
            The objects of the database are items of information related to a company.
            A company dataset (CD) contains objects related to a single company.
            A conflict of interest class (COI) contains the datasets of companies in competition
            COI(O) represents the conflict of interest class that contains object O.
            CD(O) represents the company dataset that contains object O. The model assumes that each object belongs to exactly one conflict of interest class.
            CW-* Property Rule:
            A subject S may write to an object O if and only if all of the following conditions hold:

            The CW-simple security rule permits S to read O; and
            For all unsanitized objects O???, S can read O??? => CD(O???) = CD(O).
            ????????????????????????????????????:??????S ??????????????????O???????????????????????????????????????:

                ???????????????S????????????????????????O'?????????O'???O?????????????????????????????????

                ?????????S??????????????????O'?????????O'???O?????????????????????????????????

                ?????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????:??????????????????????????????????????????????????????????????????????????????;?????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????????

                ??????????????????*-??????:??????S???????????????O????????????????????????????????????????????????????????????:

                ????????????????????????????????????S??????O???

                ???S????????????????????????????????????????????????????????????
    Critical Infromation Systems Security Policy
    Access Principles
    Security Polices in Practice
    Example of Policy Areas
    Basic of Most Security Policies
    Inclusive and Exclusive Policies
    Hierarchical Policies
    Security Policies and Systems Engineering
        1
    