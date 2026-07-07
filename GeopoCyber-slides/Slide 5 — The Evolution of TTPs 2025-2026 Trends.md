dissoj@aua.ac.ke  
July 07, 2026


# Slide 5 — The Evolution of TTPs (2025-2026 Trends)

# 🎯 Slide 5 — The Evolution of TTPs: 2025-2026 Trends

This is the **technical heart** of your presentation. ExCo doesn't need to become cybersecurity experts — they need three sharp mental models they can use in decisions. The narrative arc: **the attacker's playbook has fundamentally changed, and our defenses were built for the old playbook** .

---

## 🖼 On-Slide Content

### **Title (top):**
> # The Evolution of TTPs
> ### *2025-2026 — Three shifts that broke our old defense model*

### **Layout — Three vertical "trend cards" side-by-side:**

---

#### 🔑 **TREND 1 — IDENTITY > EXPLOITATION**
> ### *"Log in, don't break in"* 

**What changed:**
Attackers no longer force their way through firewalls. They **authenticate** — using stolen or forged credentials of **Non-Human Identities**: API keys, service tokens, automated workflow accounts .

**Why it matters:**
- MFA and biometrics protect **humans** — not machines
- NHIs outnumber human accounts **~45 to 1** in modern enterprises *[industry benchmark — to validate]*
- Zero-Trust architectures are **bypassed at the trust root**

**Executive takeaway:**
> *We built our fortress around the front door. The attackers came in with a valid keycard.*

---

#### 🌿 **TREND 2 — LIVING OFF THE LAND + EDGE**
> ### *"Invisible by design"* 

**What changed:**
Two combined tactics :
1. **Living off the Land (LotL)** — attackers use **native OS tools** (PowerShell, WMI) instead of custom malware — nothing for EDR to flag
2. **Edge Targeting** — they compromise **routers, VPNs, firewalls** — devices that **cannot host security agents**

**Why it matters:**
- EDR/XDR investments are effectively **blind** to both vectors
- Edge compromise = **persistent foothold** outside our monitoring perimeter
- Detection requires **behavioral analytics**, not signature-based tools

**Executive takeaway:**
> *Our most expensive detection tools cannot see where the attackers now live.*

---

#### 💣 **TREND 3 — GEOPOLITICAL TRIPLE EXTORTION**
> ### *"Ransomware as a political weapon"* 

**What changed:**
Ransomware is no longer just about payment . The new model:
1. **Encrypt** the data (classic ransomware)
2. **Exfiltrate & leak** sensitive data publicly
3. **Directly threaten** end clients, executives, regulators

**Why it matters:**
- Goal shifts from **profit → sector destabilization**
- Payment doesn't end the crisis — **reputational and regulatory damage continues**
- Crisis response must include **client comms, regulator liaison, executive protection**

**Executive takeaway:**
> *The ransom demand is now the least of our problems.*

---

### **Bottom banner (thin, spanning all three columns):**
> **Our defense architecture was designed for malware, perimeters, and criminals. The 2026 attacker exploits identity, invisibility, and instability.**

---

## 🎤 Speaker Notes (what you say — ~5 minutes)

