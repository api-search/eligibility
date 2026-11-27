---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Platform is intended for use only within the United States by individuals 18 years of age or older.
  minimum_age:
    text: individuals 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: No emergencies
    text: The Platform is not designed for medical or psychiatric emergencies.
  - summary: No controlled substances
    text: MDI clinicians do not prescribe controlled substances through the Platform.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may request information to verify your age, identity, and location before allowing you to use certain features or request a Consultation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: August AI
provenance_date: '2026-11-09'
provider_name: August AI
provider_slug: august-ai
slug: august-ai-eligibility
source_date: '2026-11-09'
source_filename: august-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.meetaugust.ai/terms/us
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: August AI\naid: august-ai\nurl: https://www.meetaugust.ai/terms/us\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Platform is intended for use only within the United States by individuals 18 years of age or older.\nentity_types: []\nrestricted_uses:\n- summary: No emergencies\n  text: The Platform is not designed for medical or psychiatric emergencies.\n- summary: No controlled substances\n  text: MDI clinicians do not prescribe controlled substances through the Platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may request information\
  \ to verify your age, identity, and location before allowing you to use certain\n    features or request a Consultation.\nminimum_age:\n  value: '18'\n  text: individuals 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/august-ai/eligibility/august-ai-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from August AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Health
- Telehealth
- Healthcare
- Health AI
- Medical
- Consumer Health
- Symptom Checker
- WhatsApp
---
