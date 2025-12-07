# AI-Powered Document Intelligence for Insurance & Compliance  
### Cutting Document Review Time from Minutes to Seconds

This case study explains how BIS Advisors designed and deployed an AI-powered 
document intelligence system that dramatically reduces the time required to 
interpret long, dense, and cross-referenced documents such as:

- Insurance policies (cyber, property, liability, ESG)
- SOC 2 Type I/II reports
- NIST 800-53 and 800-171 frameworks
- Cyber endorsements, exclusions, and regulatory guidance
- Audit evidence and compliance documentation

The system consistently delivers:

- **80–90% reduction in document lookup time**  
- **2–7 second grounded, citation-backed answers**  
- **Low-to-mid 90% accuracy**  
- **Hybrid deployment across on-prem RTX 4090 and GCP L4**  
- **Predictable, low compute costs per question**

---

## 📄 Full Case Study (PDF)

👉 **[Download CaseStudy.pdf](./CaseStudy.pdf)**  
(If the link fails before upload, place the PDF in this folder.)

---

## 🔧 Technical Overview

The solution is built using a domain-optimized Retrieval-Augmented Generation (RAG) 
pipeline with the following components:

| Component | Implementation |
|----------|----------------|
| Language | Python |
| LLM | Llama 3.1 Instruct 8B (self-hosted) |
| Inference | vLLM |
| Embeddings | Llama 3.1 Embeddings |
| Vector DB | FAISS |
| Deployment | Hybrid: On-prem RTX 4090 + GCP L4 |

---

## 🚀 Business Impact

Across underwriting, claims, cybersecurity, and audit workflows, the system enables:

- Faster and more consistent decision-making  
- Clear, traceable responses backed by source citations  
- Reduced operational effort and analyst fatigue  
- Improved compliance and audit readiness  

---

## 🧠 About BIS Advisors

BIS Advisors helps insurance, finance, and regulated industries deploy practical, 
reliable AI systems—focused on cost-efficient self-hosted LLMs, hybrid deployments, 
and document intelligence solutions.

https://bisadvisors.com  
connect@bisadvisors.com

---

## 📁 Repository Structure


