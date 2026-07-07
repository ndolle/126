dissoj@aua.ac.ke  
July 07, 2026


# yes slide 3

# 🎯 Slide 3 — Actor Mapping: China & Russia

This is your **first "meaty" content slide** — where ExCo starts taking notes. The key is to make each actor feel **distinct and memorable**. Think of it as introducing two very different adversaries with very different playbooks .

---

## 🖼 On-Slide Content

### **Title (top):**
> # Threat Actor Mapping (1/2)
> ### *The "Big Four" — Part 1: Patient Espionage vs. Kinetic Sabotage*

### **Layout — Two side-by-side "actor cards":**

---

#### 🇨🇳 **CHINA** — *Espionage & IP Theft*
> **"Patient economic dominance."**

| Dimension | Detail |
|---|---|
| 🎯 **Motivation** | Long-term strategic advantage & global economic dominance  |
| 📍 **Primary Targets** | Intellectual property, critical infrastructure, advanced manufacturing  |
| 🛠 **Methods** | Stealthy, low-noise TTPs — extensive *Living off the Land*  |
| ⚡ **Signature Trait** | **Patience** — dwell times measured in months, sometimes years |
| 🔎 **Recent Marker** | UNC3886 — Singapore telecoms compromise (Feb 2026)  |

---

#### 🇷🇺 **RUSSIA** — *Sabotage & Disruption*
> **"Cyber as an extension of the battlefield."**

| Dimension | Detail |
|---|---|
| 🎯 **Motivation** | Geopolitical intimidation integrated with kinetic military operations  |
| 📍 **Primary Targets** | Energy grids, government networks, logistics, Ukraine support lines  |
| 🛠 **Methods** | Heavy proxy reliance; destructive wipers disguised as ransomware  |
| ⚡ **Signature Trait** | **Deniability** — hacktivist proxies muddy attribution |
| 🔎 **Recent Marker** | Polish power grid attacks — ~30 sites (Dec 2025-Jan 2026)  |

---

### **Bottom banner (thin, spanning both columns):**
> **Same category ("nation-state"), completely different playbooks. Our defense must match both.**

---

## 🎤 Speaker Notes (what you say — ~3 minutes)

> *"Now let's meet the adversaries. Over this slide and the next, I'll walk you through the four nation-states that dominate the threat landscape. What matters is not memorizing their names — it's understanding that **each has a distinct motivation, and therefore a distinct playbook**. Our defenses have to account for all four."*
>
> **[Turn to the China card]**
> *"Start with **China**. If I had to describe China in one word, it would be **patient**.*
>
> *China's strategic goal is not to disrupt us. It is to **surpass us economically** — over decades. That reframes everything they do. They don't want to be noticed. They want to be inside our networks, quietly, for as long as possible, harvesting intellectual property, mapping our critical infrastructure, and understanding how our industries work* .
>
> *Their tradecraft is exceptional. They favor what we call **'Living off the Land'** — using tools that are already legitimately installed on our systems, so no malware alarm goes off. A Chinese operator inside your network looks, to your monitoring tools, like a normal system administrator* . *That's what makes them so dangerous.*
>
> *The clearest recent example is **UNC3886** — the group that compromised **all four major telecom operators in Singapore**, using zero-day vulnerabilities and rootkits, for months of undetected espionage. The Singaporean government had to launch its largest-ever cyber defense operation just to expel them* . *We'll come back to this case."*
>
> **[Turn to the Russia card]**
> *"**Russia is the opposite.** Where China wants to remain invisible, Russia wants you to **know they were there** — but not be able to prove it.*
>
> *Russia's cyber operations are an **extension of its military doctrine**. Since the war in Ukraine escalated, we have seen cyber attacks synchronized with kinetic operations — the digital equivalent of artillery preparation before an assault* .
>
> *Their signature move is the **wiper disguised as ransomware**. It looks like a criminal attack demanding money, but the encryption is irreversible — the goal was never payment. The goal was **destruction**, with plausible deniability wrapped around it* .
>
> *Their targets tell the strategic story: **energy grids, logistics, government networks** — anything that supports Ukraine or NATO. In December and January, coordinated attacks hit around **thirty sites of the Polish power grid** . *Poland is a critical logistics hub for Ukrainian support. That is not a coincidence. That is doctrine."*
>
> **[Deliver the bottom banner slowly]**
> *"So — same category on paper. **Completely different playbooks in practice.** China wants your secrets. Russia wants your operations offline. A defense strategy that assumes 'nation-state = one thing' will fail against both."*

