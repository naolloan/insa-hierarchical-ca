# INSA Hierarchical Certificate Authority (PKI)

This project implements a **hierarchical Certificate Authority (CA)** using OpenSSL, modeled after **INSA as the Root CA**.  
The goal is to demonstrate how real-world PKI systems establish **trust, authentication, and secure communication**.

## CA Hierarchy
INSA Root CA
→ Directorate CA
→ Department CA
→ End Entities (Client & Server)

## What Was Implemented
- Root CA with self-signed X.509 certificate  
- Subordinate Directorate and Department CAs  
- Client and Server certificates issued by Department CA  
- Full certificate chain verification  
- Secure session key exchange using RSA and symmetric keys  

## Project Structure
- `pki/` – CA hierarchy and certificates  
- `demo/` – Session key exchange demonstration  
- `screenshots/` – Evidence of implementation and verification  
