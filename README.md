{
  "Type": "UnencryptedConfiguration",
  "Certificates": [
    {
      "GUID": "{b96e6a07-0a9c-4764-b0c1-3d327257d663}",
      "Type": "Authority",
      "X509": "MIIFCjCCAvKgAwIBAgIBATANBgkqhkiG9w0BAQ0FADA5MQswCQYDVQQGEwJQQTEQMA4GA1UEChMHTm9yZFZQTjEYMBYGA1UEAxMPTm9yZFZQTiBSb290IENBMB4XDTE2MDEwMTAwMDAwMFoXDTM1MTIzMTIzNTk1OVowOTELMAkGA1UEBhMCUEExEDAOBgNVBAoTB05vcmRWUE4xGDAWBgNVBAMTD05vcmRWUE4gUm9vdCBDQTCCAiIwDQYJKoZIhvcNAQEBBQADggIPADCCAgoCggIBAMkr/BYhyo0F2upsIMXwC6QvkZps3NN2/eQFkfQIS1gql0aejsKsEnmY0Kaon8uZCTXPsRH1gQNgg5D2gixdd1mJUvV3dE3y9FJrXMoDkXdCGBodvKJyU6lcfEVF6/UxHcbBguZK9UtRHS9eJYm3rpL/5huQMCppX7kUeQ8dpCwd3iKITqwd1ZudDqsWaU0vqzC2H55IyaZ/5/TnCk31Q1UP6BksbbuRcwOVskEDsm6YoWDnn/IIzGOYnFJRzQH5jTz3j1QBvRIuQuBuvUkfhx1FEwhwZigrcxXuMP+QgM54kezgziJUaZcOM2zF3lvrwMvXDMfNeIoJABv9ljw969xQ8czQCU5lMVmA37ltv5Ec9U5hZuwk/9QO1Z+d/r6Jx0mlurS8gnCAKJgwa3kyZw6e4FZ8mYL4vpRRhPdvRTWCMJkeB4yBHyhxUmTRgJHm6YR3D6hcFAc9cQcTEl/I60tMdz33G6m0O42sQt/+AR3YCY/RusWVBJB/qNS94EtNtj8iaebCQW1jHAhvGmFILVR9lzD0EzWKHkvyWEjmUVRgCDd6Ne3eFRNS73gdv/C3l5boYySeu4exkEYVxVRn8DhCxs0MnkMHWFK6MyzXCCn+JnWFDYPfDKHvpff/kLDobtPBf+Lbch5wQy9quY27xaj0XwLyjOltpiSTLWae/Q4vAgMBAAGjHTAbMAwGA1UdEwQFMAMBAf8wCwYDVR0PBAQDAgEGMA0GCSqGSIb3DQEBDQUAA4ICAQC9fUL2sZPxIN2mD32VeNySTgZlCEdVmlq471o/bDMP4B8gnQesFRtXY2ZCjs50Jm73B2LViL9qlREmI6vE5IC8IsRBJSV4ce1WYxyXro5rmVg/k6a10rlsbK/eg//GHoJxDdXDOokLUSnxt7gk3QKpX6eCdh67p0PuWm/7WUJQxH2SDxsT9vB/iZriTIEe/ILoOQF0Aqp7AgNCcLcLAmbxXQkXYCCSB35Vp06u+eTWjG0/pyS5V14stGtw+fA0DJp5ZJV4eqJ5LqxMlYvEZ/qKTEdoCeaXv2QEmN6dVqjDoTAok0t5u4YRXzEVCfXAC3ocplNdtCA72wjFJcSbfif4BSC8bDACTXtnPC7nD0VndZLp+RiNLeiENhk0oTC+UVdSc+n2nJOzkCK0vYu0Ads4JGIB7g8IB3z2t9ICmsWrgnhdNdcOe15BincrGA8avQ1cWXsfIKEjbrnEuEk9b5jel6NfHtPKoHc9mDpRdNPISeVawDBM1mJChneHt59Nh8Gah74+TM1jBsw4fhJPvoc7Atcg740JErb904mZfkIEmojCVPhBHVQ9LHBAdM8qFI2kRK0IynOmAZhexlP/aT/kpEsEPyaZQlnBn3An1CRz8h0SPApL8PytggYKeQmRhl499+6jLxcZ2IegLfqq41dzIjwHwTMplg+1pKIOVojpWA=="
    }
  ],
  "NetworkConfigurations": [
    {
      "GUID": "{69b40c68-c747-4b7f-8ed5-95c98d8c34ff}",
      "Name": "ShamDam",
      "Type": "VPN",
      "VPN": {
        "Type": "OpenVPN",
        "Host": "31.171.152.19",
        "OpenVPN": {
          "Port": 1194,
          "UserAuthenticationType": "Password",
          "CompLZO": "false",
          "SaveCredentials": true,
          "VerifyX509": {
            "Name": "CN=al18.nordvpn.com"
          },
          "Proto": "udp",
          "KeyDirection": "1",
          "RemoteCertTLS": "server",
          "Cipher": "AES-256-CBC",
          "Auth": "SHA512",
          "RenegSec": 0,
          "ServerCARefs": [
            "{b96e6a07-0a9c-4764-b0c1-3d327257d663}"
          ],
          "ClientCertType": "None",
          "TLSAuthContents": "-----BEGIN OpenVPN Static key V1-----\ne685bdaf659a25a200e2b9e39e51ff03\n0fc72cf1ce07232bd8b2be5e6c670143\nf51e937e670eee09d4f2ea5a6e4e6996\n5db852c275351b86fc4ca892d78ae002\nd6f70d029bd79c4d1c26cf14e9588033\ncf639f8a74809f29f72b9d58f9b8f5fe\nfc7938eade40e9fed6cb92184abb2cc1\n0eb1a296df243b251df0643d53724cdb\n5a92a1d6cb817804c4a9319b57d53be5\n80815bcfcb2df55018cc83fc43bc7ff8\n2d51f9b88364776ee9d12fc85cc7ea5b\n9741c4f598c485316db066d52db4540e\n212e1518a9bd4828219e24b20d88f598\na196c9de96012090e333519ae18d3509\n9427e7b372d348d352dc4c85e18cd4b9\n3f8a56ddb2e64eb67adfc9b337157ff4\n-----END OpenVPN Static key V1-----\n"
        }
      }
    }
  ]
}
