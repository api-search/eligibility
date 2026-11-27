---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this TOS on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: you are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: No unsolicited or harvested email
    text: 'you may not use the Service to directly or indirectly send, transmit, handle, distribute or deliver: (a) unsolicited email (“spam” or “spamming”) in violation of applicable law'
  - summary: No purchased or rented email lists
    text: you agree that you will not use any purchased or rented lists or any other lists you obtained from a third party.
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
name: LocBox Labs
provenance_date: '2026-11-09'
provider_name: LocBox Labs
provider_slug: fetchrev-com
slug: fetchrev-com-eligibility
source_date: '2026-11-09'
source_filename: fetchrev-com-eligibility.yml
source_heading: Eligibility
source_page: https://fetchrev.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LocBox Labs\naid: fetchrev-com\nurl: https://fetchrev.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this TOS on behalf of a company, business or other legal entity, you represent\n    that you have the authority to bind such entity\nrestricted_uses:\n- summary: No unsolicited or harvested email\n  text: 'you may not use the Service to directly or indirectly send, transmit, handle, distribute or deliver: (a)\n    unsolicited email (“spam” or “spamming”) in violation of applicable law'\n\
  - summary: No purchased or rented email lists\n  text: you agree that you will not use any purchased or rented lists or any other lists you obtained from a third\n    party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/fetchrev-com/eligibility/fetchrev-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from LocBox Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketing
- Automation
- Local Business
- Software-as-a-Service
---
