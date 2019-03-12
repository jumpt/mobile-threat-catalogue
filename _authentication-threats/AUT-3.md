---
    layout: threat
    ThreatCategory: "Authentication: User to Device"
    ID: AUT-3
    Threat: "Computer vision attacks inferring the PIN/password from video recordings"
    ThreatDescription: "If an attacker can record or gains access to video recorded by a camera or similar device with line-of-sight on a user\'s mobile device while he or she is entering a PIN, password, or other secret, the attacker can attempt to infer that secret. Success of the attack will vary based on various factors, but increases with higher resolution recordings, greater proximity, a less-obstructed and direct (perpendicular) view of the device, and the opportunity to analyze multiple recordings of a user\'s keystrokes over time."
    ThreatOrigin:
    ExploitExample: "Black Hat: Google Glass Can Steal Your Passcodes [^126]"
    CVEExample:
    PossibleCountermeasures:
        "When entering PINs, passwords, or other secrets, limit visibility of the device to others.":
            - Mobile Device User
        "Use devices and applications that support biometric authentication methods (e.g. fingerprint), which are not as easily captured by casual recording methods as entry of PINs or passwords.":
            - Mobile Device User
            - Enterprise
        "Increase the minimum length and reduce the maximum lifetime of passwords and PINs to reduce the probability a inference attack will be successful.":
            - Mobile Device User
            - Enterprise
        "When possible, configure remote services with authentication mechanisms that allow the use of random one-time passwords, which if recorded during entry, cannot later be used to authenticate.":
            - Mobile Device User
            - Enterprise
        "To prevent a successful password inferrence attack from singly enabling authentication by an attacker, configure  sensitive services to require 2-factor authentication.":
            - Mobile Device User
            - Enterprise
        "To increase the difficulty of visual or sensor-based inference attacks on entries by the on-screen keyboard, a randomized keyboard layout for PIN or password entry could be implemented as a feature of the mobile OS.":
            - Mobile OS Developer
---

