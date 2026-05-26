# Subject-Based Access Control (SBAC)

## Types of Subject-Based Control
- **User-based control** — Access assigned based on the user identity
- **Process-based control** — Access assigned based on active processes
- **Device-based control** — Access assigned based on trusted devices
- **Service-based control** — Access assigned based on services or applications

---

# Types of Subject Access Control

## DAC — Discretionary Access Control
- Resource owner decides who gets access

## MAC — Mandatory Access Control
- Access controlled through fixed rules set by administrators

## RBAC — Role-Based Access Control
- Access assigned based on organizational roles

## ABAC — Attribute-Based Access Control
- Flexible access control using attributes such as:
  - Time of day
  - Location
  - Device type
  - User behavior

---

# Implementing Subject Access Control Policies

- Follow the **Principle of Least Privilege (PoLP)**
- Use network and system segmentation
- Enable auditing and monitoring
- Implement Multi-Factor Authentication (MFA)

---

# Challenges and Solutions

| Challenge | Solution |
|---|---|
| Unauthorized access | Implement strict authentication controls |
| Insider threats | Enforce role-based policies |
| Access mismanagement | Conduct regular audits and apply automatic revocation |

---

# Technologies Supporting Subject Access Control

## IAM — Identity and Access Management
- Provides centralized authentication and authorization

## PAM — Privileged Access Management
- Manages and restricts high-privilege accounts

## Zero Trust Security
- Requires continuous verification and authentication

---

# Popular Tools

- **Okta** — IAM platform
- **CyberArk** — PAM solution
- **Microsoft Entra ID** — Conditional access and IAM

---

# Subject Access Control Trends and Innovations

- AI-driven access controls
- Blockchain-based identity management
- Context-aware access policies

---

# Future Challenges for Subject Access Control

- Balancing security and usability
- Integrating legacy systems with modern controls
- Adapting to evolving compliance requirements

---

# Biometric Authentication

## Types of Biometrics

- Fingerprint recognition
- Facial recognition
- Iris and retina scanning
- Voice recognition
- Behavioral biometrics

---

# Advantages of Biometric Authentication

- Enhanced security
- Convenience
- Faster authentication
- Non-transferable credentials

---

# Challenges of Biometric Authentication

- Privacy concerns
- False positives and false negatives
- High implementation costs
- Data breaches (biometric data cannot be changed)

---

# Best Practices for Biometric Authentication

- Combine biometrics with MFA
- Protect biometric data using encryption and secure storage
- Conduct regular system audits
- Ensure user consent and regulatory compliance

---

# Use Cases for Biometric Authentication

## Enterprise Security
- Employee authentication and access control

## Banking and Finance
- Transaction verification and fraud prevention

## Healthcare
- Securing patient records and systems

## Mobile Devices
- Device unlocking and payment authentication

---

# Biometric Authentication Trends and Innovations

- AI-powered biometrics
- Contactless biometrics
- Decentralized identity systems
- Biometric payment systems

---

# Future Challenges for Biometric Authentication

- Ethical concerns and surveillance issues
- Increasing biometric-based attacks
- Evolving regulatory frameworks

---

# Secret Management

Secret management is the practice of securely storing and managing sensitive information.

## Benefits

- Prevents unauthorized data breaches
- Supports compliance requirements
- Reduces the risk of credential leaks

---

# Common Secrets

- API keys
- Database credentials
- Encryption keys
- TLS/SSL certificates

---

# Best Practices for Secret Management

- Use secrets managers such as:
  - AWS Secrets Manager
  - HashiCorp Vault
- Encrypt sensitive data at rest and in transit
- Limit access using PoLP
- Automate secret rotation
- Monitor and audit secret usage

---

# Common Mistakes to Avoid

| Mistake | Risk |
|---|---|
| Hardcoding secrets in source code | Public exposure |
| Sharing secrets through email/chat | Credential leakage |
| Using weak or default credentials | Unauthorized access |

---

# Popular Secret Management Tools

- **AWS Secrets Manager** — Centralized secret storage for AWS
- **HashiCorp Vault** — Secret management and access policies
- **Azure Key Vault** — Microsoft cloud secret management
- **CyberArk Conjur** — DevOps secret management

