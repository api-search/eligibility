---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are competent and possess the legal capacity to enter into a contract, i.e. you have attained the age of majority.
    type: individual
  - text: is an agreement between Virya Logistics Technologies Private Limited ("Agraga", "we", "our", "us") and you or the entity you represent
    type: business
  minimum_age:
    text: If you are a minor, you may use the Platform only under the supervision of a guardian or parent who agrees to be bound by these terms.
    value: '18'
  restricted_uses:
  - summary: Unlawful, harassing or abusive use
    text: You expressly agree that you shall not use the Platform for any purposes that are unlawful, harassing, abusive, threatening, harmful, vulgar, obscene, or otherwise objectionable, nor solicit others to do so.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need your email, full name, phone number, country, and GST details to register on the Platform.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agraga
provenance_date: '2026-11-09'
provider_name: Agraga
provider_slug: agraga
slug: agraga-eligibility
source_date: '2026-11-09'
source_filename: agraga-eligibility.yml
source_heading: Eligibility
source_page: https://www.agraga.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agraga\naid: agraga\nurl: https://www.agraga.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are competent and possess the legal capacity to enter into a contract,\n    i.e. you have attained the age of majority.\n- type: business\n  text: is an agreement between Virya Logistics Technologies Private Limited (\"Agraga\", \"we\", \"our\", \"us\") and you\n    or the entity you represent\nrestricted_uses:\n- summary: Unlawful, harassing or abusive use\n  text: You expressly agree that\
  \ you shall not use the Platform for any purposes that are unlawful, harassing, abusive,\n    threatening, harmful, vulgar, obscene, or otherwise objectionable, nor solicit others to do so.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You need your email, full name, phone number, country, and GST details to register on the Platform.\nminimum_age:\n  value: '18'\n  text: If you are a minor, you may use the Platform only under the supervision of a guardian or parent who agrees\n    to be bound by these terms.\n"
source_yaml_url: https://artifacts.apis.io/agraga/eligibility/agraga-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Agraga's own page on 2026-11-09.
synthetic: false
tags:
- Logistics
- Freight
- Freight Forwarding
- Supply Chain
- Shipping
- Customs
- Warehousing
- Embedded Finance
- Trade
- India
- Company
---
