---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 18 years old;
    type: individual
  - text: If You are accepting these Terms on behalf of a company, limited liability partnership, partnership or any other legal entity, You have the authority to bind such entity to these Terms
    type: business
  minimum_age:
    text: You are at least 18 years old;
    value: '18'
  restricted_uses:
  - summary: Export control violations
    text: export or re-export the Site or any portion thereof, or any software available on or through the Site, in violation of the export control laws or regulations of India
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
name: greytHR
provenance_date: '2026-11-09'
provider_name: greytHR
provider_slug: greythr
slug: greythr-eligibility
source_date: '2026-11-09'
source_filename: greythr-eligibility.yml
source_heading: Eligibility
source_page: https://www.greythr.com/terms-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: greytHR\naid: greythr\nurl: https://www.greythr.com/terms-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 18 years old;\n- type: business\n  text: If You are accepting these Terms on behalf of a company, limited liability partnership, partnership or any\n    other legal entity, You have the authority to bind such entity to these Terms\nrestricted_uses:\n- summary: Export control violations\n  text: export or re-export the Site or any portion thereof, or any software available on or through the Site, in\n \
  \   violation of the export control laws or regulations of India\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old;\n"
source_yaml_url: https://artifacts.apis.io/greythr/eligibility/greythr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from greytHR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Human Resources
- Payroll
- Artificial Intelligence
- Software-as-a-Service
---
