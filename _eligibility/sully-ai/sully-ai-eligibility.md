---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may be required to register with Sully.ai or provide information about yourself (e.g., name and email address) in order to access and use certain features of the Service.
    type: individual
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering. In addition, if you are under 18 years old, you may use the Service, with or without registering, only with the express consent of your parent or guardian
    value: '13'
  restricted_uses:
  - summary: No emergency medical or mental health care
    text: DO NOT USE THE SERVICE TO PROVIDE EMERGENCY MEDICAL OR MENTAL HEALTH CARE SERVICES.
  - summary: Competitors barred from access
    text: No employee, independent contractor, agent, or affiliate of any competing company offering a virtual AI assistant in the medical field is permitted to view, access, or use any portion of the Service without express written permission from Sully.ai.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: SULLY.AI DOES NOT VERIFY THE VALIDITY OF YOUR CREDENTIALS AND YOU ARE RESPONSIBLE FOR HAVING THE CREDENTIALS REQUIRED TO PROVIDE YOUR SERVICES.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sully AI
provenance_date: '2026-11-10'
provider_name: Sully AI
provider_slug: sully-ai
slug: sully-ai-eligibility
source_date: '2026-11-10'
source_filename: sully-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.sully.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sully AI\naid: sully-ai\nurl: https://www.sully.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may be required to register with Sully.ai or provide information about yourself (e.g., name and email\n    address) in order to access and use certain features of the Service.\nrestricted_uses:\n- summary: No emergency medical or mental health care\n  text: DO NOT USE THE SERVICE TO PROVIDE EMERGENCY MEDICAL OR MENTAL HEALTH CARE SERVICES.\n- summary: Competitors barred from access\n  text: No employee, independent\
  \ contractor, agent, or affiliate of any competing company offering a virtual AI\n    assistant in the medical field is permitted to view, access, or use any portion of the Service without express\n    written permission from Sully.ai.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: SULLY.AI DOES NOT VERIFY THE VALIDITY OF YOUR CREDENTIALS AND YOU ARE RESPONSIBLE FOR HAVING THE CREDENTIALS\n    REQUIRED TO PROVIDE YOUR SERVICES.\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.\n    In addition, if you are under 18 years old, you may use the Service, with or without registering, only with\n    the express consent of your parent or guardian\n"
source_yaml_url: https://artifacts.apis.io/sully-ai/eligibility/sully-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Sully AI's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Health Tech
- Medical AI
- Clinical AI
- AI Scribe
- Ambient Scribe
- Clinical Documentation
- SOAP Notes
- Medical Coding
- ICD-10
- CPT
- SNOMED
- Speech-to-Text
- Audio Transcription
- Real-Time Streaming
- WebSocket
- Webhook
- EHR Integration
- Epic
- Cerner
- HIPAA
- AI Agents
- Workflow Automation
- Healthcare Automation
---
