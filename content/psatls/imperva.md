---
title: "imperva.com"
date: 2023-11-01T17:01:07Z
draft: true
---


# Public Service Announcements TLS: IMPERVA.COM


### imperva.com TLS certificate served as certificate for Israeli Intelligence Domains


#### Download Original Certificate [here](/monitoring/tls/imperva.com.cer)


```bash
openssl x509 -text -noout -in "imperva.com.cer"
```


```
Certificate:
    Data:
        Version: 3 (0x2)
        Serial Number:
            01:a7:47:92:e9:2c:6e:09:57:36:5b:75:8f:29:63:b5
        Signature Algorithm: sha256WithRSAEncryption
        Issuer: C = BE, O = GlobalSign nv-sa, CN = GlobalSign Atlas R3 DV TLS CA 2023 Q3
        Validity
            Not Before: Jul 19 02:10:22 2023 GMT
            Not After : Jan 15 02:10:22 2024 GMT
        Subject: CN = imperva.com
        Subject Public Key Info:
            Public Key Algorithm: rsaEncryption
                Public-Key: (2048 bit)
                Modulus:
                    00:d9:a0:d2:9b:4e:92:df:e1:cf:86:93:66:7a:da:
                    29:21:24:80:9b:92:40:bc:5d:94:10:b3:a6:ec:ac:
                    a0:95:b6:69:76:58:29:ea:7d:84:1f:a3:ff:64:9b:
                    4f:54:49:bd:da:5b:a9:f9:6d:5a:d9:8f:81:0d:fa:
                    2e:50:01:80:0b:5e:4b:4d:34:01:70:2c:74:cc:30:
                    63:1c:ec:e8:c0:bc:5c:3d:e1:75:0c:62:cf:dc:99:
                    67:6e:72:66:5b:5e:4e:07:4f:4d:36:50:ca:f4:42:
                    8c:86:da:cd:90:e9:90:bb:8d:d6:c8:18:49:13:2c:
                    02:be:72:f7:d5:78:63:3a:3d:3d:f5:e3:f8:95:73:
                    46:06:3b:4e:f4:d8:46:7d:f8:87:8c:19:72:f5:82:
                    3e:4d:22:0c:0f:51:39:5b:33:52:d5:f3:1d:f5:ea:
                    7b:56:a7:b6:79:be:47:15:58:7c:0c:18:45:44:9d:
                    67:a9:47:e8:04:1c:c7:56:0c:2d:c5:00:c7:7b:6d:
                    49:2c:86:04:34:39:ef:eb:8d:ab:6c:bc:26:98:fb:
                    99:88:9e:35:f1:8b:3f:d3:44:b7:a9:68:a9:da:a6:
                    a7:11:ca:8e:bf:bc:ab:8a:21:d7:86:5c:10:94:84:
                    c7:86:e4:ee:8a:0b:38:33:63:9a:00:65:3f:9d:98:
                    a3:75
                Exponent: 65537 (0x10001)
        X509v3 extensions:
            X509v3 Subject Alternative Name:
                DNS:home.idf.il, DNS:*.prat.idf.il, DNS:my.idf.il, DNS:www.lebanonwar2.idf.il, DNS:glz.co.il, DNS:maarachot.idf.il, DNS:*.home.idf.il, DNS:*.go.idf.il, DNS:imperva.com, DNS:*.base.idf.il, DNS:www.idf.il, DNS:api.base.idf.il, DNS:go.idf.il, DNS:miluim.idf.il, DNS:prat.idf.il, DNS:mitgaisim.idf.il, DNS:*.maarachot.idf.il, DNS:base.idf.il, DNS:*.glz.co.il, DNS:*.mitgaisim.idf.il, DNS:www.mitgaisim.idf.il, DNS:www.base.idf.il, DNS:*.medical.idf.il, DNS:lebanonwar2.idf.il, DNS:www.my.idf.il, DNS:*.miluim.idf.il
            X509v3 Key Usage: critical
                Digital Signature, Key Encipherment
            X509v3 Extended Key Usage:
                TLS Web Server Authentication, TLS Web Client Authentication
            X509v3 Subject Key Identifier:
                47:50:2F:B2:12:21:06:75:64:EF:E6:4D:99:33:C2:32:71:7D:9D:01
            X509v3 Certificate Policies:
                Policy: 2.23.140.1.2.1
                Policy: 1.3.6.1.4.1.4146.10.1.3
                  CPS: https://www.globalsign.com/repository/
            X509v3 Basic Constraints: critical
                CA:FALSE
            Authority Information Access:
                OCSP - URI:http://ocsp.globalsign.com/ca/gsatlasr3dvtlsca2023q3
                CA Issuers - URI:http://secure.globalsign.com/cacert/gsatlasr3dvtlsca2023q3.crt
            X509v3 Authority Key Identifier:
                ED:A0:E6:01:05:3E:34:82:1A:A4:4F:5F:C5:BD:11:41:AA:DF:F3:61
            X509v3 CRL Distribution Points:
                Full Name:
                  URI:http://crl.globalsign.com/ca/gsatlasr3dvtlsca2023q3.crl
            CT Precertificate SCTs:
                Signed Certificate Timestamp:
                    Version   : v1 (0x0)
                    Log ID    : 76:FF:88:3F:0A:B6:FB:95:51:C2:61:CC:F5:87:BA:34:
                                B4:A4:CD:BB:29:DC:68:42:0A:9F:E6:67:4C:5A:3A:74
                    Timestamp : Jul 19 02:10:25.333 2023 GMT
                    Extensions: none
                    Signature : ecdsa-with-SHA256
                                30:45:02:20:3B:4D:CE:0E:E7:B6:83:E4:16:C2:F1:BB:
                                1D:2F:96:D0:9F:90:20:18:91:E9:DF:51:51:27:65:DF:
                                62:36:D8:42:02:21:00:DE:AC:BD:5B:A8:30:08:3D:06:
                                F6:C4:DB:73:A9:0C:71:3C:41:01:F0:5F:53:EC:12:F7:
                                80:EF:23:5B:0A:51:C5
                Signed Certificate Timestamp:
                    Version   : v1 (0x0)
                    Log ID    : 3B:53:77:75:3E:2D:B9:80:4E:8B:30:5B:06:FE:40:3B:
                                67:D8:4F:C3:F4:C7:BD:00:0D:2D:72:6F:E1:FA:D4:17
                    Timestamp : Jul 19 02:10:25.450 2023 GMT
                    Extensions: none
                    Signature : ecdsa-with-SHA256
                                30:45:02:20:61:D1:3B:FF:5D:2B:75:F3:06:DE:C0:29:
                                37:6B:2D:F9:32:FE:FA:7D:93:25:B0:12:BF:60:9C:1D:
                                39:1F:6B:B9:02:21:00:C1:F8:AC:AB:C0:62:7F:9C:92:
                                CB:A7:D5:38:76:BF:06:47:65:3F:7D:3B:F9:6C:98:F8:
                                F4:8D:E7:77:75:98:6B
                Signed Certificate Timestamp:
                    Version   : v1 (0x0)
                    Log ID    : DA:B6:BF:6B:3F:B5:B6:22:9F:9B:C2:BB:5C:6B:E8:70:
                                91:71:6C:BB:51:84:85:34:BD:A4:3D:30:48:D7:FB:AB
                    Timestamp : Jul 19 02:10:26.070 2023 GMT
                    Extensions: none
                    Signature : ecdsa-with-SHA256
                                30:44:02:20:42:99:61:98:98:D6:0F:0B:62:15:45:48:
                                B5:6A:BB:26:F8:66:A0:EF:CF:A7:A4:33:92:62:0A:02:
                                FB:78:A9:9D:02:20:42:BE:26:27:2D:3A:20:91:D9:25:
                                86:F2:84:1F:77:68:C7:E4:79:BD:10:0C:67:72:53:43:
                                31:E3:F9:E4:74:06
    Signature Algorithm: sha256WithRSAEncryption
    Signature Value:
        21:ae:d8:80:6a:25:1a:32:b7:16:27:66:d1:4b:a4:6a:58:4f:
        71:ed:6f:d7:f3:68:53:c5:f7:b6:8d:9c:f8:f2:23:34:f2:e0:
        17:94:63:46:b9:cc:4a:7d:d3:c8:1a:04:3e:39:1a:56:57:41:
        dd:99:bd:c8:5f:4e:65:52:32:1a:f9:9f:ce:de:de:ee:1a:2a:
        20:ee:dc:db:41:49:c3:76:ea:01:aa:5c:76:1e:b4:dc:f5:5a:
        6b:14:a8:ac:f6:b9:76:87:76:ff:40:f7:35:6b:5d:46:91:d0:
        55:1e:1c:1c:9c:20:01:6a:42:a8:7e:c3:b2:ff:46:15:6b:b1:
        44:7d:23:0a:64:41:6a:ce:ef:24:3a:54:22:3d:b1:64:05:37:
        56:f4:03:3d:cd:f5:29:1f:2c:72:29:31:60:fa:bf:19:0e:45:
        08:73:68:4d:52:7d:50:3c:4c:96:18:00:ae:d5:7a:44:ce:61:
        82:8e:80:cd:ae:0d:87:02:99:bf:f9:a9:ad:3e:c7:97:1e:9c:
        68:81:f8:3f:b7:bb:4e:e1:bf:08:19:46:f4:b5:34:9b:48:85:
        54:96:6e:d0:63:0c:bd:30:61:1a:c7:b6:53:f7:52:1e:71:8e:
        09:2b:a0:08:1b:88:9a:4d:5c:ee:36:a9:ea:7b:f5:62:41:e0:
        0a:bf:fd:27
```