---

# Steps for Implementing Secure Secret Management

1. Identify and classify sensitive credentials
2. Use dedicated secret management tools
3. Apply strict access controls using RBAC and IAM
4. Enable logging and monitoring
5. Regularly rotate and update secrets

---

# Emerging Trends in Secret Management

- Zero Trust security models
- Automated secret rotation
- AI-powered anomaly detection
- Decentralized identity and blockchain authentication

---

# Challenges in Secret Management

- Increasing volume of secrets
- Managing multi-cloud environments
- Maintaining compliance requirements

---

# Cloud IAM Access and Trust Policies

## Benefits

- Centralized control over user access
- Enhanced security through least privilege
- Improved compliance support

---

# Core Components of Cloud IAM and Trust Policies

## IAM Users and Groups
- Define users, groups, roles, and permissions

## IAM Policies
- Define allowed and denied actions

## Trust Policies
- Control access between services and accounts

---

# IAM Policy Types

## Identity-Based Policies
- Attached to users, groups, or roles

## Permission Boundaries
- Define maximum allowed permissions

## Resource-Based Policies
- Attached directly to cloud resources

---

# Trust Policies

- Define which entities can assume roles
- Enable federated access for external users
- Support cross-account access between cloud services

---

# Best Practices for Cloud IAM and Trust Policies

- Follow least privilege principles
- Use IAM roles instead of long-term credentials
- Monitor IAM activity using logging and auditing tools
- Rotate and expire credentials regularly
- Implement MFA

---

# Common Pitfalls to Avoid

| Pitfall | Risk |
|---|---|
| Overly permissive policies | Excessive access |
| Hardcoded credentials | Credential compromise |
| Lack of monitoring | Undetected misuse |

---

# Steps for Configuring IAM Policies

1. Define users, roles, and groups
2. Create policies following least privilege
3. Attach policies to correct entities
4. Test and validate access
5. Monitor and audit policy usage

---

# Recommended IAM Tools

- **AWS IAM Access Analyzer** — Detects overly permissive policies
- **Google Cloud IAM** — Centralized policy management
- **Azure RBAC** — Fine-grained permission assignments

---

# Emerging Trends in Cloud IAM and Trust Policies

- AI-powered access management
- Decentralized identity management
- Adaptive access policies
- Zero Trust architectures

---

# Challenges in Cloud IAM

- Managing IAM across multi-cloud environments
- Adapting policies to evolving cybersecurity threats
- Maintaining regulatory compliance

---

# Identity and Access Management (IAM) Logging and Monitoring

## Importance

- Provides visibility into user actions
- Detects unauthorized access and insider threats
- Supports regulatory compliance requirements

---

# Key Components of IAM Logging and Monitoring

## Access Logs
- Track who accessed what and when

## Audit Logs
- Record security-related events

## Monitoring Tools
- Analyze and alert on suspicious activities

---

# Common IAM Log Types

## Event Logs
- Capture system-wide activities

## Authentication Logs
- Track login attempts and authentication events

## Authorization Logs
- Record granted and denied access attempts

## Session Logs
- Monitor active user sessions and durations

---

# Common Logging Tools

- **AWS CloudTrail** — Tracks API calls and access requests
- **Google Cloud Logging** — Monitors identity-related events
- **Microsoft Entra ID Logs** — Authentication and authorization logging
- **Splunk** — Aggregates and analyzes security logs

## Best Practices for IAM Logging and Monitoring
- Enable centralzied looging
- User real-time monitoring
- Implement access alerts
- Regularly audit logs // identify potential security gaps

## Common Challenges
- Log overload | Use filtering and correlation tech
- Insider threats | implemetn behavior-based anomaly detection
- Compliance req | Automate audit log collection and retention

## Steps for Implementing Logging and Monitoring
1. Identify critical access points and sensitive data
2. Configure logging for IAM policies and auth events
3. Integreate logs with SIEM systems
4. Setup alerts for unathorized access attempts
5. Regularly review and continous improvements

## Security Framework Alignment
- NIST 800-53 // security and privacy controls
- ISO 27001 // international standard for information security management
- SOC 2 // compliance for service org handling sensitive customer data

