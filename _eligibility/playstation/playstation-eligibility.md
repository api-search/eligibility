---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Some PlayStation Services and Content may not be available or supported in your country or language.
  entity_types:
  - text: To accept these Terms, you represent that you are at least 18 years of age and have reached the legal age of majority in the country in which your account is registered.
    type: individual
  minimum_age:
    text: you represent that you are at least 18 years of age and have reached the legal age of majority in the country in which your account is registered.
    value: '18'
  restricted_uses:
  - summary: Virtual Items obtained outside game or store
    text: Any attempt to obtain Virtual Items outside of the applicable game, the app, or PlayStation Store is prohibited.
  - summary: Resellers prohibited from Store purchases
    text: You must be an end user to purchase from PlayStation Store. Resellers, as determined by us in our sole discretion, are prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may request identifying documentation or information from you as part of your Account creation (or at any time thereafter)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PlayStation
provenance_date: '2026-11-10'
provider_name: PlayStation
provider_slug: playstation
slug: playstation-eligibility
source_date: '2026-11-10'
source_filename: playstation-eligibility.yml
source_heading: Eligibility
source_page: https://www.playstation.com/en-us/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PlayStation\naid: playstation\nurl: https://www.playstation.com/en-us/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Some PlayStation Services and Content may not be available or supported in your country or language.\nentity_types:\n- type: individual\n  text: To accept these Terms, you represent that you are at least 18 years of age and have reached the legal age\n    of majority in the country in which your account is registered.\nrestricted_uses:\n- summary: Virtual Items obtained outside game or store\n  text: Any attempt to obtain\
  \ Virtual Items outside of the applicable game, the app, or PlayStation Store is prohibited.\n- summary: Resellers prohibited from Store purchases\n  text: You must be an end user to purchase from PlayStation Store. Resellers, as determined by us in our sole discretion,\n    are prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may request identifying documentation or information from you as part of your Account creation (or at\n    any time thereafter)\nminimum_age:\n  value: '18'\n  text: you represent that you are at least 18 years of age and have reached the legal age of majority in the country\n    in which your account is registered.\n"
source_yaml_url: https://artifacts.apis.io/playstation/eligibility/playstation-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from PlayStation's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Entertainment
- Console
- DigitalMarketplace
---
