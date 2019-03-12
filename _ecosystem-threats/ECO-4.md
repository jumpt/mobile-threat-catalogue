---
    layout: threat
    ThreatCategory: "Mobile OS & Vendor Infrastructure"
    ID: ECO-4
    Threat: "Exploitation of app store remote installation capabilities to install malicious apps onto mobile devices"
    ThreatOrigin: "Symantec Internet Security Threat Report 2016 [^110]"
    ExploitExample:
        - "How I Almost Won Pwn2Own via XSS [^200]"
        - "How Anywhere Computing Just Killed Your Phone-Based Two-Factor Authentication [^201]"
    CVEExample:
    PossibleCountermeasures:
        "To prevent an attacker from gaining unauthorized access to remote installation functionality, enable two-factor or other strong authentication methods for user accounts on app stores.":
            - Mobile Device User
            - Enterprise
        "To detect unauthorized activity, including remote installation of apps, use features from Google or others to periodically analyze account activity for suspicious logins.":
            - Mobile Device User
            - Enterprise
        "Deploy a combination of MDM, MAM, or container solutions and mobile devices that successfully enforce policies (e.g., whitelisting) that prevent unauthorized applications from being installed to managed areas of the device.":
            - Enterprise
        "To reduce the time to detection of malicious applications, use app threat intelligence services to identify malicious apps installed on devices.":
            - Enterprise
---
