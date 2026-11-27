---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the signatory to this Agreement is entering into this Agreement on behalf of a company or other legal entity, such signatory represents that he/she/it has the authority to bind such entity to this Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Direct competitors barred
    text: not use the Services if, in DemandScience’ reasonable determination, Customer is or becomes a direct competitor of DemandScience
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
name: Terminus
provenance_date: '2026-11-10'
provider_name: Terminus
provider_slug: terminus
slug: terminus-eligibility
source_date: '2026-11-10'
source_filename: terminus-eligibility.yml
source_heading: Eligibility
source_page: https://demandscience.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Terminus\naid: terminus\nurl: https://demandscience.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If the signatory to this Agreement is entering into this Agreement on behalf of a company or other legal\n    entity, such signatory represents that he/she/it has the authority to bind such entity to this Agreement.\nrestricted_uses:\n- summary: Direct competitors barred\n  text: not use the Services if, in DemandScience’ reasonable determination, Customer is or becomes a direct competitor\n    of DemandScience\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/terminus/eligibility/terminus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Terminus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Account Based Marketing
- Marketing
- Advertising
- Sales
- B2B
- Analytics
- Email
- Email Verification
- Data Quality
---
