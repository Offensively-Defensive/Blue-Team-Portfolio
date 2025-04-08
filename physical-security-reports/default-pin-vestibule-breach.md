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
| Unattended security checkpoint | High | No
