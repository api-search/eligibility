---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: access to the Site from territories where the content of the Site may be illegal is prohibited.
  entity_types:
  - text: the words “you” and “your” refer to the user visiting the Site and your company or organization.
    type: business
  minimum_age:
    text: By accessing or using the Site in any manner, you affirm that you are at least 13 years old
    value: '13'
  restricted_uses:
  - summary: No emergency medical use
    text: DO NOT USE THE CONTENT OF THE SITE FOR EMERGENCY MEDICAL NEEDS.
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
name: Ollin Bio
provenance_date: '2026-11-10'
provider_name: Ollin Bio
provider_slug: ollin-bio
slug: ollin-bio-eligibility
source_date: '2026-11-10'
source_filename: ollin-bio-eligibility.yml
source_heading: Eligibility
source_page: https://ollin.bio/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ollin Bio\naid: ollin-bio\nurl: https://ollin.bio/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: access to the Site from territories where the content of the Site may be illegal is prohibited.\nentity_types:\n- type: business\n  text: the words “you” and “your” refer to the user visiting the Site and your company or organization.\nrestricted_uses:\n- summary: No emergency medical use\n  text: DO NOT USE THE CONTENT OF THE SITE FOR EMERGENCY MEDICAL NEEDS.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n\
  \  text: By accessing or using the Site in any manner, you affirm that you are at least 13 years old\n"
source_yaml_url: https://artifacts.apis.io/ollin-bio/eligibility/ollin-bio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ollin Bio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biotechnology
- Therapeutics
- Life Sciences
- Drug Development
- Pharmaceuticals
- a16z Portfolio
---
