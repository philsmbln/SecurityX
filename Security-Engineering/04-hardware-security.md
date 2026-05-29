Platform and Hardware Security
- Prevents firmware and hardware-based attacks // like TPM module installed
- Ensures secure execution environments for sensitive data
- Strengthen authentication and encryption capabilities

## Key Platform and Hardware Sec Components
- TPM // a secure cryptoprocessor for key storage and system integrity // chip in the computer
- HSM // a dedicated hardware device for cryptographic operations // standalone
- vTPM // a software-emulated TPM for virtualized environments

## TPM
- a tamper resistant chip that provides a hardware root of trust
- Ensure OS integrity at startup // prevents rootkits from altering OS
- Protect cryptographic keys
- Detects unathorized firmware changes

## HSM
- A physical device that manages digital keys and perform cryptographic operations
- Generate and protects private keys
- Offloads cryptographic functions for perfomance and security
- Prevents unauthorized access to stored keys

## vTPM
- software-based implementation of TPM in virutalized environments
- Extends TPM capabilties to virtual machines
- Enables full-disk encryption for virtual intances
- Verifies the trustworthiness of virtual workloads

## Comparison
### **TPM**
- Disk encryption: protecting Bitlocker and LUKS key storage
- Device authentication: ensuring secure identity for networked systems
- Remote attestation: verifying the integrity of remote devices
### **HSM**
- Secure payments: used in banking for encrypting transactions
- PKI and certificate management: protecting certificate authority private keys
- Cloud security: HSM as a service in cloud environments
### **vTPM**
- Performance overhead: software-based security introduces latency
- Isolation concerns: ensuring vTPM is properly sandboxed in multi-tenant environment
- Key management complexity: requires integration with extenal HSM solutions for security

## 