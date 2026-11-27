---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Spam, malware and destructive code
    text: Authorized Users agree that they will not knowingly use the Service to upload, post, host, or transmit unsolicited bulk email “Spam”
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
name: CollBox
provenance_date: '2026-11-09'
provider_name: CollBox
provider_slug: collbox
slug: collbox-eligibility
source_date: '2026-11-09'
source_filename: collbox-eligibility.yml
source_heading: Eligibility
source_page: https://collbox.co/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CollBox\naid: collbox\nurl: https://collbox.co/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such entity\nrestricted_uses:\n- summary: Spam, malware and destructive code\n  text: Authorized Users agree that they will not knowingly use the Service to upload, post, host, or transmit unsolicited\n    bulk email “Spam”\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/collbox/eligibility/collbox-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CollBox's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Law
- Finance
- Software-as-a-Service
- Invoicing
---
