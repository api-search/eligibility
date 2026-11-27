---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website is available in several countries and customers can enter into purchase agreements in several languages. For updated information about available countries and languages, please see the country selector on the Website.
  entity_types:
  - text: The Website is provided for private use and are not intended to be used to purchase products for re-sale or export for companies.
    type: individual
  minimum_age:
    text: To use the Website, you must be 18 years of age or older. If you are under the age of 18 but at least 13 years of age, you may use this Website only under the supervision of a parent or legal guardian
    value: '18'
  restricted_uses:
  - summary: No purchases for resale or export by companies
    text: The Website is provided for private use and are not intended to be used to purchase products for re-sale or export for companies.
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
name: Marshall
provenance_date: '2026-11-10'
provider_name: Marshall
provider_slug: marshall
slug: marshall-eligibility
source_date: '2026-11-10'
source_filename: marshall-eligibility.yml
source_heading: Eligibility
source_page: https://www.marshall.com/us/en/policies/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Marshall\naid: marshall\nurl: https://www.marshall.com/us/en/policies/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website is available in several countries and customers can enter into purchase agreements in several\n    languages. For updated information about available countries and languages, please see the country selector\n    on the Website.\nentity_types:\n- type: individual\n  text: The Website is provided for private use and are not intended to be used to purchase products for re-sale\n    or export for companies.\nrestricted_uses:\n- summary: No purchases\
  \ for resale or export by companies\n  text: The Website is provided for private use and are not intended to be used to purchase products for re-sale\n    or export for companies.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To use the Website, you must be 18 years of age or older. If you are under the age of 18 but at least 13\n    years of age, you may use this Website only under the supervision of a parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/marshall/eligibility/marshall-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Marshall's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Audio
- Consumer Electronics
- Headphones
- Speakers
- Amplifiers
- Music
---
