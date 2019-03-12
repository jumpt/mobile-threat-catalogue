---
    layout: threat
    ThreatCategory: "Network Threats: Bluetooth"
    ID: LPN-11
    Threat: "Brute-force decryption of Bluetooth 4.0 or older communication due to weak BR/EDR encryption algorithm"
    ThreatOrigin: "Guide to Bluetooth Security (SP 800-121) [^28]"
    ExploitExample:
    CVEExample:
    PossibleCountermeasures:
        "To resist brute-force decryption attacks, use the maximum PIN length and encryption key sizes available on configurable Bluetooth devices.":
            - Mobile Device User
        "Restrict the use of older Bluetooth devices with a static or 4-digit PIN to very low-risk use cases.":
            - Mobile Device User
            - Enterprise
        "To prevent unauthorized disclosure or modification to data transmitted over a compromised Bluetooth session, use Bluetooth applications that provide strong over-the-top encryption to data prior to transmission over the Bluetooth interface.":
            - Mobile Device User
            - Enterprise
---
