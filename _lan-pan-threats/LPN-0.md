---
    layout: threat
    ThreatCategory: "Network Threats: Wi-Fi"
    ID: LPN-0
    Threat: Rogue access points
    ThreatOrigin: "Guidelines for Securing Wireless Local Area Networks (WLANs) (SP 800-153) [^16]"
    ExploitExample: "Darkhotel: A Sophisticated New Hacking Attack Targets High-Profile Hotel Guests [^17]"
    CVEExample:
    PossibleCountermeasures:
        "Avoid the use of untrusted and unencrypted Wi-Fi networks, particularly when needing to access sensitive services.":
            - Mobile Device User
        "When needing to connect to untrusted and unencrypted Wi-Fi networks, attempt to verify with a representative of the hosting organization (e.g., coffe shop employee) that the detected network is the correct one.":
            - Mobile Device User
        "To reduce the probability of connecting to rogue access points, use Wi-Fi hotspot services that associate access points with registered Wi-Fi provider, geolocation, and crowd-sourced reputation data to make assertions about the their apparent trustworthiness.":
            - Mobile Device User
            - Enterprise
        "To avoid this threat, only allow mobile devices to connect to authorized Wi-Fi networks that use WPA2 encryption.":
            - Enterprise
---
