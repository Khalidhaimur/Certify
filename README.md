Certify is a tool used for auditing and exploiting Active Directory Certificate Services (AD CS) in penetration testing scenarios. It helps identify misconfigurations and potential security risks related to certificate management.

📌 Available Files:
Certify.exe - The main executable file.

Certify.exe.config - Configuration file for the tool.

Interop.CERTENROLLLib.dll - Required DLL for certificate enrollment operations.

🚀 How to Use:
1️⃣ Enumerate Certificate Authorities (CAs):
Certify.exe cas

2️⃣ Find Vulnerable Certificate Templates:
Certify.exe find vulnerable
3️⃣ Request a Certificate Using a Template:
Certify.exe request /ca:DOMAIN-CA /template:VulnerableTemplate

4️⃣ Export the Certificate as PFX:
Certify.exe request /ca:DOMAIN-CA /template:VulnerableTemplate /pfx