> *"We've talked about **who** the adversaries are. Now let's talk about **how** they operate — because this is where our defenses are most exposed.*
>
> *I want to focus on three shifts. Not because they're the only trends — but because each one **breaks a specific assumption** that our current security architecture is built on. If you take nothing else from this section, remember these three."*
>
> **[Point to Trend 1 — Identity]**
> *"The first shift is captured in a phrase our threat intel teams have adopted: **'Log in, don't break in.'***
>
> *For twenty years, cyber defense has been about **stopping intruders at the perimeter** — firewalls, intrusion detection, MFA. We got very good at that. So attackers stopped trying to break through. Instead, they **log in** — with valid credentials* .
>
> *But here's the twist: they're not stealing your employees' passwords anymore. Employees have MFA, biometrics, behavioral monitoring. **Humans are hard.**
>
> *Instead, they target **Non-Human Identities** — the API keys, service tokens, and automated workflow accounts that our applications use to talk to each other* . *These accounts have massive privileges, often no MFA, weak rotation policies, and are frequently checked into code repositories by accident. In a modern enterprise, non-human identities outnumber human accounts by roughly **45 to 1** — and each one is a potential front door.*
>
> ***Our Zero-Trust architecture was built for humans. The attackers moved to machines.***"
>
> **[Point to Trend 2 — LotL & Edge]**
> *"The second shift is about **invisibility**.*
>
> *We have spent significant budget over the past five years on EDR — Endpoint Detection and Response — tools that look for malware on servers and laptops. Attackers responded in two ways.*
>
> *First: they stopped using malware. They use what's called **'Living off the Land'** — legitimate tools that are already installed on our systems, like PowerShell and WMI, to conduct their operations* . *When your EDR looks at what they're doing, it sees a system administrator running normal scripts. Nothing to flag.*
>
> *Second — and this is the more concerning part — they've moved to **Edge devices**: routers, VPN concentrators, firewalls, load balancers. These devices are the front door of our network, but they're also the **one place we cannot install EDR agents** . *They run proprietary firmware. So the attackers set up shop there, establish persistent access, and monitor everything flowing in and out of our network — completely invisible to our detection stack.*
>
> *This is exactly what happened in Singapore — the Chinese group **UNC3886** compromised edge infrastructure at four telecom operators and stayed there for **months** before being detected* . *That's not a Singaporean problem. That's a global blind spot."*
>
> **[Point to Trend 3 — Triple Extortion]**
> *"The third shift changes what ransomware **is**.*
>
> *Two years ago, ransomware was a criminal transaction: encrypt data, demand payment, decrypt, done. Today, ransomware is a **geopolitical weapon** wearing a criminal costume* .
>
> *The modern playbook is what we call **triple extortion**. First, they encrypt your data — the classic move. Second, they exfiltrate that data before encryption and threaten to publish it — so paying the ransom doesn't restore confidentiality. Third, and this is new: **they contact your clients, your executives, your regulators directly** — with threats, with leaked data, with demands.*
>
> *The strategic intent has shifted. When a nation-state or its proxy launches a triple-extortion attack against a bank, the goal isn't €5M in Bitcoin. **The goal is to destabilize the institution, spook the market, or damage a strategic sector.** Payment doesn't end the crisis — because payment was never the point.*
>
> *This has enormous implications for how we run crisis response. We can no longer treat ransomware as a finance-and-IT problem. It's a **communications, regulatory, legal, and executive-protection problem** from the first hour."*
>
> **[Deliver the bottom banner slowly]**
> *"So here is the uncomfortable synthesis. **Our current defenses were built for a world of malware, perimeters, and criminals looking for money.** The 2026 attacker operates in a world of **identity, invisibility, and instability**. Every euro we spent optimizing for the old model is a euro that doesn't help us against the new one.*
>
> *That is the case for the reinvestment I'll walk you through in a few slides."*

---

## 🎨 Design & Visual Direction

| Element | Recommendation |
|---|---|
| **Layout** | Three equal vertical columns — signals "three equally important shifts" |
| **Icons** | One strong icon per trend: 🔑 (key/identity), 🌿 (camouflage/LotL), 💣 (weaponization) — but professional line-art versions |
| **"Executive takeaway"** | Italic, quoted, in an accent color — these are your **memorable one-liners** |
| **Color coding** | Reuse the accent colors from Slide 2's pillars if possible — creates visual continuity across the deck |
| **Density warning** | ⚠️ This slide is dense. Consider **animated reveal** — one column at a time — so ExCo focuses on each trend during your narrative |
| **Bottom banner** | Same dark-bar treatment as Slides 2-4 for visual consistency |

💡 **If density is a concern:** Split into **3 separate slides** — one per trend. Each becomes a 90-second deep-dive. Slower pacing, more absorbed. Recommended if your slide budget allows.

---

## 💡 Anticipated ExCo Questions (be ready)

