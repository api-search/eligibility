---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: These Terms are applicable to users located in the United States only. If you are located outside of the United States, you will be presented with a different set of terms.
  entity_types:
  - text: To use the Service, you must be, and represent and warrant that you are, at least 13 years of age and competent to agree to these Terms.
    type: individual
  minimum_age:
    text: at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: No personal information of minors or sensitive personal data
    text: contains any personal information of minors; contains any sensitive personal information, such as financial information, payment card numbers, social security numbers, or health information without First Resonance’s prior written consent granted as part of a Customer Agreement
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
name: First Resonance
provenance_date: '2026-11-09'
provider_name: First Resonance
provider_slug: first-resonance
slug: first-resonance-eligibility
source_date: '2026-11-09'
source_filename: first-resonance-eligibility.yml
source_heading: Eligibility
source_page: https://www.firstresonance.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: First Resonance\naid: first-resonance\nurl: https://www.firstresonance.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: These Terms are applicable to users located in the United States only. If you are located outside of the\n    United States, you will be presented with a different set of terms.\nentity_types:\n- type: individual\n  text: To use the Service, you must be, and represent and warrant that you are, at least 13 years of age and competent\n    to agree to these Terms.\nrestricted_uses:\n- summary: No personal information of minors or sensitive personal data\n\
  \  text: contains any personal information of minors; contains any sensitive personal information, such as financial\n    information, payment card numbers, social security numbers, or health information without First Resonance’s\n    prior written consent granted as part of a Customer Agreement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/first-resonance/eligibility/first-resonance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from First Resonance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Infrastructure
- Manufacturing
- MES
- Factory Operating System
- Hardware
- Aerospace
- GraphQL
- Traceability
- Supply Chain
---
