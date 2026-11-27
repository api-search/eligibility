---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.
  entity_types:
  - text: These Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: you are not a minor in the jurisdiction in which you reside, or if a minor, you have received parental permission to use the Site
    value: null
  restricted_uses:
  - summary: Industry-regulated interactions
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Site.
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
name: Central Payments
provenance_date: '2026-11-09'
provider_name: Central Payments
provider_slug: central-payments
slug: central-payments-eligibility
source_date: '2026-11-09'
source_filename: central-payments-eligibility.yml
source_heading: Eligibility
source_page: https://central-payments.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Central Payments\naid: central-payments\nurl: https://central-payments.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Site is not intended for distribution to or use by any person or\n    entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.\nentity_types:\n- type: business\n  text: These Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: Industry-regulated interactions\n\
  \  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not a minor in the jurisdiction in which you reside, or if a minor, you have received parental permission\n    to use the Site\n"
source_yaml_url: https://artifacts.apis.io/central-payments/eligibility/central-payments-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Central Payments's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Embedded Finance
---
