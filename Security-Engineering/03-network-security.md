# Network Misconfiguration
- Increase risk of exploitation
- Reduces network performance and reliability
- Endanger compliance

## Common Types of Misconfigurations
- Default credentials
- Open ports and services // unnecessary
- Weak encryption // use of outdated
- Imporper access controls
- Misconfigured firewall and ACLs // inconsistent or over

## Detecting Network Misconfuration
- Automated network scanning
- Log and traffic anaylsis
- Configuration audits
- Penetration Testing

## Preventing Network Misconfiguration
- Use secure conf baselines
- Implement RBAC
- Regularly patching and update systems
- Disable unused services and ports

`should be ongoing and not permanent`

## Future consideration for Network Security
- AI and machine learning in security audits
- Zero trust architecture
- Cloud misconfiguration management
- Threat intelligence and management

## Challenges Ahead
- Balancing security with operational security
- Managing network configurations across hybrid infrastructure
- Adapting to evolving compliance reqs

`proper configuration`

# IDS and IPS 
`Should be note: a lot of device can do both`
- IDS // only to detect
- IPS // actively act or block

## Why IDS and IPS are important
- Identify and mitigate different cyber threats
- Enhance network visibility and security
- Compliance

## Key components
- Signature-based detection
- Anomaly-based detection
- Heuristic anaylsis // behavioral most likely use AI

## Common IDS/IPS Issues
- False Positive
- False Negative
- Performance bottlenecks
- Signature management
- Misconfiguration

## Best Practices
- Regularly refining tuning detection rules
- Baseline network activity
- Deploy in strategic location
- Use multiple units if possible
- Enable automated resonses
- Integrate with SIEM

# Network Observability
`Why is it improtant`
- Identify and mitigates performance issues proactively
- Enhances security 
- Support compliance

## Key components
- Telemetry data collection
- Real-time analysis
- Automated insights

## Implementing Network Observability
- Utilize compregensive logging
- Leverage AI
- Integrate with SIEM and SOAR solutions
- Monitor end to end performance

## Common Tools
- Kentik | Provides realt-time telemetry
- Obkio | Continous network performance monitoring
- Site24x7 | cloud-based network
- Auvik | Automated network visibility analysis

`to name a few`

## Challenges of Network Observability
- Data overload
- Latency and packet loss
- Security gaps
- Tool integration complexity

## Solutions 
- Using AI-driven analytics
- Deploy network probes and sensors
- Inspect metadata for encypted traffic
- Standardize

## Future Trends
- Automated remediation
- Cloud-native observability
- Zero trust network monitoring
- Real-time threat intelligence integration
`active vs reactive`

## Consideration for the Future
- Increase demand for AI-driven network insight
- Greater focus on real-time analytics for security and performance
- Need for seamless integration with cloud security frameworks

# DNS Security
- Measures and protocol designed to protect DNS from threats
- Prevents attack from redirecting users
- Protect against DNS spoofing
- Ensures confidentiality and integrity

## Key DNS threats
- DNS // manipulating DNS queies
- Cache poisoning // insert of false DNS data
- DDoS attacks
- Domain hijacking

## Implementing DNS Security Measures
- Enable DNSSEC
- Use secure recursive resolvers
- Monitor and log DNS queries
- Implement rate limiting
- Restrict zone transfers

## Key Security Tools
- Cloudflare DNS
- Google Public DNS
- Quad9
- IBM DNSSEC Validator
- etc
`many propriety includes security features`

## Common DNS Challenges
- DNS traffic encryption
` Securing open DNS resolvers
` Timely patch management

## DNS Solution
- DNS over HTTPS (DoH)
- DNS over TLS (DoT)
- Configure access control
- Deploy threat intelligence feed
- patch management

## Future trends
- AI-powered DNS security
- Zero trust DNS security
- Decentralized DNS
- Automated threat intelligence integration

## Consideration for the future
- Increased reliance on encrypted DNS queries
- Stronger collaboration between ISP and DNS security providers
- Need for autoamted incident response systems within DNS infrastructures

# Email Network Security
`Why is it important`
- Prevents phishing and social engineering attacks
- Protects sensitive info from interception
- Reduces risk of malware and ransonware

## Common Email Threats
- Phishing attacks
- Business email compromise (BEC)
- Email spoofing
- Malicious attachments

## Essential Email Security Protocols
- DKIM // ensure email integrity using cryptographic signatures
- SPF // Prevents unauthorized use of domain names
- DMARC // helps detect and prevent email spoofing
- Secure/Multipurpose Intenet Mail Extensions (S/MIME) // encrypts email content and verifies sender identity

## Best Practices
- MFA for email access
- Email filtering
- Implementing encryption
- Conduct regular security awareness training
- and recognize email scams

## Strategies for Protecting Email Systems
- ATP
- Email gateway security
- AI-based anomaly detection
- Zero trust email security

## Challenges and Solutions
- High Volume of Phishing emails | Deploy AI-driven email filtering sol
- Credential Theft via email | enfornce MFA and strong password policies
- Compliance with Data Protection Laws | email encryption

## Emerging Trends
- AI-powered email security
- Deepfake phishing attacks
- Blockchain for email authentication
- Automated incident response

## Considerations for the Future
- Zero trust email frameworks
- AI-based email security
- Behavior-based threat intelligence to counter phishing
`if using cloud-based, provider is mainly providing securities, but not the password polcies etc that can be configured; there's always pros and cons using onprem and cloud-based`

