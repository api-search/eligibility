---
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Website, the Mobile App, and related services are limited to users located in U.S. states where such services are made available by Rula and the Group.
  entity_types:
  - text: The Website and the Mobile App are intended for use by individuals who are at least eighteen (18) years old, including parents and legal guardians managing care on behalf of minors.
    type: individual
  - text: To register as a Provider with Rula and utilize the Website in such capacity, you must be a licensed physician, nurse practitioner, or other qualified healthcare professional engaged or contracted by the Group
    type: other
  minimum_age:
    text: at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: AI Feature not for emergencies or care
    text: THE AI FEATURE IS NOT MEDICAL CARE, BEHAVIORAL HEALTH TREATMENT, PSYCHOTHERAPY, COUNSELING, DIAGNOSIS, CLINICAL GUIDANCE, CRISIS INTERVENTION, OR EMERGENCY SUPPORT.
  - summary: Not for emergencies
    text: The Website, the Mobile App, and their services, including any messaging functionality, are not intended for medical emergencies or urgent situations and are not monitored continuously.
  - summary: No commercial use of AI Feature
    text: use the AI Feature for any commercial purpose, including to provide services to third parties
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Rula may require proof of age, identity, or legal authority at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rula
provenance_date: '2026-11-10'
provider_name: Rula
provider_slug: rula
slug: rula-eligibility
source_date: '2026-11-10'
source_filename: rula-eligibility.yml
source_heading: Eligibility
source_page: https://www.rula.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rula\naid: rula\nurl: https://www.rula.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Website, the Mobile App, and related services are limited to users located in U.S.\n    states where such services are made available by Rula and the Group.\nentity_types:\n- type: individual\n  text: The Website and the Mobile App are intended for use by individuals who are at least eighteen (18) years\n    old, including parents and legal guardians managing care on behalf of minors.\n- type: other\n  text: To register as a Provider\
  \ with Rula and utilize the Website in such capacity, you must be a licensed physician,\n    nurse practitioner, or other qualified healthcare professional engaged or contracted by the Group\nrestricted_uses:\n- summary: AI Feature not for emergencies or care\n  text: THE AI FEATURE IS NOT MEDICAL CARE, BEHAVIORAL HEALTH TREATMENT, PSYCHOTHERAPY, COUNSELING, DIAGNOSIS, CLINICAL\n    GUIDANCE, CRISIS INTERVENTION, OR EMERGENCY SUPPORT.\n- summary: Not for emergencies\n  text: The Website, the Mobile App, and their services, including any messaging functionality, are not intended\n    for medical emergencies or urgent situations and are not monitored continuously.\n- summary: No commercial use of AI Feature\n  text: use the AI Feature for any commercial purpose, including to provide services to third parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Rula may require proof of age, identity, or legal authority at any time.\nminimum_age:\n  value: '18'\n \
  \ text: at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/rula/eligibility/rula-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Rula's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mental Health
- Telehealth
- Healthcare
- Behavioral Health
- Therapy
- Psychiatry
- Insurance
---