---

## 🎨 Design & Visual Direction

| Element | Recommendation |
|---|---|
| **Layout** | Strict two-column symmetry — reinforces the "compare and contrast" message |
| **Flag/color accent** | Subtle national flag colors as accent bars (red for China, red-blue for Russia) — but muted, not cartoonish |
| **Actor headshot/logo** | ❌ Avoid stock imagery of hooded hackers. Use a clean iconographic silhouette or country outline instead |
| **Signature Trait row** | Make this row **visually distinct** (bold, colored) — it's your memorable "one word" per actor |
| **Recent Marker row** | Same style — creates a mental anchor to the case studies you'll present later |
| **Bottom banner** | Same dark-bar style as Slide 2 for visual consistency |

💡 **Pro tip:** If you have animation available, reveal the two cards **sequentially** — talk about China with only that side visible, then reveal Russia. This forces attention and prevents ExCo from reading ahead.

---

## 💡 Anticipated ExCo Questions (be ready)

**Q1: "Which of the two is a bigger threat to *us*?"**
> Suggested answer: *"Different threats, both material. **China** is the bigger risk to our **long-term competitive position** — through IP theft and infrastructure mapping. **Russia** is the bigger risk to our **operational continuity** — especially given our exposure to Central and Eastern European markets, and any activity that touches sanctions enforcement or Ukraine-related financing. I don't rank them — I plan for both."*

**Q2: "You said Russia uses wipers disguised as ransomware. How do we tell the difference during an incident?"**
> Suggested answer: *"In the first hours, we often can't — and that's the point. Our incident response has to assume the **worst case** — that recovery from backups may be the only path, and that paying a ransom would be both useless and, in Russia's case, potentially a sanctions violation. This is why **resilience** — the ability to operate in degraded mode — matters more than negotiation capability."*

**Q3: "'Living off the Land' — if they use our own tools, can we even detect them?"**
> Suggested answer: *"Yes, but it requires a different detection paradigm. Instead of looking for **malware signatures**, we look for **behavioral anomalies** — a legitimate admin tool being used at 3am, by an account that doesn't normally touch that server, from an unusual geography. This is where **UEBA** — User and Entity Behavior Analytics — and mature SOC operations become non-negotiable. Under-investing here leaves us blind to exactly the actors we most need to see."*

**Q4: "Is Russia still capable at this level, given the war and sanctions?"**
> Suggested answer: *"Categorically yes. Cyber is one of the few domains where Russia has **increased** activity since 2022, not decreased. Sanctions constrain their conventional military-industrial complex, but their cyber apparatus is cheap, deniable, and asymmetric — exactly the kind of capability a constrained state doubles down on."*

**Q5: "Do these actors ever collaborate?"** *(the strategic-thinker question)*
> Suggested answer: *"Rarely operationally, but they **learn from each other**. Tools, techniques, and lessons flow between them — especially between Russia and North Korea, and increasingly Iran and Russia via Ukraine. It's not an alliance, but it's a shared learning curve — and it accelerates the threat for us."*

---

## ✅ Validation Checkpoints

Before we move to Slide 4 (Iran & North Korea), please confirm or adjust:

1. **Card structure** — The 5-row layout (Motivation / Targets / Methods / Signature Trait / Recent Marker) — keep as is, or simplify to the original 3-row structure from your source (Motivation / Targets / Methods only) ?
2. **"Signature Trait" row** — I added this as a memorability hook (**Patience** for China, **Deniability** for Russia). Keep, or drop it as an editorializing addition?
3. **BNP-specific framing in Q&A** — I referenced "Central/Eastern European exposure" and "sanctions enforcement" in the Q1 answer. Accurate for your context, or should I strip bank-specific references and keep it generic?
4. **Sequential reveal (animation)** — Comfortable with animation, or prefer a static slide? Some ExCo audiences find click-throughs annoying if overdone.
5. **Flag imagery** — OK with subtle flag color accents, or entirely avoid national imagery (some organizations prefer neutral geopolitical framing)?

---

👉 Once you validate (or request tweaks), I'll deliver **Slide 4 — Actor Mapping: Iran & North Korea** in the same format, maintaining visual and narrative consistency.