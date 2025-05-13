# Security+ 1.0 – Threats, Attacks, and Vulnerabilities

| **Term** | **Definition + Example** |
|---------|----------------------------|
| **Phishing** | Fraudulent emails tricking users into revealing personal information. <br>_Example: Email pretending to be from your bank asking for login details._ |
| **Smishing** | SMS-based phishing. <br>_Example: "Your package is stuck. Click here to fix it."_ |
| **Vishing** | Voice call phishing. <br>_Example: Call claiming to be IRS requesting SSN._ |
| **Spam** | Unsolicited messages, mostly promotional. <br>_Example: Emails advertising products with malicious links._ |
| **SPIM** | Spam over instant messaging platforms. <br>_Example: Fake job offer on WhatsApp or Skype._ |
| **Spear phishing** | Targeted phishing toward specific individuals. <br>_Example: Email to a CEO with tailored info._ |
| **Dumpster diving** | Retrieving sensitive info from trash. <br>_Example: Finding discarded documents with login credentials._ |
| **Shoulder surfing** | Watching someone enter a password or PIN. <br>_Example: Looking over someone’s shoulder at ATM._ |
| **Pharming** | Redirecting to fake websites without consent. <br>_Example: Typing bank URL and landing on a fake site._ |
| **Tailgating** | Unauthorized person follows authorized person into a restricted area. <br>_Example: Walking behind employee into secure door._ |
| **Eliciting information** | Tactics to extract confidential info. <br>_Example: Friendly conversation leading to Wi-Fi password disclosure._ |
| **Whaling** | Phishing targeting high-profile individuals. <br>_Example: Email scam targeting company executives._ |
| **Prepending** | Adding malicious content at the start. <br>_Example: Prefixing links with "update-" to seem legitimate._ |
| **Identity fraud** | Stealing and using another’s identity. <br>_Example: Using stolen credentials to open a bank account._ |
| **Invoice scams** | Sending fake invoices for payment. <br>_Example: Invoice sent to accounting appearing legitimate._ |
| **Credential harvesting** | Collecting login info through malicious tools. <br>_Example: Fake login pages or keyloggers._ |
| **Reconnaissance** | Collecting info on a target. <br>_Example: Scanning network ports or browsing LinkedIn profiles._ |
| **Hoax** | Deceptive message creating panic or misleading. <br>_Example: “Delete system32 to improve PC speed.”_ |
| **Impersonation** | Pretending to be someone trusted. <br>_Example: Helpdesk impersonator asking for credentials._ |
| **Watering hole attack** | Compromising a common site visited by the target. <br>_Example: Infecting a popular vendor site._ |
| **Typosquatting** | Registering domain similar to legitimate one. <br>_Example: gooogle.com instead of google.com._ |
| **Pretexting** | Creating a fabricated scenario to steal data. <br>_Example: Pretending to be IT to get login credentials._ |
| **Influence campaigns** | Social media or information operations to influence. <br>_Example: Fake news during elections._ |
| **Hybrid warfare** | Mix of cyber, social, and traditional attacks. <br>_Example: Cyberattacks used alongside propaganda._ |
| **Social media** | Exploiting platforms for misinformation or attacks. <br>_Example: Creating fake profiles to spread malware._ |

### Principles (Reasons for Effectiveness)

| **Principle** | **Definition + Example** |
|--------------|---------------------------|
| **Authority** | Pretending to be someone in power. <br>_Example: “I’m from IT, I need your password.”_ |
| **Intimidation** | Using fear to force compliance. <br>_Example: “Your job is at risk if you don’t comply.”_ |
| **Consensus** | Using peer behavior to gain trust. <br>_Example: “Everyone else clicked the link.”_ |
| **Scarcity** | Creating urgency due to limited availability. <br>_Example: “Only 2 licenses left! Click now.”_ |
| **Familiarity** | Building rapport to build trust. <br>_Example: Acting like a colleague to request info._ |
| **Trust** | Exploiting trusted sources or branding. <br>_Example: Fake email using real company logos._ |
| **Urgency** | Forcing quick decisions without thinking. <br>_Example: “Update your password now or lose access!”_ |

### Attack Types

