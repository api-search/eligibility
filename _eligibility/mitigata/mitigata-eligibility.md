---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The availability, scope, pricing, and eligibility for any service may vary depending on geography, customer type, underwriting requirements, technical feasibility, applicable law, and partner availability.
  entity_types:
  - text: You may use Mitigata only if you are legally capable of entering into a binding contract under applicable law.
    type: individual
  - text: If you are using the services on behalf of a company, employer, or other legal entity, you represent and warrant that you are authorised to bind that entity to these Terms
    type: business
  minimum_age:
    text: You may use Mitigata only if you are legally capable of entering into a binding contract under applicable law.
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: You agree to use the services only for lawful purposes and in accordance with these Terms.
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
name: Mitigata
provenance_date: '2026-11-10'
provider_name: Mitigata
provider_slug: mitigata
slug: mitigata-eligibility
source_date: '2026-11-10'
source_filename: mitigata-eligibility.yml
source_heading: Eligibility
source_page: https://mitigata.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mitigata\naid: mitigata\nurl: https://mitigata.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The availability, scope, pricing, and eligibility for any service may vary depending on geography, customer\n    type, underwriting requirements, technical feasibility, applicable law, and partner availability.\nentity_types:\n- type: individual\n  text: You may use Mitigata only if you are legally capable of entering into a binding contract under applicable\n    law.\n- type: business\n  text: If you are using the services on behalf of a company, employer, or other legal entity,\
  \ you represent and\n    warrant that you are authorised to bind that entity to these Terms\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You agree to use the services only for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You may use Mitigata only if you are legally capable of entering into a binding contract under applicable\n    law.\n"
source_yaml_url: https://artifacts.apis.io/mitigata/eligibility/mitigata-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Mitigata's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cybersecurity
- Cyber Insurance
- Compliance
- Security Operations
- Managed Security
- Insurance
- India
---
