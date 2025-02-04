# JA4+ Technical Details  
[JA4: TLS Client Fingerprinting](https://github.com/FoxIO-LLC/ja4/blob/main/technical_details/JA4.md)  
[JA4S: TLS Server/Session Fingerprinting](https://github.com/FoxIO-LLC/ja4/blob/main/technical_details/JA4S.md)  
[JA4H: HTTP Client Fingerprinting](https://github.com/FoxIO-LLC/ja4/blob/main/technical_details/JA4H.md)  
[JA4L: Light Distance Locality](https://github.com/FoxIO-LLC/ja4/blob/main/technical_details/JA4L.md)  
[JA4X: X509 TLS Certificate Fingerprinting](https://github.com/FoxIO-LLC/ja4/blob/main/technical_details/JA4X.md)  
[JA4SSH: SSH Traffic Fingerprinting](https://github.com/FoxIO-LLC/ja4/blob/main/technical_details/JA4SSH.md)  

### JA4+ General Rules
1. If a hashed field is empty, the output is 000s instead of a hash of an empty field. This is more conducive for analysis.
