# 🩺 DhanvaCare  
**MedGemma Impact Challenge 2026**

**DhanvaCare** is a **conceptual, design-focused AI healthcare decision-support ecosystem** built using **Google MedGemma (HAI-DEF)** and **HeAR (Health Acoustic Representations)**.  
It is designed to **reduce preventable medical errors caused by miscommunication**—between patients and clinicians, across care teams, and during critical medical handoffs.

Named after *Dhanvantari* as a historical association with medicine, DhanvaCare reflects a design philosophy that combines **trusted medical knowledge with modern, safety-aligned AI** to improve clarity, continuity, and care coordination.

> **TL;DR:** A MedGemma-powered, safety-first healthcare support system focused on reducing misdiagnosis caused by medical miscommunication.

> ⚠️ **Important**: This submission is a **non-clinical, non-diagnostic prototype**. All outputs are illustrative. No real patient data, backend pipelines, or clinical decision logic are included.

---

# 🌍 **The Problem I Witnessed (Why DhanvaCare Exists)**

I have *personally witnessed multiple deaths and serious medical complications* that occurred not due to negligence, but due to **unintentional misdiagnosis caused by miscommunication**.

* Patients, overwhelmed by pain or anxiety, often miss mentioning subtle symptoms that later turn out to be crucial.

* Doctors and nurses, working under extreme time pressure, may initially interpret symptoms as common conditions.

* During medical handoffs, vital information can be delayed, fragmented, or lost.

None of this is intentional — it is a **systemic human limitation in high-pressure healthcare environments**.

These gaps inspired me to build **DhanvaCare** — *a system that listens better, remembers better, and communicates better* than traditional workflows.

---

# 🚀 **The Solution**

**DhanvaCare** is designed to capture patient information once, structure it intelligently, and reuse it safely across care journeys.

**DhanvaCare** is an AI-assisted, non-diagnostic Clinical Decision Support System designed to:

* Capture structured symptom input

* Interpret symptoms using MedGemma

* Align outputs with clinical safety guardrails

* Generate triage recommendations

* Maintain clinician-in-the-loop oversight

⚠️ The system does NOT provide medical diagnoses.
It supports triage and structured communication.

*Better symptom capture → better clinical reasoning → safer outcomes.*

It *does not replace doctors.*
It supports them, especially when time, clarity, and continuity are at risk.

---

# 🌟 **Core Capabilities — The 6-Pillar Framework**

> *This prototype focuses on demonstrating a unified safety-first workflow rather than fully implementing each module.*

1️⃣ **AI Diagnosis & Intelligent Triage**

A shared tool for patients, nurses, and doctors

**Multimodal inputs:**

* 📝 Text
* 🎤 Voice (HeAR)
* 📷 Camera (visual symptoms)
* 📄 Medical document importer

* Local-language UI support (designed for countries like India)

* Conversational Q&A-style symptom intake

AI-generated diagnostic report with:
* Structured symptom summary
* Risk triage
* Probable condition ranges (non-diagnostic)
Nurses or staff can collect complete information before the doctor arrives, making treatment faster and more efficient.

---

**2️⃣ Emergency Response Section 🚑**

Designed for Golden Hour situations

* Immediate guidance for:

     * Heart attack
     * Stroke
     * Critical emergencies

* One-tap emergency helplines
* Nearby hospitals and emergency centers
* Symptom-triggered escalation logic

---

**3️⃣ Doctors Nearby (Smart Discovery) 🗺️**

* A map-based interface for informed healthcare access

* Discover doctors based on:

    * Rating
    * Fee / affordability
    * Specialty
    * Distance & availability

* Especially useful for:

    * Migrants (students & professionals)
    * People new to a city
    * Emergency situations

  ---

  **4️⃣ Online Consultation 💻**

* Healthcare without physical barriers
* Designed for:

    * Physically handicapped individuals
    * Elderly patients
    * Busy professionals

* AI-generated pre-consult summaries
* Saves time for both patient and doctor

---

**5️⃣ Med Record (Secure Med-Vault) 🛡️**

* Continuity of care when time is critical
* Centralized medical history
* Instantly shareable during emergencies
* Prevents delays caused by searching old reports
* Built with privacy, consent, and security as core principles

---

**6️⃣ AI Animation & Visualization 🎥**

* Understanding before consent

* AI-generated animated videos explaining:

     * What happened in the body
     * Disease progression
     * Treatment or surgery necessity

* Used by:
     * *Patients → clarity & reduced fear*
     * *Doctors → better communication & informed consent*

---

# **🧠 High-Level System Architecture**

**Patient Inputs**
 ├── Text
 
 ├── Voice (HeAR)
 
 ├── Camera
 
 └── Documents
        ↓
        
