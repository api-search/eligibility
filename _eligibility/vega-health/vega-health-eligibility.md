---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is operated in the United States, and is primarily intended for users located in the United States. Vega Health makes no representation that the Service is appropriate or available for use beyond the United States.
  entity_types:
  - text: If you are accessing and using the Service on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: The Service is offered and available to users who are at least eighteen (18) years of age and can form a legally binding contract under applicable law.
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: Vega Health grants you a limited, non-exclusive, revocable, non-assignable, personal, and non-transferable license to download, display, view, use, or play such Content for your personal, non-commercial use only.
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
name: Vega Health
provenance_date: '2026-11-10'
provider_name: Vega Health
provider_slug: vega-health
slug: vega-health-eligibility
source_date: '2026-11-10'
source_filename: vega-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.vegahealth.com/policies/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vega Health\naid: vega-health\nurl: https://www.vegahealth.com/policies/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is operated in the United States, and is primarily intended for users located in the United\n    States. Vega Health makes no representation that the Service is appropriate or available for use beyond the\n    United States.\nentity_types:\n- type: business\n  text: If you are accessing and using the Service on behalf of a company or other legal entity, you represent and\n    warrant that you have the authority to bind that entity\
  \ to these Terms.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: Vega Health grants you a limited, non-exclusive, revocable, non-assignable, personal, and non-transferable\n    license to download, display, view, use, or play such Content for your personal, non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is offered and available to users who are at least eighteen (18) years of age and can form a\n    legally binding contract under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/vega-health/eligibility/vega-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Vega Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Clinical AI
- AI Governance
- Marketplace
- Health Systems
---