**Q1: "You said NHIs outnumber humans 45 to 1. What's our number?"**
> Suggested answer: *"Honest answer: we don't have a precise count yet — and that's part of the problem. NHI discovery and inventory is one of the first investments I'll ask you to sanction. What I can tell you is that industry benchmarks put the ratio between 30:1 and 60:1 for organizations at our scale, and we have no reason to believe we're an outlier."*

**Q2: "If EDR can't detect Living off the Land, why are we still paying for it?"**
> Suggested answer: *"EDR still catches roughly 60-70% of the threat volume — the noisier, less sophisticated attacks. What it doesn't catch is the top-tier nation-state activity. The answer isn't to abandon EDR; it's to **layer behavioral analytics on top** — UEBA, network detection, identity threat detection. We need defense in depth, not defense replacement."*

**Q3: "You said we can't install security agents on edge devices. Is that actually true, or is it a vendor problem?"**
> Suggested answer: *"It's largely a **vendor architecture problem** — the devices run proprietary firmware, and manufacturers don't expose the interfaces we'd need. There's slow progress in the industry — some vendors now offer telemetry APIs — but for the majority of our edge fleet, we're dependent on the manufacturer's own security posture. **This is why hardware supply chain security is now a board-level concern**."*

**Q4: "On triple extortion — should we ever pay a ransom?"**
> Suggested answer: *"Our position — aligned with regulatory guidance and industry best practice — is that we **do not pay**, for three reasons. First, sanctions risk: many actors are on OFAC and EU lists, and payment can trigger enforcement action. Second, no guarantee: payment often doesn't stop the leak or the client harassment. Third, precedent: paying makes us a repeat target. Our investment goes into **resilience and recovery**, not negotiation capability."*

**Q5: "This all sounds very grim. Is there anything we're doing well?"** *(the morale-check question)*
> Suggested answer: *"Yes — several things. Our identity governance for **human accounts** is mature. Our SOC has significantly improved detection times over the past 18 months. Our crisis simulation exercises have measurably improved executive readiness. What I'm flagging today are the **gaps that emerged because the threat evolved faster than any single control roadmap** — not fundamental failures. The point of this briefing is to redirect investment, not to sound an alarm."*

**Q6: "How does this compare to what our peer banks are doing?"** *(the benchmarking question)*
> Suggested answer: *"Across our tier-1 peer group, NHI management is universally identified as the top gap. Two peers have launched dedicated NHI programs in the past 12 months. Edge visibility is more variable — some are investing heavily, others are still scoping. On triple-extortion readiness, we are **at parity or slightly ahead** thanks to our crisis simulation program. I can share a detailed benchmark separately if useful."*

---

## ✅ Validation Checkpoints

Before we move to Slide 6 (Case Studies Part 1), please confirm or adjust:

1. **Slide density** — Three trends on one slide vs. **three separate slides** (one per trend)? My honest recommendation: **split it** if you have the budget. Each trend deserves its own moment.
2. **The "45:1" NHI benchmark** — I flagged it as *[to validate]*. Do you have an internal number, or should I remove the specific figure and use qualitative language ("dramatically outnumber")?
3. **The "60-70% EDR efficacy" figure** in the Q&A — same question. Real benchmark, or should I generalize?
4. **Ransomware payment position** — I stated a firm "we do not pay" stance. Confirm this matches BNP Paribas's actual policy, or should I soften to "our policy is guided by regulatory, sanctions, and precedent considerations"?
5. **Peer benchmarking claim** — I positioned BNP as "at parity or slightly ahead" on triple-extortion readiness. Fair, or overstating? I can adjust to more conservative language.
6. **"Executive takeaway" one-liners** — Are these landing right?
   - *"We built our fortress around the front door. The attackers came in with a valid keycard."*
   - *"Our most expensive detection tools cannot see where the attackers now live."*
   - *"The ransom demand is now the least of our problems."*

   Keep, soften, or replace? These are your **quotable moments** — the lines an ExCo member might repeat to a colleague later.

---

👉 Once you validate (or request tweaks), I'll deliver **Slide 6 — Case Studies (Part 1: Lazarus & Russian Proxies)** — where we anchor the abstract trends in real-world events with dates, figures, and impact .