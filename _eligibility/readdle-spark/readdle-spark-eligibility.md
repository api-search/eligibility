---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - RU
    - BY
    served: []
    text: We do not provide services or access to our products to customers from the Russian Federation and the Republic of Belarus.
  entity_types:
  - text: To use the service, you must be at least 16 years of age.
    type: individual
  - text: If you represent a company or other legal entity and wish to obtain access to the App and/ or purchase several subscriptions for your organisation's authorised users (“ Authorised Users ”), the organization you represent will become our customer (“ Business Customer ”).
    type: business
  minimum_age:
    text: To use the service, you must be at least 16 years of age.
    value: '16'
  restricted_uses:
  - summary: Sanctions and export control compliance
    text: You may not use, access, or export our services in violation of applicable international sanctions and export control laws, including but not limited to those of the United States and the European Union.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Spark Mail (Readdle)
provenance_date: '2026-11-10'
provider_name: Spark Mail (Readdle)
provider_slug: readdle-spark
slug: readdle-spark-eligibility
source_date: '2026-11-10'
source_filename: readdle-spark-eligibility.yml
source_heading: Eligibility
source_page: https://sparkmailapp.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spark Mail (Readdle)\naid: readdle-spark\nurl: https://sparkmailapp.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - RU\n  - BY\n  text: We do not provide services or access to our products to customers from the Russian Federation and the Republic\n    of Belarus.\nentity_types:\n- type: individual\n  text: To use the service, you must be at least 16 years of age.\n- type: business\n  text: If you represent a company or other legal entity and wish to obtain access to the App and/ or purchase several\n    subscriptions for your organisation's authorised users (“ Authorised\
  \ Users ”), the organization you represent\n    will become our customer (“ Business Customer ”).\nrestricted_uses:\n- summary: Sanctions and export control compliance\n  text: You may not use, access, or export our services in violation of applicable international sanctions and export\n    control laws, including but not limited to those of the United States and the European Union.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: To use the service, you must be at least 16 years of age.\n"
source_yaml_url: https://artifacts.apis.io/readdle-spark/eligibility/readdle-spark-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Spark Mail (Readdle)'s own page on 2026-11-10.
synthetic: false
tags:
- Email
- Productivity
- iOS
- macOS
- Android
---
