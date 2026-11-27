---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To be eligible to use the Service, you must be at least 18 years of age and have legal capacity to agree to these Terms of Use
    type: individual
  minimum_age:
    text: you must be at least 18 years of age and have legal capacity to agree to these Terms of Use
    value: '18'
  restricted_uses:
  - summary: Law enforcement access
    text: Law enforcement agencies, government officials, and their agents are prohibited from creating accounts on the Service, uploading DNA data to the Service, or using the Service in any way for investigative, surveillance, or forensic purposes.
  - summary: DNAsolves geographic restriction
    text: DNAsolves is not available to residents of Maryland, Florida, or New Jersey
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
name: AWAKENS
provenance_date: '2026-11-09'
provider_name: AWAKENS
provider_slug: awakens
slug: awakens-eligibility
source_date: '2026-11-09'
source_filename: awakens-eligibility.yml
source_heading: Eligibility
source_page: https://genomelink.io/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AWAKENS\naid: awakens\nurl: https://genomelink.io/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To be eligible to use the Service, you must be at least 18 years of age and have legal capacity to agree\n    to these Terms of Use\nrestricted_uses:\n- summary: Law enforcement access\n  text: Law enforcement agencies, government officials, and their agents are prohibited from creating accounts on\n    the Service, uploading DNA data to the Service, or using the Service in any way for investigative,\
  \ surveillance,\n    or forensic purposes.\n- summary: DNAsolves geographic restriction\n  text: DNAsolves is not available to residents of Maryland, Florida, or New Jersey\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years of age and have legal capacity to agree to these Terms of Use\n"
source_yaml_url: https://artifacts.apis.io/awakens/eligibility/awakens-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AWAKENS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Genomics
- DNA
- Bioinformatics
- Health
- Consumer Genetics
- Ancestry
- OAuth
- Personal Genomics
- Authentication
---
