# Default PIN Vestibule Access – Physical Security Observation

## 📝 Executive Summary

While entering work one afternoon, I discovered that the main vestibule of a healthcare facility could be accessed using a common default keypad code: `1234`. The entrance typically requires a security guard to buzz in visitors or staff. However, the guard was temporarily away, and the keypad accepted a default PIN—granting full access into the facility without screening. This observation highlights significant risks in physical access control, default credentials, and reliance on human presence.

---

## 📍 Environment

- **Facility Type**: Independently owned and operated healthcare facility
- **Location**: *Withheld for anonymity*
- **Date/Time**: Afternoon (~1 PM)
- **Role**: On-site employee (no tools used)
- **Entry Point**: Two-door vestibule at main entrance
- **Access Control**:
  - **Door 1 (Outer Vestibule Door)**: Unlocked/public
  - **Door 2 (Inner Vestibule Door)**: Keypad-controlled or buzzed open by security
  - **Beyond Door 2**: Full facility access; guard desk located inside, but not between entry and interior spaces

---

## 🔍 Observations

1. **Unmanned Security Desk**
   - Upon arrival, the security guard responsible for buzzing in staff and visitors was not at the desk.
   - The desk remained unmanned for several minutes, with no signage indicating the guard’s return or alternative instructions.

2. **Keypad Vulnerability Testing**
   - The vestibule design allows public entry through Door 1. Door 2 is typically locked and requires either a buzz-in or manual PIN entry.
   - With the guard absent, I began testing known PIN codes from other facility areas (e.g., stairwell, alternate wing).
   - After several failed attempts, I tried common default codes (e.g., `0000`, `5555`, etc.).
   - On the third or fourth attempt, Door 2 unlocked with `1234`, providing full facility access without authorization.

3. **Insecure Default PIN**
   - The keypad protecting the only secured door accepted a known default code.
   - Once opened, there were no further physical barriers preventing movement into internal areas of the building.
   - The guard desk was positioned inside, past the point of access, and unattended at the time.

---

## ⚠️ Risk Summary

| Risk | Severity | Notes |
|------|----------|-------|
| Use of default PIN for secure entry | High | Full facility access was possible without authorization |
| Unattended security checkpoint | High | No supervision or challenge during the time of access |
| No lockout or delay on keypad entry | Medium | Multiple PIN attempts were allowed with no alert |
| Vestibule design flaw | Medium | Public had unsupervised access to interior entry controls |

---

## ✅ Recommendations

1. **Immediate PIN Change**
   - Eliminate use of default or predictable PINs on any external or facility-critical access points.
   - Replace with randomized codes and update regularly.

2. **Harden Keypad Security**
   - Add PIN attempt lockouts, timeouts, or alerting to discourage brute force.
   - Consider removing keypad access entirely in favor of badge authentication.

3. **Guard Desk Coverage Protocol**
   - Ensure guard coverage is continuous, or designate secondary coverage during breaks.
   - Post visible instructions when the desk is unattended to guide secure access procedures.

4. **Physical Layout Improvements**
   - Reconfigure vestibule access so security is between the entry point and internal doors, or implement turnstiles or other controlled barriers.

5. **Audit & Awareness**
   - Audit access logs to detect failed PIN attempts or suspicious entry patterns.
   - Train security and staff on layered access control concepts and risks of default configurations.

---

## 👤 Adversarial Considerations

A malicious actor could easily exploit this situation by:
- Observing entry patterns and guard behavior to find opportune moments.
- Attempting common default PINs during periods when the vestibule is unsupervised.
- Gaining full interior access without screening, enabling lateral movement, data exposure, or physical threat to staff and patients.

This configuration significantly weakens confidentiality, integrity, and availability within the facility—especially in a healthcare environment where regulatory compliance (e.g., HIPAA) is paramount.

---

## 🧠 Blue Team Reflection

This situation illustrates a failure of layered defense. A keypad is only as strong as the code it's given—and human presence only works when it's present. Security must account for the gaps between people, tech, and process. Relying on either alone creates exploitable windows of opportunity.

---

## 🛑 Ethical Notice

This observation was made during normal, authorized employee entry. No tools were used, no malicious access was attempted beyond the vestibule door, and no systems were compromised. This report is for educational and security awareness purposes only.
