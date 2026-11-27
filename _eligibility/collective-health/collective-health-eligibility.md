---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our websites, portals, mobile apps and digital platforms operate in the United States (U.S.) and are not targeted to individuals who reside in the European Economic Area (EEA) or other countries outside of the U.S.
  entity_types:
  - text: authorized users representing a company, its employees, or other persons in using or accessing the Services
    type: business
  minimum_age:
    text: Individuals under 13 years of age are not authorized to use the Services.
    value: '13'
  restricted_uses:
  - summary: Unauthorized commercial use
    text: Unless otherwise expressly authorized by these Terms, User agrees not to display, distribute, license, perform, publish, reproduce, duplicate, copy, create derivative works from, modify, sell, offer for sale, resell, exploit, transfer or upload for any commercial purposes
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
name: Collective Health
provenance_date: '2026-11-09'
provider_name: Collective Health
provider_slug: collective-health
slug: collective-health-eligibility
source_date: '2026-11-09'
source_filename: collective-health-eligibility.yml
source_heading: Eligibility
source_page: https://collectivehealth.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Collective Health\naid: collective-health\nurl: https://collectivehealth.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our websites, portals, mobile apps and digital platforms operate in the United States (U.S.) and are not\n    targeted to individuals who reside in the European Economic Area (EEA) or other countries outside of the U.S.\nentity_types:\n- type: business\n  text: authorized users representing a company, its employees, or other persons in using or accessing the Services\nrestricted_uses:\n- summary: Unauthorized commercial\
  \ use\n  text: Unless otherwise expressly authorized by these Terms, User agrees not to display, distribute, license, perform,\n    publish, reproduce, duplicate, copy, create derivative works from, modify, sell, offer for sale, resell, exploit,\n    transfer or upload for any commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Individuals under 13 years of age are not authorized to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/collective-health/eligibility/collective-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Collective Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Life Sciences
- Health Benefits
- Third-Party Administrator
- Health Insurance
- Healthcare
- Employee Benefits
---
