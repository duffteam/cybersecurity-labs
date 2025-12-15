# Cybersecurity Portfolio (Authorized Lab Work)

**Owner:** Angel Sarango  
**Focus:** Entry-level Penetration Testing / IT Security / SOC  
**Scope:** This portfolio summarizes hands-on labs completed in authorized training environments (e.g., TryHackMe / controlled VMs).  
**Note:** Detailed step-by-step exploit instructions are intentionally omitted in this public-facing writeup.

---

## Skills Demonstrated

- Reconnaissance: host discovery, port scanning, service fingerprinting  
- Web testing: directory enumeration, upload attack surfaces, CMS assessment  
- Credential attacks (lab): password spraying / brute forcing (Hydra)  
- Post-exploitation: shell stabilization, local enumeration, artifact validation  
- Privilege escalation: Linux SUID/GTFOBins patterns; Windows escalation to SYSTEM  
- Pivoting: Metasploit session routing (autoroute) into segmented networks  
- Reporting: evidence capture, clean narrative, remediation-oriented notes  

## Tooling

Nmap, Gobuster, Hydra, Netcat, Metasploit Framework, Searchsploit/Exploit-DB, LinPEAS, SSH/Wget/Linux utilities.

---

## Projects

### 1) Steel Mountain (Windows)

**Objective:** Identify exposed services, obtain initial access, and escalate to **NT AUTHORITY\SYSTEM**.  
**Highlights:**
- Service discovery and vulnerability identification (HFS 2.3)
- Initial foothold and post-exploitation validation
- Privilege escalation to SYSTEM (full compromise demonstrated)

**Evidence:** Included in the PDF portfolio (selected screenshots).

---

### 2) Pivot (Multi-Stage / Lateral Movement)

**Objective:** Compromise an initial host and pivot into an internal segment to access additional services and data.  
**Highlights:**
- Application fingerprinting (Drupal)
- Database user enumeration
- Metasploit routing via `autoroute` to enable pivot access

**Evidence:** Included in the PDF portfolio (selected screenshots).

---

### 3) Vulnversity (Linux Web Exploitation)

**Objective:** Use web enumeration to discover an upload surface, achieve RCE, then escalate to **root**.  
**Highlights:**
- Directory enumeration discovered a hidden internal path
- Upload-based code execution for initial access
- Root compromise validated via proof file

**Evidence:** Included in the PDF portfolio (selected screenshots).

---

### 4) Dark Corp (WordPress - Credential Attack to RCE)

**Objective:** Enumerate CMS endpoints, validate weak authentication (lab), execute post-auth RCE, escalate to root.  
**Highlights:**
- WordPress attack surface discovery
- Valid credentials identified in a lab setting
- Post-auth code execution through theme modification
- Root escalation and final key retrieved

**Evidence:** Included in the PDF portfolio (selected screenshots).

---

### 5) Blue (Windows - SMB Exploitation)

**Objective:** Validate SMB exposure impact and document post-exploitation artifacts.  
**Highlights:**
- SMB assessment and exploitation in a controlled lab
- Artifact validation and clear evidence capture for reporting

**Evidence:** Included (excerpt) in the PDF portfolio.

---

### 6) GameZone (Linux - Webmin RCE)

**Objective:** Identify exposed admin surface and validate remote command execution impact.  
**Highlights:**
- Webmin administration surface identification
- RCE path selection and shell validation (lab)

**Evidence:** Included (excerpt) in the PDF portfolio.

---

### Supporting Lab: Nebula (Linux Privilege Escalation)

**Objective:** Demonstrate repeatable post-exploitation workflow and privilege escalation patterns.  
**Highlights:**
- Structured local enumeration
- SUID/GTFOBins-style escalation identification
- Evidence-driven validation and reporting

---

## Resume bullets (copy/paste)

- Completed multiple end-to-end penetration testing labs (Windows and Linux), documenting reconnaissance, exploitation, and remediation-oriented outcomes.
- Demonstrated privilege escalation to SYSTEM (Windows) and root (Linux) through evidence-based enumeration and controlled exploitation.
- Performed web content discovery, CMS attack-surface assessment, and authenticated/unauthenticated exploitation in authorized lab environments.
- Configured pivot routing with Metasploit autoroute to access segmented services and validate lateral movement risk.

