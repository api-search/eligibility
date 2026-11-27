---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    - GB
    - CH
    - AU
    - NZ
    - IN
    - IL
    - TR
    - BR
    - CO
    - AR
    - CL
    - PE
    - JP
    - KR
    text: The Solutions and Services are intended for access and use in the United States, Canada, the European Union, the United Kingdom, Switzerland, Australia, New Zealand, India, Israel, Türkiye, Brazil, Colombia, Argentina, Chile, Peru, Japan, South Korea, and other jurisdictions where Massive Bio lawfully offers the Solutions and Services.
  entity_types:
  - text: You must have legal capacity to enter into these Terms. Unless a Solution expressly supports an authorized parent, guardian, caregiver, or institutional workflow, individual account holders must be at least 18 years old.
    type: individual
  - text: Healthcare professionals and organizational users must be authorized to act in their stated role and on behalf of the organization they identify.
    type: business
  minimum_age:
    text: individual account holders must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No medical care substitution
    text: DOES NOT PRACTICE MEDICINE THROUGH THE SOLUTIONS, DOES NOT REPLACE A LICENSED HEALTHCARE PROFESSIONAL
  - summary: No unlawful discriminatory decisions
    text: Do not use the Solutions to make unlawful discriminatory decisions, send unlawful communications, or conduct unauthorized marketing.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Massive Bio may verify identity, professional status, credentials, affiliations, organization relationships, eligibility, and authority to use a Solution.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Massive Bio
provenance_date: '2026-11-10'
provider_name: Massive Bio
provider_slug: massive-bio
slug: massive-bio-eligibility
source_date: '2026-11-10'
source_filename: massive-bio-eligibility.yml
source_heading: Eligibility
source_page: https://massivebio.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Massive Bio\naid: massive-bio\nurl: https://massivebio.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  - GB\n  - CH\n  - AU\n  - NZ\n  - IN\n  - IL\n  - TR\n  - BR\n  - CO\n  - AR\n  - CL\n  - PE\n  - JP\n  - KR\n  excluded: []\n  text: The Solutions and Services are intended for access and use in the United States, Canada, the European Union,\n    the United Kingdom, Switzerland, Australia, New Zealand, India, Israel, Türkiye, Brazil, Colombia, Argentina,\n    Chile, Peru, Japan, South Korea, and other jurisdictions where Massive Bio lawfully offers the Solutions\
  \ and\n    Services.\nentity_types:\n- type: individual\n  text: You must have legal capacity to enter into these Terms. Unless a Solution expressly supports an authorized\n    parent, guardian, caregiver, or institutional workflow, individual account holders must be at least 18 years\n    old.\n- type: business\n  text: Healthcare professionals and organizational users must be authorized to act in their stated role and on\n    behalf of the organization they identify.\nrestricted_uses:\n- summary: No medical care substitution\n  text: DOES NOT PRACTICE MEDICINE THROUGH THE SOLUTIONS, DOES NOT REPLACE A LICENSED HEALTHCARE PROFESSIONAL\n- summary: No unlawful discriminatory decisions\n  text: Do not use the Solutions to make unlawful discriminatory decisions, send unlawful communications, or conduct\n    unauthorized marketing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Massive Bio may verify identity, professional status, credentials, affiliations, organization\
  \ relationships,\n    eligibility, and authority to use a Solution.\nminimum_age:\n  value: '18'\n  text: individual account holders must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/massive-bio/eligibility/massive-bio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Massive Bio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Oncology
- Clinical Trials
- Artificial Intelligence
- Cancer Care
- Digital Health
- Patient Matching
- Genomics
---
