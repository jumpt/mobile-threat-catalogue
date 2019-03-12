---
    layout: threat
    ThreatCategory: Enterprise Mobility
    ID: EMM-7
    Threat: "End user privacy incursions by an administrator or attacker with administrative access to the EMM/MDM administrative console (e.g., tracking device location, call logs, text messages, personal contacts, etc.)"
    ThreatOrigin: "Worker Fired for Disabling GPS App That Tracked Her 24 Hours a Day [Updated] [^6]"
    ExploitExample:
    CVEExample:
    PossibleCountermeasures:
        "Ensure that the EMM/MDM console provides privacy controls to limit administrator access to privacy-sensitive information.":
            - Enterprise
        "Configure EMM/MDM solutions to audit administrative access and activity, particularly with respects to privacy-sensitive information.":
            - Enterprise
        "Configure EMM/MDM solutions to collect and audit only the minimal set of data necessary to meet the organization\'s broader mobile device security goals.":
            - Enterprise
        "Educate enterprise users about the privacy implications of enrolling their device into a EMM solution, such as clearly defining what data will be collected, and establishing procedures for resolving potential privacy violations.":
            - Enterprise
        "To prevent the potential for an attacker to gain access to highly privacy-sensitive information, such as call logs, configure EMM solutions with workflows that require multiple adminstrators to authorize access to such information prior to its release by the system.":
            - Enterprise
        "To further minimize the potential for EMM solutions to capture privacy-sensitive data, particularly for BYOD scenarios, deploy EMM solutions that discriminate the data collected when a device is being operated in a business context versus a personal context.":
            - Enterprise
---
