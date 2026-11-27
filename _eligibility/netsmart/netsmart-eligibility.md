---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of the Netsmart APIs is not authorized in any jurisdiction that does not give effect to all the provisions of this Agreement.
  entity_types:
  - text: you (or the company, organization or other legal entity that you represent)
    type: business
  - source: https://careconnect.netsmartcloud.com/terms-of-service/index.html
    text: you (or the company, organization or other legal entity that you represent) ("Developer", or "you", or "your")
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No protected health information submitted
    text: Developer shall not submit or make available to Netsmart any Protected Health Information
  - source: https://careconnect.netsmartcloud.com/terms-of-service/index.html
    summary: No PHI submission
    text: Developer shall not submit or make available to Netsmart any Protected Health Information
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
name: Netsmart
provenance_date: '2026-11-10'
provider_name: Netsmart
provider_slug: netsmart
slug: netsmart-eligibility
source_date: '2026-11-10'
source_filename: netsmart-eligibility.yml
source_heading: Eligibility
source_page: https://oauthtest.netsmartcloud.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Netsmart\naid: netsmart\nurl: https://oauthtest.netsmartcloud.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://careconnect.netsmartcloud.com/terms-of-service/index.html\n  - https://oauthtest.netsmartcloud.com/terms\ncountries:\n  served: []\n  excluded: []\n  text: Use of the Netsmart APIs is not authorized in any jurisdiction that does not give effect to all the provisions\n    of this Agreement.\nentity_types:\n- type: business\n  text: you (or the company, organization or other legal entity that you represent)\n- type: developer\n  text: you (or the company, organization or other legal entity\
  \ that you represent) (\"Developer\", or \"you\", or \"your\")\n  source: https://careconnect.netsmartcloud.com/terms-of-service/index.html\nrestricted_uses:\n- summary: No protected health information submitted\n  text: Developer shall not submit or make available to Netsmart any Protected Health Information\n- summary: No PHI submission\n  text: Developer shall not submit or make available to Netsmart any Protected Health Information\n  source: https://careconnect.netsmartcloud.com/terms-of-service/index.html\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/netsmart/eligibility/netsmart-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Netsmart's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare IT
- Electronic Health Records
- FHIR
- Behavioral Health
- Post-Acute Care
- Human Services
- Interoperability
- HL7
- Care Coordination
- Mental Health
---