| **Attack Type** | **Definition + Example** |
|------------------|---------------------------|
| **Ransomware** | Malware encrypts data; demands ransom. <br>_Example: WannaCry._ |
| **Trojans** | Malicious software disguised as legit. <br>_Example: Fake Flash Player update._ |
| **Worms** | Self-replicating malware spreads on network. <br>_Example: ILOVEYOU worm._ |
| **PUPs** | Potentially unwanted programs, often bundled. <br>_Example: Browser toolbars or adware._ |
| **Fileless virus** | Malware running in memory, not stored on disk. <br>_Example: Using PowerShell to exploit._ |
| **Command and control (C2)** | Communication path for attacker to control infected system. <br>_Example: Botnet receiving commands._ |
| **Bots** | Infected systems that follow commands. <br>_Example: PC in a DDoS botnet._ |
| **Cryptomalware** | Encrypts files and demands crypto ransom. <br>_Example: Locky ransomware using Bitcoin._ |
| **Logic bombs** | Code that activates on condition. <br>_Example: Wiping files on a specific date._ |
| **Spyware** | Monitors and collects user data secretly. <br>_Example: Keyloggers capturing credentials._ |
| **Keyloggers** | Records keystrokes to steal data. <br>_Example: Capturing username/password._ |
| **RAT** | Remote Access Trojan for stealth control. <br>_Example: Attacker sees and controls user’s screen._ |
| **Rootkit** | Deeply hidden malware modifying OS. <br>_Example: Prevents antivirus detection._ |
| **Backdoor** | Hidden entry point for re-access. <br>_Example: Developer left backdoor in software._ |

### Password Attacks

| **Type** | **Definition + Example** |
|---------|----------------------------|
| **Spraying** | Trying common passwords across many users. <br>_Example: Trying "123456" for all emails._ |
| **Dictionary** | Uses list of likely passwords. <br>_Example: Using a password list file._ |
| **Brute Force** | Tries all combinations. <br>_Example: “aaa”, “aab”, “aac”…_ |
| **Offline** | Cracking using stolen hash files. <br>_Example: Breach leads to password file being cracked._ |
| **Online** | Attempting logins on live system. <br>_Example: Repeated login attempts on website._ |
| **Rainbow table** | Uses precomputed hashes to crack. <br>_Example: Using rainbow table for MD5 hashes._ |
| **Plaintext** | Stealing passwords in readable form. <br>_Example: Unencrypted passwords in text file._ |

### Physical Attacks

| **Type** | **Definition + Example** |
|---------|---------------------------|
| **Malicious USB cable** | Cable with embedded malware. <br>_Example: HID attack cable logging keystrokes._ |
| **Malicious flash drive** | Auto-runs malware when plugged in. <br>_Example: Rubber Ducky USB device._ |
| **Card cloning** | Duplicating RFID/Mag cards. <br>_Example: Skimming ATM card._ |
| **Skimming** | Copying credit card info at reader. <br>_Example: Hidden reader on gas station terminal._ |

### Adversarial AI

| **Type** | **Definition + Example** |
|---------|----------------------------|
| **Tainted training data** | Feeding bad data to mislead AI. <br>_Example: Biased image dataset misidentifying faces._ |
| **Model insecurity** | Exploiting weaknesses in ML. <br>_Example: Input causing misclassification._ |

### Other Attacks

| **Type** | **Definition + Example** |
|---------|---------------------------|
| **Supply-chain attack** | Targeting vendor or update processes. <br>_Example: SolarWinds attack._ |
| **Cloud vs. On-prem** | Cloud can be multi-tenant, more API attacks; on-prem limited access. <br>_Example: Cloud misconfiguration leaking data._ |
| **Birthday attack** | Exploiting hash collisions. <br>_Example: Two inputs creating same hash._ |
| **Collision** | When two inputs have same hash. <br>_Example: MD5 hash collision._ |
| **Downgrade attack** | Forcing system to use weaker security. <br>_Example: SSL/TLS downgrade to SSL 2.0._ |


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Security+ 1.0 </title>
  <link rel="stylesheet" href="../assets/style.css">
</head>
<body>
  <header>
    <h1>Security+_1.0</h1>
  </header>

  <main>
    <p>Security+ 1.0 - 1.0 Threats, Attacks, and Vulnerabilities </p>
  
  </main>

  <footer>
    <p>&copy; 2025 Ajeesh Mathai| <a href="../index.html">Back to Home</a></p>
  </footer>
</body>
</html>
