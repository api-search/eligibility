---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: on behalf of your employer or another legal entity
    type: business
  - text: YOU REPRESENT AND WARRANT THAT YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD
    type: individual
  minimum_age:
    text: YOU REPRESENT AND WARRANT THAT YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: Licensee agrees not to export or re-export the Software Product, Cloud Services and Documentation in any form without the appropriate United States and foreign governmental licenses.
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
name: Incredibuild
provenance_date: '2026-11-09'
provider_name: Incredibuild
provider_slug: incredibuild
slug: incredibuild-eligibility
source_date: '2026-11-09'
source_filename: incredibuild-eligibility.yml
source_heading: Eligibility
source_page: https://www.incredibuild.com/eula
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Incredibuild\naid: incredibuild\nurl: https://www.incredibuild.com/eula\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: on behalf of your employer or another legal entity\n- type: individual\n  text: YOU REPRESENT AND WARRANT THAT YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD\nrestricted_uses:\n- summary: Export restrictions\n  text: Licensee agrees not to export or re-export the Software Product, Cloud Services and Documentation in any\n    form without the appropriate United States and foreign governmental licenses.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU REPRESENT AND WARRANT THAT YOU ARE AT LEAST EIGHTEEN (18) YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/incredibuild/eligibility/incredibuild-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Incredibuild's own page on 2026-11-09.
synthetic: false
tags:
- Company
- DevOps
- Build Acceleration
- Continuous Integration
- Distributed Computing
- Build Cache
- Developer Tools
- CI/CD
---
