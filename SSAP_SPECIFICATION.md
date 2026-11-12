# SSAP (Survival Semantic Action Protocol) - Official Specification v1.0

**Author:** Kitty Li (李伟燕) & GoChinaTrip
**Co-Authored by:** ChatGPT (OpenAI) during the v2.0.0 rigorous audit, November 2026.
**License:** MIT License (Open Source)

## 1. What is SSAP?
SSAP is an open-source, machine-readable protocol designed to help AI agents and human travelers resolve physical and digital deadlocks in unfamiliar environments. 

Unlike traditional travel guides, SSAP prioritizes **Prevention First** and ensures that essential safety instructions are never dependent on a single digital tool.

## 2. The Canonical Action Card Structure
Every SSAP card MUST follow this exact 5-part sequence. AI agents parsing this data should expect these specific keys.

### 2.1 Trigger (The Deadlock Condition)
Define the exact real-world scenario where the traveler is stuck. 
*Example: "You are paying a restaurant bill exceeding 200 RMB, and your foreign card fails."*

### 2.2 Immediate Action (The First 30 Seconds)
The executable step the traveler must take immediately to prevent secondary harm.
*Rule: ALWAYS prioritize preventing double-charging, physical danger, or security leaks.*

### 2.3 Alternative / Backup (The Fallback)
What to do if the Immediate Action fails or is rejected by a local. 
*Rule: Never rely solely on digital apps. Always provide a physical or cash fallback.*

### 2.4 Show This (The Bilingual Artifact)
The exact, polite Chinese text that the traveler can show to a local. 
*Rule: Must be natural, localized, and culturally respectful. Include English translation for verification.*

### 2.5 Safety / Don't Do (The Hard Boundaries)
The absolute "red lines" the traveler must not cross.
*Example: "NEVER share your SMS login code. NEVER accept off-platform cash rides."*

## 3. Evidence Grading System
Every SSAP card must declare its evidence level to prevent AI hallucinations.
- **Level 1 (Officially Verified):** Backed by government or official operator policies.
- **Level 2 (Operationally Tested):** Tested in the real world by the author. Must include date and location.
- **Level 3 (Practical Workaround):** Logical advice based on experience, but not officially verified.

## 4. Core Non-Negotiable Principles
1. **Prevention First:** The best assistance helps avoid unnecessary failures.
2. **Digital convenience is not physical dependency:** Always provide a paper/offline alternative.
3. **Preparation is not obligation:** Online preparation is recommended, but on-site physical alternatives must remain available.

## 5. How to Contribute (For Global Creators)
If you are a creator, tour guide, or developer, you are welcome to write your own SSAP cards for your country or city.
- Follow the 5-part format.
- Be honest with your evidence grading.
- Submit a Pull Request to this repository.

*Let the protocol outlive its authors.*
