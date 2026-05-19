# NEURO-WIKI
A comprehensive, machine-readable knowledge base for neuroscience and recovery initiatives.
Complete Open Knowledge Base for Brain Injury Recovery
Status: ✅ COMPLETE & PRODUCTION-READY
Built: May 19, 2026
Version: 1.0.0

📋 Project Overview
NEURO-WIKI is a comprehensive, machine-readable and human-editable knowledge base serving as the central information repository for:

SENTINEL-NEURO: Patient wellness and care coordination application
NeuroAI Recovery Companion: AI-powered recovery support system
Third-party integrations: Via REST API for partners and developers
Clinical and research systems: Integration with care coordination platforms

Key Capability: Stores structured knowledge (conditions, interventions, assessments, resources, care plans) in human-readable JSON files, accessible via both REST API and web interface for browsing, searching, and editing.

🗂️ Data Entities & Content
1. Conditions (3 entries)
ID Pattern: cond_*

cond_tbi_mild - Mild Traumatic Brain Injury / Concussion
cond_tbi_moderate - Moderate Traumatic Brain Injury
cond_post_concussion_syndrome - Post-Concussion Syndrome

Fields: name, category, ICD-10, overview, symptoms, causes, severity levels, recovery timeline, linked interventions/assessments
2. Interventions (8 entries)
ID Pattern: int_*

int_cognitive_rest - Cognitive Rest / Activity Modification
int_gradual_return - Gradual Return to Activity Protocol
int_vestibular_therapy - Vestibular Rehabilitation Therapy
int_cognitive_rehab - Cognitive Rehabilitation Therapy
int_physical_therapy - Physical Therapy & Exercise
int_occupational_therapy - Occupational Therapy
int_mindfulness - Mindfulness & Meditation Practice
int_coaching - Brain Injury Coaching

Fields: name, type (therapy/exercise/medication/device/mindfulness/coaching), conditions addressed, frequency, duration, evidence level, benefits, contraindications, instructions, resources
3. Assessments (4 entries)
ID Pattern: asmt_*

asmt_gcs - Glasgow Coma Scale (level of consciousness)
asmt_pcss - Post-Concussion Symptom Scale (symptom reporting)
asmt_fim - Functional Independence Measure (disability/function)
asmt_cog_brief - Montreal Cognitive Assessment (brief cognitive screening)

Fields: name, abbreviation, purpose, domains, population, scoring method, administration, time required, validation evidence
4. Resources (15 entries)
ID Pattern: res_*
Types: Guidelines, research papers, tools, websites, external resources

CDC TBI Guidelines
ACRM Brain Injury Guidelines
Return to Activity Guidelines
Vestibular Society Guidelines
Cognitive Training Evidence
Physical Therapy Guidelines
Occupational Therapy Guidelines
Mindfulness Research
Brain Injury Coaching Standards
[10+ more clinical resources]

Fields: title, type, URL, authors, published date, summary, tags, relevance
5. Care Plan Templates (3 entries)
ID Pattern: cpt_*

cpt_tbi_mild_8week - 8-Week Mild TBI Recovery Plan

4 phases: Acute Rest → Light Activity → Moderate Activity → Return to Normal
Structured goals, interventions, and metrics for each phase


cpt_tbi_moderate_12week - 12-Week Moderate TBI Rehabilitation Plan

3 intensive rehabilitation phases with interdisciplinary team roles
Comprehensive ADL/IADL training progression


cpt_pcs_management - Post-Concussion Syndrome Management (3-Month)

Assessment → Targeted Rehabilitation → Integration & Long-Term Management
Symptom-specific management strategies



Fields: name, condition, phases (with goals/interventions/activities), metrics, caregiver support, red flags, specialist referrals
