---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Advertiser represents and warrants that it is not located in, under the control of, or a national or resident of any country to which the United States has embargoed goods or services
  entity_types:
  - text: This Agreement is between you, as an individual or the entity you represent
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Objectionable Content
    text: Advertiser represents and warrants that the Creative does not contain any Objectionable Content.
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
name: Jampp
provenance_date: '2026-11-09'
provider_name: Jampp
provider_slug: jampp
slug: jampp-eligibility
source_date: '2026-11-09'
source_filename: jampp-eligibility.yml
source_heading: Eligibility
source_page: https://www.jampp.com/advertisers-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jampp\naid: jampp\nurl: https://www.jampp.com/advertisers-terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Advertiser represents and warrants that it is not located in, under the control of, or a national or resident\n    of any country to which the United States has embargoed goods or services\nentity_types:\n- type: business\n  text: This Agreement is between you, as an individual or the entity you represent\nrestricted_uses:\n- summary: Objectionable Content\n  text: Advertiser represents and warrants that the Creative does not contain any\
  \ Objectionable Content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jampp/eligibility/jampp-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Jampp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- Marketing
- Mobile
- Analytics
- Reporting
- GraphQL
- DSP
- App Marketing
- Attribution
---
