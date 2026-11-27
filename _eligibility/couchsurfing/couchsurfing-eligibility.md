---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to access or use the Services.
    type: individual
  - text: If you are using the Services on behalf of any entity, you represent and warrant that you are authorized to accept these Terms on such entity’s behalf
    type: business
  minimum_age:
    text: You must be at least 18 years old to access or use the Services.
    value: '18'
  restricted_uses:
  - summary: No commercial use without consent
    text: use our Services for any commercial purpose whatsoever, unless with prior written consent from Couchsurfing
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: We cannot and do not confirm each member’s identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Couchsurfing
provenance_date: '2026-11-09'
provider_name: Couchsurfing
provider_slug: couchsurfing
slug: couchsurfing-eligibility
source_date: '2026-11-09'
source_filename: couchsurfing-eligibility.yml
source_heading: Eligibility
source_page: https://support.couchsurfing.org/hc/en-us/articles/360003344313-Terms-of-Use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Couchsurfing\naid: couchsurfing\nurl: https://support.couchsurfing.org/hc/en-us/articles/360003344313-Terms-of-Use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to access or use the Services.\n- type: business\n  text: If you are using the Services on behalf of any entity, you represent and warrant that you are authorized\n    to accept these Terms on such entity’s behalf\nrestricted_uses:\n- summary: No commercial use without consent\n  text: use our Services for any commercial purpose whatsoever,\
  \ unless with prior written consent from Couchsurfing\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: We cannot and do not confirm each member’s identity.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to access or use the Services.\n"
source_yaml_url: https://artifacts.apis.io/couchsurfing/eligibility/couchsurfing-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Couchsurfing's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Hospitality
- Community
- Social
- Accommodation
- Marketplace
---
