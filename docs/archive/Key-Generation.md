
# Generation of Keys


# Keys in MOSIP

Key | Key type | Objects | Storage | Generated by
----|----------|---------|---------|-------------
Kernel Root | RSA 2048 | <ul><li>Private Key</li><li>Self Signed Certificate</li></ul> | HSM-1 | Country
Registration | RSA 2048 | <ul><li>Private Key</li><li>Certifcate Signed by Kernel Root</li></ul> | HSM-1 | Country
Pre Registration | RSA 2048| <ul><li>Private Key</li><li>Certifcate Signed by Kernel Root</li></ul> | HSM-1 | Country
Kernel Sign | RSA 2048 | <ul><li>Private Key</li><li>Certifcate Signed by Kernel Root</li></ul> | HSM-1 | Country
Registration Processor | RSA 2048| <ul><li>Private Key</li><li>Certifcate Signed by Kernel Root</li></ul> | HSM-1 | Country
Partner Management | RSA 2048 | <ul><li>Private Key</li><li>Certifcate Signed by Kernel Root</li></ul> | HSM-1 | Country
ID Repository | RSA 2048 | <ul><li>Private Key</li><li>Certifcate Signed by Kernel Root</li></ul> | HSM-1 | Country
Kernel Identity Cache | AES 256 | Symmetric Key | HSM-1 | Country
Registration Client (TPM) | RSA 2048 | <ul><li>Private Key</li><li>Certificate</li></ul> | <ul><li>Client TPM (Private Key)</li><li>Server DB (Certificate)</li></ul>| Registration Client Software
Registration Client Packet Encryption | RSA 2048 | <ul><li>Private Key</li><li>Certificate Signed by Registration</li></ul> | <ul><li>Server DB (Private key)</li><li>Client DB (Certificate)</li></ul> | System
Data Share (10000 keys) | AES 256 | <ul><li>Symmetric Key</li><li>Encrypted by Kernel Identity Cache</li></ul>| Key Manager DB |System
CA / Sub-CA Certificates| X.509 | Certificates | Partner Management DB | CA
Partner Certificates | X.509 | Certificates Signed by CA | Partner Management DB | Partners
IDA Root | RSA 2048 | <ul><li>Private Key</li><li>Self Signed Certificate</li></ul> | HSM-2 | Country
IDA | RSA 2048 | <ul><li>Private Key</li><li>Certifcate Signed by IDA Root</li></ul> | HSM-2 | Country/IDA Partner
IDA Sign | RSA 2048 | <ul><li>Private Key</li><li>Certifcate Signed by IDA Root</li></ul> | HSM-2 | Country
IDA Identity Cache | AES 256 | Symmetric Key | HSM-2 | Country
IDA Internal | RSA 2048 | <ul><li>Private Key</li><li>Certifcate Signed by IDA</li></ul> | IDA DB | Country
IDA Partner | RSA 2048 | <ul><li>Private Key</li><li>Certifcate Signed by IDA</li></ul> | IDA DB | Country
IDA FIR | RSA 2048 | <ul><li>Private Key</li><li>Certifcate Signed by IDA</li></ul> | IDA DB | Country
IDA Credential Service | RSA 2048 | <ul><li>Private Key</li><li>Certifcate Signed by IDA</li></ul> | IDA DB | Country