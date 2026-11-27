---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You or your employer or client or an entity that you represent and have full authority to enter into an agreement on its behalf
    type: business
  minimum_age:
    text: you represent and warrant that you are of legal age to enter into a binding agreement and use our services.
    value: null
  restricted_uses:
  - summary: Spamming, copyright violation, illegal activity
    text: You agree not to use the services for spamming or in violation of any party's copyrights or for any illegal activities.
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
name: KloudConnectors
provenance_date: '2026-11-09'
provider_name: KloudConnectors
provider_slug: kloudconnectors
slug: kloudconnectors-eligibility
source_date: '2026-11-09'
source_filename: kloudconnectors-eligibility.yml
source_heading: Eligibility
source_page: https://www.kloudconnectors.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KloudConnectors\naid: kloudconnectors\nurl: https://www.kloudconnectors.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You or your employer or client or an entity that you represent and have full authority to enter into an\n    agreement on its behalf\nrestricted_uses:\n- summary: Spamming, copyright violation, illegal activity\n  text: You agree not to use the services for spamming or in violation of any party's copyrights or for any illegal\n    activities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: you represent and warrant that you are of legal age to enter into a binding agreement and use our services.\n"
source_yaml_url: https://artifacts.apis.io/kloudconnectors/eligibility/kloudconnectors-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from KloudConnectors's own page on 2026-11-09.
synthetic: false
tags:
- Integration
- Automation
- Cloud
- Enterprise
- Software-as-a-Service
- Company
---
