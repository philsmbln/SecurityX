# Subject-Based Access Control

- User-based control: assign based on user
- Process-based control: assign based on active process
- Device-based control: assign based on trusted devices
- Service-base control:

## Types of Subject Access Control1
- DAC  - Discretionary // Owner gets to decide who gets access
- MAC  - Mandatory // fix rules by admin
- RBAC - Role-based // assigned roles
- ABAC - Atribute-based // more flexible like time of day etc

##  Implementing Subject Access Control Policies
- Least priveledge
- Segmentation
- Auditing and monitoring
- MFA

## Challenges and Solution
- Unathorized Access | Implement strict authentication controls
- Insider Threats | Enforce role-based policies
- Access Mismanagement | Conduct regular audits and apply automatic revocation

## Tecnhologies Supporting Subject Access Control
- IAM: provide centralized auth
- PAM: manages and restrics high-priviledge accounts
- Zero-trust: continous verification and auth

## Popular Tools
- Okta: IAM
- CyberArk: PAMM
- Microsoft Entra ID: Conditional access and IAM

## Subject Access Control Treands and Innovation
- AI-driven access controls
- Blockchain-based identity management
- Context-aware policies

## Future Challenges for Subject Access control
- Balancing security and usability
- Integrating legacy with modern controls
- Adapting to evolving compliance

# Biometrics Authentication
- Fingerprint recognition
- Facial recognition
- Iris and Retina scanning
- Voice recognition
- Behavioral biometrics

## Advantanges of Biometrics auth
- Enhances security
- Convenience
- Speed and Effeciency
- Non-transferrable

## Challenges of Biometrics auth
- Privacy concerns
- False positives/negatives
- Cost
- Data breaches // cannot change

## Best Practices
- Combine with MFA
- Protect with encryption and secure storage
- Regular system audits
- User consent and compliance

## Use Cases for Biometrics auth
- Enterprise security // for employees
- Banking and finance // for transaction
- Healthcare // securing patient data
- Mobile devices // unlock and auth payments

## Biometrics auth Trends and Innovations
- AI-powered biometrics // accuracy
- Contactless biometrics // hygiene
- Decentralized
- Biometric payment systems

## Future Challenges for Biometrics Auth
- Ethical concerns // surveillance
- Increased attacked // cannot be changed
- Regulatory framework // adaptation with changes

# Secret Management
Practice of storing sensitive info
- Prevents unauthorized data breaches
- Support compliance
- Reduce the risk of credential leaks // limits potential damage

# Common Secrets
- API keys // access data
- Database credentials // username and password to access data
- Encryption keys
- TLs/SSL certificates

## Best Practices for Secret Management
- User secrets manager // like vaults AWS secret manager or Hashicorp vault
- Encrypt sensitive data // protects secret at rest and in transit
- Limit access // PoLP
- Automates secret rotation // regularly rotate
- Monitor and audit usage // track secret and detect anomalies

## Common Mistakes to Avoid
- Hardcoding Secrets in Source Code | Risk of public exposure
- Sharing Secrets via Email/Chat
- Using Weak or Default creds 

## Popular Tools for Secrets 
- AWS Secret Manager | centralized secret storage for aws environment
- HashiCorp Vault | secret managemnet and access policies
- Azure Key Vault | Microsoft
- CyberArk Conjur | secret for DevOps workflows

## Steps for Implementing Secure Secret Management
1. Identify and classify sensitive creds
2. Use a dedicated secrets management tools
3. Apply strict access controls like RBAC and IAM policies
4. Implementing logging and monitoring
5. Regularly roate and update

## Emerging Trends in Secrets Management
- Zero trust security models
- Automated secrets rotation
- AI-powered anomaly detection
- Decentralized identify and blockchain-based auth

## Challenges
- Increasing volume of secrets
- Managing multicloud secret environments
- Ensuring compliance

# Cloud IAM Access and Trust Policies
- Provides centralized control over user access
- Enhance security by enforcing least priveilege
- Support compliance

## Core Components of Cloud IAM Access and Trust Polcies
- IAM users and groups // define roles and permission
- IAM policies // define what action are allowed and denied
- Trust policies // manage permission access over services

## IAM Policy Types
- Identify-based policies // attach permission to users, groups or roles
- Permission boundaries // guardrail
- Resource-based policies // attaching to the resource itself

## Trust policies
- Define which entity can assume a role
- Enable federated access for external users
- Support cross-account access between AWS services

## Best Pracitces for Cloud IAM and Trust Policies
- Follow least privilege, grant only neccesary permission
- use IAM roles
- Monitor IAM usage, enable logging and auditng with CloudTrail
- Rotate an expire credentials
- Implement MFA

## Common Pitfalls to Avoid
- Overly permissive policies
- Hardcoded credentials
- Lack of policy monitoring

## Steps for Configuring IAM Policies
1. Define user, roles and groups
2. Create policies following least priviledge principle
3. Attach policies to correct entity
4. Test and validate access
5. monitor and audit policy usage

## Recommended IAM Tools
- AWS IAM Access Analyzer | detects overly permissive policices
- Google CloudI IAM | centralized policy manager
- Azure RBAC | assign fine-grained permissions

## Emerging Trend in Cloud IAM and Trust POlicies
- AI powered
- Decentralized identity management
- Adapative policies
- Zero trust

## Challenges
- Management IAM in multi cloud environment
- Adapting IAm policies to evolving cybersecurity threat
- Ensuring compliance

# Identity and Access Management Logging and Monitoring
- provides visibility in user actions
- helps detect unauthorized access and insider threats
- support regulatory compliance req

## Key components of IAM logging and monitor
- access logs // tracks who access what and when
- audit logs // record security-related evenst
- monitoring tools

## Key IAM and Monitoring Types
- Event logs // capture system-wide act
- Authentication logs // tracks user login attempts
- Authorization logs // log granted and denied attempts
- Session logs // record active user session and duration

## Common Logging Toools
- AWS CloudTrail | Tracks API calls and access req
- Google Cloud Logging | Monitors identity related events
- Micro Entra ID logs | Logs windows based authentication and authorization logs
- Splunk | Aggregates and analyzes security logs from multiple sources