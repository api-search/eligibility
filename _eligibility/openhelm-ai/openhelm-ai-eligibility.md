---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you confirm that you are at least 18 years old (or the age of majority in your jurisdiction)
    type: individual
  - text: If you are using OpenHelm on behalf of a company or other legal entity, you represent that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: you confirm that you are at least 18 years old (or the age of majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: GDPR personal data processing
    text: Process personal data of EU/EEA residents in violation of GDPR
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
name: openhelm-ai
provenance_date: '2026-11-10'
provider_name: openhelm-ai
provider_slug: openhelm-ai
slug: openhelm-ai-eligibility
source_date: '2026-11-10'
source_filename: openhelm-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.openhelm.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: openhelm-ai\naid: openhelm-ai\nurl: https://www.openhelm.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you confirm that you are at least 18 years old (or the age of majority in your jurisdiction)\n- type: business\n  text: If you are using OpenHelm on behalf of a company or other legal entity, you represent that you have the\n    authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: GDPR personal data processing\n  text: Process personal data of EU/EEA residents in violation of GDPR\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you confirm that you are at least 18 years old (or the age of majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/openhelm-ai/eligibility/openhelm-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from openhelm-ai's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Productivity
- Software-as-a-Service
- Platform
---
