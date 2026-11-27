---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF CUSTOMER IS ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, CUSTOMER REPRESENTS THAT CUSTOMER HAS THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not medical advice
    text: THE EXACARE SOLUTION IS NOT INTENDED TO BE USED AS MEDICAL ADVICE, DIAGNOSIS, OR TREATMENT OF ANY MEDICAL CONDITION OR HEALTH PROBLEM
  - summary: Not time-critical functions
    text: the EXACARE Solution will not be used, and are not licensed for use, in connection with any of Customer’s time-critical or mission-critical functions.
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
name: ExaCare AI
provenance_date: '2026-11-09'
provider_name: ExaCare AI
provider_slug: exacare-ai
slug: exacare-ai-eligibility
source_date: '2026-11-09'
source_filename: exacare-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.exacare.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ExaCare AI\naid: exacare-ai\nurl: https://www.exacare.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF CUSTOMER IS ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, CUSTOMER REPRESENTS\n    THAT CUSTOMER HAS THE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: Not medical advice\n  text: THE EXACARE SOLUTION IS NOT INTENDED TO BE USED AS MEDICAL ADVICE, DIAGNOSIS, OR TREATMENT OF ANY MEDICAL\n    CONDITION OR HEALTH PROBLEM\n- summary: Not time-critical functions\n  text: the\
  \ EXACARE Solution will not be used, and are not licensed for use, in connection with any of Customer’s\n    time-critical or mission-critical functions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/exacare-ai/eligibility/exacare-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from ExaCare AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Post-Acute Care
- Senior Care
- Skilled Nursing
- Home Care
- Hospice
- Electronic Health Records
- Artificial Intelligence
- Revenue Cycle
---