**Multimodal AI Layer**

 ├── MedGemma (Clinical Reasoning)
 
 └── HeAR (Acoustic Health Signals)
        ↓
        
**Decision & Safety Layer**

 ├── Symptom Structuring
 
 ├── Risk Triage
 
 ├── Emergency Escalation
        ↓
        
**Care Interfaces**

 ├── Diagnosis Report
 
 ├── Doctor Discovery
 
 ├── Tele-Consultation
 
 └── Med-Vault

> Black-box representation only. No clinical scoring or diagnostic logic included.
---

# **🛠️ Technology Stack**

* AI Models ( Future Integration)

    * Google MedGemma (HAI-DEF)
    * HeAR (Health Acoustic Representations)

* Cloud & Deployment ( Future)

    * Google Cloud Vertex AI

* Frontend

     * Vibe-coded Web Architecture 

* Design Philosophy

     * Human-Centric Design Thinking
 
---

# 📊 Intended Evaluation (Conceptual)

The system would be evaluated on:
- Completeness of symptom capture  
- Reduction of information loss during handoffs  
- Clinician time saved during intake  
- Safety alignment and conservativeness of AI outputs  

---

# 1️⃣ Frontend Prototype (Lovable)

* A no-code UI prototype demonstrating user interaction

* Simulates patient and clinician workflows

* Uses mocked AI responses for demonstration

🔗**Prototype Link:** https://dhanvacare-ai-trisha.lovable.app

---

# 📓 Backend Intelligence [Kaggle Notebook (Core AI Logic)]

The primary MedGemma-based reasoning and prompt design are demonstrated in a Kaggle notebook submitted as part of the Google MedGemma Impact Challenge 2026.

🔗 **Kaggle Notebook:** https://www.kaggle.com/code/trishadayanand/dhanvacare-ai-powered-symptom-triage-assistant

Due to ethical, deployment, and security considerations, live model inference is not connected to the frontend. All AI reasoning is transparently demonstrated in the notebook.

---

# **🔒 Ethics, Safety & Responsibility**

* ❌ No autonomous diagnosis or prescriptions
* ✅ AI acts as clinical decision support only
* 🔐 Consent-based medical data access
* 🧠 Bias-aware and safety-aligned design
* 👨‍⚕️ Doctors remain the final authority

---

# 🚀 **Future Developmental Phases and Scope**

**Developmental Phase**
Phase 1 – Concept & Prototype (Completed)
Phase 2 – API Integration & Live Model Inference
Phase 3 – Real-world Validation & User Testing
Phase 4 – Clinical Collaboration & Deployment

**Future Scope**
**🌿 Veda Alchemix** (Future Feature within DhanvaCare)

Veda Alchemix will be introduced as a wellness intelligence module that bridges the traditional wisdom of Ayurveda with modern lifestyle needs.

Planned capabilities:

* Translate Ayurvedic principles into practical, kitchen-friendly wellness recommendations.
* Suggest food-based preventive care aligned with user health profiles.
* Provide evidence-informed traditional remedy guidance alongside modern medical triage (clearly separated as supportive wellness, not diagnosis).
* Promote preventive healthcare by connecting traditional roots of Ayurveda into the modern kitchen ecosystem.

**🌍 Ecosystem Expansion**
Integration with wearable health devices.
Hospital and telemedicine platform interoperability.
Population-level health analytics for public health insights.
Offline-first lightweight deployment for rural and low-connectivity regions.


# **🧬 About the Developer**

I am **Trisha. D**, a first-year Computer Science & Engineering student at Sir MVIT, Bengaluru, India, with a strong foundation in Biology from Pre-University College (+1 & +2). While I am early in my CS journey and have limited coding experience, I have leveraged AI-assisted design tools and conceptual modeling to create DhanvaCare — a prototype focused on reducing preventable medical errors through human-centered AI.

# **❤️ Closing Note**

**DhanvaCare** was born not from theory, but from **witnessing how small communication gaps can cost lives.*
This project is my attempt to reduce those gaps — with empathy, technology, and responsibility.

Developed with ❤️ to make healthcare safer, clearer, and more human.

### ✅ CC BY 4.0 / Prototype Safety

This repository and submission are licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

- Only **conceptual, illustrative, and design-focused elements** are included.  
- **Core AI pipelines, clinical decision logic, backend systems, and real patient data** are intentionally excluded to protect intellectual property and ensure patient safety.  
- This prototype demonstrates **workflow, UX, and impact**, not a production-ready clinical system.  
- AI is intended **only as decision support**, and doctors remain the final authority.

📌 *For the personal motivation and real-world experiences that inspired this project, see* **Vision.md**.
