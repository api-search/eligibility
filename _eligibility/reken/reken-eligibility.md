---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer acknowledges and agrees the Solutions shall not be used, transferred, or otherwise exported or re-exported to regions that the United States and/or the European Union maintains an embargo or comprehensive sanctions
  entity_types:
  - text: ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal data upload
    text: (vii) upload personal data as defined in the General Data Protection Regulation (GDPR) Regulation (EU) 2016/679, or similar data protection or privacy laws in applicable jurisdictions, without prior authorization from the data owner
  - summary: Hazardous or safety-critical use
    text: THE SOLUTIONS ARE NOT FAULT-TOLERANT AND ARE NOT DESIGNED OR INTENDED FOR USE IN ANY HAZARDOUS ENVIRONMENT REQUIRING FAIL-SAFE PERFORMANCE OR OPERATION.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Reken
provenance_date: '2026-11-10'
provider_name: Reken
provider_slug: reken
slug: reken-eligibility
source_date: '2026-11-10'
source_filename: reken-eligibility.yml
source_heading: Eligibility
source_page: https://reken.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reken\naid: reken\nurl: https://reken.ai/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer acknowledges and agrees the Solutions shall not be used, transferred, or otherwise exported or\n    re-exported to regions that the United States and/or the European Union maintains an embargo or comprehensive\n    sanctions\nentity_types:\n- type: business\n  text: ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY\nrestricted_uses:\n- summary: Personal data upload\n  text: (vii) upload personal data as defined in the General Data Protection Regulation (GDPR) Regulation (EU) 2016/679,\n\
  \    or similar data protection or privacy laws in applicable jurisdictions, without prior authorization from the\n    data owner\n- summary: Hazardous or safety-critical use\n  text: THE SOLUTIONS ARE NOT FAULT-TOLERANT AND ARE NOT DESIGNED OR INTENDED FOR USE IN ANY HAZARDOUS ENVIRONMENT\n    REQUIRING FAIL-SAFE PERFORMANCE OR OPERATION.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/reken/eligibility/reken-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Reken's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Security
- Cybersecurity
- Fraud Prevention
- Anti-Phishing
- Deepfakes
- Trust and Safety
- On-Device AI
---
