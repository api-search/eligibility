---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: if the User is acting as an authorized representative of a legal entity, then that legal entity
    type: business
  minimum_age:
    text: The Website is not intended or authorized for use by persons under the age of eighteen (18).
    value: '18'
  restricted_uses:
  - summary: Export and embargo restrictions
    text: User shall not provide access or use of the Website to any third party located in any country which has been embargoed
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
name: Tune
provenance_date: '2026-11-10'
provider_name: Tune
provider_slug: tune
slug: tune-eligibility
source_date: '2026-11-10'
source_filename: tune-eligibility.yml
source_heading: Eligibility
source_page: https://www.tune.com/resources/data-and-privacy/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tune\naid: tune\nurl: https://www.tune.com/resources/data-and-privacy/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website is not intended for distribution to or use by any person or entity in any jurisdiction or country\n    where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: if the User is acting as an authorized representative of a legal entity, then that legal entity\nrestricted_uses:\n- summary: Export and embargo restrictions\n  text: User shall not provide access or use of the Website to any third\
  \ party located in any country which has\n    been embargoed\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website is not intended or authorized for use by persons under the age of eighteen (18).\n"
source_yaml_url: https://artifacts.apis.io/tune/eligibility/tune-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Tune's own page on 2026-11-10.
synthetic: false
tags:
- Marketing
- Affiliates
- Software-as-a-Service
- Advertising
- Partnerships
---
