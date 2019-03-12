---
    layout: threat
    ThreatCategory: Mobile Operating System
    ID: STA-2
    Threat: "Failure to properly authenticate application updates, enabling attackers to cause installation of malicious apps."
    ThreatOrigin: "Android: One Root to Own Them All [^202]"
    ExploitExample: "Own your Android! Yet Another Universal Root [^214]"
    CVEExample: CVE-2013-4787
    PossibleCountermeasures:
        "Monitor the security patch state of devices and block enterprise connectivity from out-of-date devices with known exploitable vulnerabilities.":
            - Enterprise
        "Purchase devices from vendors/carriers who have committed to providing timely updates or who have known track records for prompt updates.":
            - Enterprise
        "Ensure devices are kept up-to-date with security patches to decrease the likelihood that they can be rooted/jailbroken.":
            - Enterprise
        "Use tools or device APIs (Android SafetyNet, Samsung Knox hardware-backed remote attestation, or other applicable remote attestation technologies) to detect and block enterprise connectivity from known compromised devices.":
            - Enterprise
        "Use device APIs (e.g. SystemUpdatePolicy) to enforce system update policies.":
            - Enterprise
        "Restrict installation of apps from unofficial app stores, which may not undergo certificate validation processes (e.g., side-loading)":
            - Enterprise
        "Use device built-in separation technologies such as Android for Work, Apple iOS managed apps, or Samsung Knox Workspace to provide a level of separation between enterprise apps and potentially harmful personal-use apps.":
            - Enterprise
---
