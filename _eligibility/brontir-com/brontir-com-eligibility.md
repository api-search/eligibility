---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and able to enter into a binding contract.
    type: individual
  - text: If you use the Service on behalf of an organisation, you represent that you are authorised to bind it.
    type: business
  minimum_age:
    text: You must be at least 18 and able to enter into a binding contract.
    value: '18'
  restricted_uses:
  - summary: Unlawful, harmful, or abusive activity
    text: conduct unlawful, harmful, deceptive, or abusive activity, unlawful surveillance or profiling, spam, or harassment
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Service you register an account with your email address and a password, or by signing in through a supported third-party provider (such as Google).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BRONTIR
provenance_date: '2026-11-09'
provider_name: BRONTIR
provider_slug: brontir-com
slug: brontir-com-eligibility
source_date: '2026-11-09'
source_filename: brontir-com-eligibility.yml
source_heading: Eligibility
source_page: https://brontir.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BRONTIR\naid: brontir-com\nurl: https://brontir.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to enter into a binding contract.\n- type: business\n  text: If you use the Service on behalf of an organisation, you represent that you are authorised to bind it.\nrestricted_uses:\n- summary: Unlawful, harmful, or abusive activity\n  text: conduct unlawful, harmful, deceptive, or abusive activity, unlawful surveillance or profiling, spam, or\n    harassment\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: To use the Service you register an account with your email address and a password, or by signing in through\n    a supported third-party provider (such as Google).\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to enter into a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/brontir-com/eligibility/brontir-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from BRONTIR's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Data Integration
- Web Research
- Public Data
- Software-as-a-Service
---
