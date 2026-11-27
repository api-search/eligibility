---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be at least 18 years of age
    type: individual
  - text: If you use the Platform on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: Be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: No medical advice to others
    text: Use the Platform to provide medical advice or diagnosis to others.
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
name: BioMind
provenance_date: '2026-11-09'
provider_name: BioMind
provider_slug: biomind
slug: biomind-eligibility
source_date: '2026-11-09'
source_filename: biomind-eligibility.yml
source_heading: Eligibility
source_page: https://www.biomindhealth.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BioMind\naid: biomind\nurl: https://www.biomindhealth.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be at least 18 years of age\n- type: business\n  text: If you use the Platform on behalf of an organization, you represent that you have authority to bind that\n    organization to these Terms.\nrestricted_uses:\n- summary: No medical advice to others\n  text: Use the Platform to provide medical advice or diagnosis to others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: Be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/biomind/eligibility/biomind-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BioMind's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Health
- Biotechnology
- Education
- Platform
---
