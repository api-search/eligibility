---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: To use the Services, You must be at least 18 years old, a U.S. resident, and legally capable of entering into a contract.
  entity_types:
  - text: Individuals who access the Platform directly (and not solely through a Subscribing Customer) to obtain remote online notarization
    type: individual
  - text: Subscribing Customers subscribe to the applicable Services through separately negotiated agreements
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: RON only in commissioned-state cases
    text: RON Services are available only where the notarial act is performed by a notary commissioned in a U.S. state that authorizes remote online notarization
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You authorize Snapdocs, directly or through third parties, to make any inquiries we consider necessary to verify Your identity or prevent fraud.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Snapdocs
provenance_date: '2026-11-10'
provider_name: Snapdocs
provider_slug: snapdocs
slug: snapdocs-eligibility
source_date: '2026-11-10'
source_filename: snapdocs-eligibility.yml
source_heading: Eligibility
source_page: https://www.snapdocs.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Snapdocs\naid: snapdocs\nurl: https://www.snapdocs.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: To use the Services, You must be at least 18 years old, a U.S. resident, and legally capable of entering\n    into a contract.\nentity_types:\n- type: individual\n  text: Individuals who access the Platform directly (and not solely through a Subscribing Customer) to obtain remote\n    online notarization\n- type: business\n  text: Subscribing Customers subscribe to the applicable Services through separately negotiated agreements\nrestricted_uses:\n- summary:\
  \ RON only in commissioned-state cases\n  text: RON Services are available only where the notarial act is performed by a notary commissioned in a U.S. state\n    that authorizes remote online notarization\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You authorize Snapdocs, directly or through third parties, to make any inquiries we consider necessary to\n    verify Your identity or prevent fraud.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/snapdocs/eligibility/snapdocs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Snapdocs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PropTech
- Mortgage
- Real Estate
- Fintech
- eClosing
- Title and Settlement
- Notary
---
