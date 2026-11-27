---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may only use the Services where permitted by law.
  entity_types:
  - text: The Services are designed for healthcare providers, telehealth companies, and related service providers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not medical advice
    text: The Services do not constitute medical advice.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Healthcare users may be required to verify identity and credentials. Failure to verify may restrict access.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Docura Health
provenance_date: '2026-11-09'
provider_name: Docura Health
provider_slug: docura-health
slug: docura-health-eligibility
source_date: '2026-11-09'
source_filename: docura-health-eligibility.yml
source_heading: Eligibility
source_page: https://docurahealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Docura Health\naid: docura-health\nurl: https://docurahealth.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may only use the Services where permitted by law.\nentity_types:\n- type: business\n  text: The Services are designed for healthcare providers, telehealth companies, and related service providers.\nrestricted_uses:\n- summary: Not medical advice\n  text: The Services do not constitute medical advice.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Healthcare users may be required to verify identity and credentials. Failure\
  \ to verify may restrict access.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/docura-health/eligibility/docura-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Docura Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health
- Medical-Legal
- Medical Records
- Impairment Rating
- IME
- QME
- Workers Compensation
- HIPAA
- Clinical Documentation
---