## Emerging Trends in IAM Logging and Monitoring
- AI-driven threat detertion
- Zero trust
- Automated incident response
- Decentralized identity management

## Challenges Ahead
- Managing multicloud IAM
- Adapting to evolving compliance reqs
- Balacing security and performance

# Priveleged Identity Management(PIM)
- Protects critical IT systems and sensitive data
- Reduce the risk of insider threat and credential misuse
- Helps ensure compliance req

## Core Components of PIM
- Just-in-time access
- RBAC // assign permission based on user roles
- Auditing and monitoring // tracks privilege users

## Best pratices
- Least privilege principle
- MFA
- Privileged access workstation or PAW
- Session minitoring and recording
- Automated role revocation

## Common pitfalls
- Overprivileged accounts | Implement least privilege
- Weak authentication methods | Enforce MFA
- Lack of Monitoring | Utilize SIEM tools for continous oversight

## Steps for Implementing PIM
- Identify privileged accounts
- Define access policies
- Implement access controls
- Monitor and audit activity
- Automate access revocation

## Tools for Managing Priveleged Identities
- CyberArk | Secure privileged accounts
- Microsoft Entra PIM | for microsoft
- BeyondTrust | Offers privileged session management
- ManageEngine PAM | Manages and audits privileged access

## Emerging Trends for PIM
- Zero Trust security Models
- AI-driven access controls // automate
- Passwordless auth
- Cloud-native PIM solutions // for cloud environment

## Challenges for PIM
- Balancing security with operational efficiency
- Adapting to hybrid and multicloud infrastructures
- Regulatory compliance and compliance demands

# Enterprise Authentication
- Foundational part of security
- Protects sensitive enterprise data
- Enhance security posture
- Enables regulatory compliance

## Core Authentication Methods
- SSO // centralized user authentication
- MFA // adds additional security layer
- Federated auth // allows users to access diff systems

## Key Enterprise Authentication Protocols
- SAML // Security Assertions Markup Language, used for SSO in web applications
- OpenID connect // identiy layer for federated auth
- Kerberos // secure authentication using tickets
- EAP // common for wireless networks

## IAM Solutions
- Microsoft Entra ID | Enterprise identity and access management
- Okta | Identity and SSO
- Ping Identity | Cloud
- CyberArk | PAM

## Implementing Enterprise Auth
- Use MFA
- Adopt Zero trust principles
- Monitor and audit auth logs
- Regularly rotate and review creds/auths

## Challenges and Solutions
- Password Fatigues | Implement passwordless auth
- Credential theft | Enforce MFA
- Legacy System Integration | Use federated auth solutions, bridging modern and legacy

## Emerging trends
- Biometric auth
- Decentralzied identity management
- AI-driven auth // detecting anomalies in realtime
- Passkeys and passwordless auth

## Challenges Ahead
- Adapting to evolving cybersecurity threats
- Balancing security with user experience
- Ensuring compliance with global data regulations

# Enterpise Authorization
- Defining who and what can access enterprise
- Reduce insider threats by enforcing access policies
- Ensure compliance with regulatory standards
- Enhances security posture

## Core Authorization Frameworks
- RBAC // assigns permission based on predefined roles
- ABAC // dynamically grants access
- PBAC // uses policies

## Key Authorization Protocols
- OAuth 2.0 for API auth
- SAML for federated identity
- OpenID connect // extends OAuth for authentication and authorization
- Kerberos // provides secure authenticaiton for enterprise networks for windows based systems

## Authorization Models
- DAC // User defines access rights
- MAC // Access is enforced on classification levels
- RBAC
- ABAC

## Best Practices
- PoLP
- MFA
- Implement role-based and attribute-based controls
- Continously audit access logs 
- Just in time access controls

## Common challenges
- Excessive Privilege | Implement least privilege
- Lack of Access Audits | Automate and schedule regular reviews
- Weak Authorization Policies | Use centralzied identiy governance solutions

## Emerging Trends
- Zero Trust security model
- AI-driven authorization decisions
- Decentralized identity systems
- Federation

## Challenges Ahead
- Managing auth in multicloud environment
- Evolving compliance req and enforcement
- Integrating legacy and modern identity framework