---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you can only access and use the Site for your own personal, non-commercial uses
    type: individual
  - text: If you use the Site for any commercial, business or re-sale purpose we will have no liability to you
    type: business
  minimum_age:
    text: This Site is not intended for children below 16 and you should not use the Site (and/or accept these Terms) if you are below 16.
    value: '16'
  restricted_uses:
  - summary: commercial or business use
    text: you shall not license, sell, rent, lease, transfer, assign, distribute, host, or otherwise commercially exploit the Site
  - summary: licence limits per user
    text: Licenses are limited to one per user per year, if a user leaves the company this license cannot be reused or redistributed to another user in that subscription period.
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
name: Vitrue Health
provenance_date: '2026-11-10'
provider_name: Vitrue Health
provider_slug: vitrue-health
slug: vitrue-health-eligibility
source_date: '2026-11-10'
source_filename: vitrue-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.vitruehealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vitrue Health\naid: vitrue-health\nurl: https://www.vitruehealth.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you can only access and use the Site for your own personal, non-commercial uses\n- type: business\n  text: If you use the Site for any commercial, business or re-sale purpose we will have no liability to you\nrestricted_uses:\n- summary: commercial or business use\n  text: you shall not license, sell, rent, lease, transfer, assign, distribute, host, or otherwise commercially\n    exploit the Site\n-\
  \ summary: licence limits per user\n  text: Licenses are limited to one per user per year, if a user leaves the company this license cannot be reused\n    or redistributed to another user in that subscription period.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: This Site is not intended for children below 16 and you should not use the Site (and/or accept these Terms)\n    if you are below 16.\n"
source_yaml_url: https://artifacts.apis.io/vitrue-health/eligibility/vitrue-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Vitrue Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Digital Health
- Musculoskeletal
- Ergonomics
- Workplace Wellness
- DSE Compliance
- Occupational Health
- Artificial Intelligence
---
