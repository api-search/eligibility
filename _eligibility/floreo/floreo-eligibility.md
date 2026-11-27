---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States and other territories expressly authorized by Floreo.. We make no representation that the Service is appropriate or available for use outside of the United States.
  entity_types:
  - text: To become an End-user of this Service, you must be at least 18 years old to create an account to use the Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: you must be at least 18 years old to create an account to use the Service.
    value: '18'
  restricted_uses:
  - summary: Illegal use prohibited
    text: use the Service for any illegal purpose or in violation of any local, state, national, or international law
  - summary: Research requiring IRB approval
    text: using the Service as part of research that requires approval from an institutional review board (IRB) without our prior knowledge and written consent
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
name: Floreo
provenance_date: '2026-11-09'
provider_name: Floreo
provider_slug: floreo
slug: floreo-eligibility
source_date: '2026-11-09'
source_filename: floreo-eligibility.yml
source_heading: Eligibility
source_page: https://floreovr.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Floreo\naid: floreo\nurl: https://floreovr.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States and other territories expressly authorized\n    by Floreo.. We make no representation that the Service is appropriate or available for use outside of the United\n    States.\nentity_types:\n- type: individual\n  text: To become an End-user of this Service, you must be at least 18 years old to create an account to use the\n    Service.\n- type: business\n  text: If you are an entity, organization, or company,\
  \ the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: Illegal use prohibited\n  text: use the Service for any illegal purpose or in violation of any local, state, national, or international\n    law\n- summary: Research requiring IRB approval\n  text: using the Service as part of research that requires approval from an institutional review board (IRB) without\n    our prior knowledge and written consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old to create an account to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/floreo/eligibility/floreo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Floreo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Virtual Reality
- Digital Therapeutics
- Behavioral Health
- Healthcare
- Autism
- Neurodiversity
- Telehealth
- Education
---