#### Download Current Certificate [here](/monitoring/tls/11-01-2023-www.imperva.com.cer)


```bash
openssl x509 -text -noout -in "11-01-2023-www.imperva.com.cer"
```


```
Certificate:
    Data:
        Version: 3 (0x2)
        Serial Number:
            03:9c:9f:8d:a1:60:08:1a:6d:31:08:84:f2:cd:07:d6
        Signature Algorithm: sha256WithRSAEncryption
        Issuer: C = US, O = DigiCert Inc, CN = DigiCert TLS RSA SHA256 2020 CA1
        Validity
            Not Before: Mar  1 00:00:00 2023 GMT
            Not After : Mar 20 23:59:59 2024 GMT
        Subject: C = US, ST = California, L = San Mateo, O = Imperva Inc., CN = www.imperva.com
        Subject Public Key Info:
            Public Key Algorithm: rsaEncryption
                Public-Key: (2048 bit)
                Modulus:
                    00:cf:19:8d:24:d6:36:4a:90:07:bc:ae:7c:9c:39:
                    02:28:d5:81:6f:18:8f:c8:a2:18:4b:5e:a1:54:1f:
                    5d:48:a7:08:ad:4e:2f:0b:f3:ba:24:ea:6a:df:dd:
                    47:eb:60:f7:f6:81:b5:fa:91:48:17:47:cc:6b:bb:
                    63:6c:0c:ee:28:51:c7:48:f2:9e:ef:9e:06:60:b1:
                    2e:60:c6:b4:47:d5:85:06:e4:df:68:f1:e2:3e:d2:
                    b4:ea:6b:4e:a6:00:f3:27:25:dd:b6:0f:30:b5:86:
                    8d:49:7e:2a:0b:b9:df:f2:55:54:2d:5c:4a:dc:ea:
                    7d:81:9c:f8:1a:92:01:d7:41:00:6e:a1:75:39:b8:
                    19:ec:d5:aa:d1:8a:7a:c6:a8:47:55:59:ae:f9:e0:
                    bb:ae:ac:ed:55:2c:7d:d5:55:3b:d5:72:c3:ec:ab:
                    7a:d6:ea:f4:08:c1:77:cc:e5:89:37:91:e0:f3:89:
                    b6:72:04:5e:17:ef:79:9a:74:1e:f0:d8:de:eb:79:
                    5c:71:dd:e7:09:b2:ea:06:9c:1f:2b:6f:38:25:f9:
                    ad:0c:43:d3:f6:73:e7:52:26:a3:12:a3:4d:3d:9a:
                    a8:7e:ab:6a:cc:a8:da:29:c7:25:eb:cc:49:aa:3d:
                    d7:0e:88:61:f0:2d:e1:2e:23:c2:91:0c:2f:90:35:
                    56:d1
                Exponent: 65537 (0x10001)
        X509v3 extensions:
            X509v3 Authority Key Identifier:
                B7:6B:A2:EA:A8:AA:84:8C:79:EA:B4:DA:0F:98:B2:C5:95:76:B9:F4
            X509v3 Subject Key Identifier:
                0B:BC:2E:67:68:06:06:C4:53:49:F6:FD:A3:FD:B8:97:2C:FC:E0:92
            X509v3 Subject Alternative Name:
                DNS:www.imperva.com, DNS:imperva.com
            X509v3 Key Usage: critical
                Digital Signature, Key Encipherment
            X509v3 Extended Key Usage:
                TLS Web Server Authentication, TLS Web Client Authentication
            X509v3 CRL Distribution Points:
                Full Name:
                  URI:http://crl3.digicert.com/DigiCertTLSRSASHA2562020CA1-4.crl
                Full Name:
                  URI:http://crl4.digicert.com/DigiCertTLSRSASHA2562020CA1-4.crl
            X509v3 Certificate Policies:
                Policy: 2.23.140.1.2.2
                  CPS: http://www.digicert.com/CPS
            Authority Information Access:
                OCSP - URI:http://ocsp.digicert.com
                CA Issuers - URI:http://cacerts.digicert.com/DigiCertTLSRSASHA2562020CA1-1.crt
            X509v3 Basic Constraints:
                CA:FALSE
            CT Precertificate SCTs:
                Signed Certificate Timestamp:
                    Version   : v1 (0x0)
                    Log ID    : 76:FF:88:3F:0A:B6:FB:95:51:C2:61:CC:F5:87:BA:34:
                                B4:A4:CD:BB:29:DC:68:42:0A:9F:E6:67:4C:5A:3A:74
                    Timestamp : Mar  1 23:31:14.997 2023 GMT
                    Extensions: none
                    Signature : ecdsa-with-SHA256
                                30:44:02:20:21:64:BC:2B:12:7D:5E:5D:98:CF:A6:1F:
                                EE:FA:31:D9:27:59:E4:6C:14:6D:F6:83:CB:DC:EE:88:
                                84:76:B7:87:02:20:2F:98:BC:C7:7D:F7:4D:81:48:49:
                                0A:97:87:CD:D0:37:ED:E5:88:71:97:0A:BE:B9:04:B7:
                                01:EF:E0:3C:8F:FC
                Signed Certificate Timestamp:
                    Version   : v1 (0x0)
                    Log ID    : 73:D9:9E:89:1B:4C:96:78:A0:20:7D:47:9D:E6:B2:C6:
                                1C:D0:51:5E:71:19:2A:8C:6B:80:10:7A:C1:77:72:B5
                    Timestamp : Mar  1 23:31:15.052 2023 GMT
                    Extensions: none
                    Signature : ecdsa-with-SHA256
                                30:46:02:21:00:A0:70:06:C6:8C:82:27:18:44:5F:D8:
                                81:2B:CB:1E:28:04:43:82:69:50:E2:36:59:D1:20:01:
                                8D:5D:A4:79:88:02:21:00:D9:78:68:6C:BC:00:DB:A3:
                                67:47:F3:9C:61:64:E7:A8:82:F3:50:52:AF:0E:8C:61:
                                58:41:81:40:33:95:7D:6D
                Signed Certificate Timestamp:
                    Version   : v1 (0x0)
                    Log ID    : 48:B0:E3:6B:DA:A6:47:34:0F:E5:6A:02:FA:9D:30:EB:
                                1C:52:01:CB:56:DD:2C:81:D9:BB:BF:AB:39:D8:84:73
                    Timestamp : Mar  1 23:31:14.955 2023 GMT
                    Extensions: none
                    Signature : ecdsa-with-SHA256
                                30:46:02:21:00:DA:4A:7F:C9:5D:6D:56:04:D3:52:BF:
                                DA:70:6E:CA:46:74:DF:E7:ED:9A:D1:EF:0C:61:FA:ED:
                                5F:46:79:E6:C2:02:21:00:A3:34:2B:47:0F:93:7D:4F:
                                0D:39:87:C5:14:E6:CF:63:1A:53:62:AD:05:99:AB:58:
                                BE:67:17:4A:51:1C:41:5E
    Signature Algorithm: sha256WithRSAEncryption
    Signature Value:
        40:fe:a2:e9:e2:d8:a6:d7:19:b7:fa:98:ce:f4:5f:1b:66:2a:
        4a:52:04:63:f2:60:ec:c5:20:b8:8e:22:4a:6b:bc:9f:01:03:
        03:c6:82:68:8b:75:e7:e5:d7:13:34:e0:4c:7c:7b:33:4c:fa:
        26:5d:c0:5e:03:a8:92:d9:3a:3a:f5:e8:19:2f:29:6e:2a:16:
        88:77:71:f1:61:52:a5:12:e9:3c:ed:ea:9f:4b:78:39:b7:9e:
        1f:66:56:22:8e:cc:c7:d7:76:c1:24:97:12:38:fb:a2:df:bf:
        85:c7:d7:cb:b2:ce:8a:3c:43:78:5f:c6:f0:4f:13:7d:89:31:
        ca:e8:ee:a4:7c:6b:f9:df:f3:20:e9:fd:bc:a7:f1:aa:f9:0e:
        a5:b6:4f:79:5d:3f:fc:ae:59:2c:22:0e:c4:bd:f0:89:46:6f:
        14:f2:26:05:b1:0d:43:59:fa:d1:72:95:8a:53:ea:aa:7b:c2:
        65:e9:7d:a7:a2:17:bf:6e:a9:bb:24:5b:b9:81:cf:2c:dc:73:
        78:8d:4b:54:1e:40:de:fc:58:41:87:53:13:c2:9e:1b:40:9c:
        af:df:76:9c:94:ca:14:ff:e7:b2:37:d7:5c:ce:33:77:be:26:
        8d:6b:70:fe:4d:fb:96:07:41:69:5d:a5:a5:cd:31:37:1c:d2:
        62:68:46:87
```
