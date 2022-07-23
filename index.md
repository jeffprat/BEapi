
# BioEncryption: Biometric Encryption
## What Problem Does BioEncryption Solve?
Suppose you have a secret on your mobile device you want to hide. How would you hide it? You have several options:

Use a Lock/Encrypt feature on your phone. The iPhone for example, has a Lock feature which allows lock and unlock operations using the phone’s biometric authentication system. However, actual lock/unlock is performed using a password, which the iPhone stores somewhere on the device; biometric authentication only grants seamless retrieval of that password.

Store the secret using some password-protection App. Clearly, the secret exists inside the App, and anyone who know the App’s password can reveal the secret; that password is stored on the phone.

The problem with such solutions is that your secret depends on some other secret which is stored on the mobile-device and poses a security risk.

## The BioEncryption Solution
With BioEncryption, your secret is not stored at all. Rather, it is used to modify Machine Learning biometric classification models so that it can only be revealed using your biometrics.

Note that BioEncryption is not about generating Biometric features; they can be generated from facial images (e.g., using openCV), fingerprints, iris features, etc. Rather, BioEncryption is about secret hiding using given feature files.




For more details see [https://github.com/jeffprat/BioEncryption](https://github.com/jeffprat/BioEncryption).

