---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled, operated and administered by Layer5 from our offices within the USA. If you access the Service from a location outside the USA, you are responsible for compliance with all local laws.
  minimum_age:
    text: Layer5 does not knowingly collect, either online or offline, personal information from persons under the age of eighteen. If you are under 18, you may use cloud.layer5.io only with permission of a parent or guardian.
    value: '18'
  restricted_uses:
  - summary: Unlawful use in any jurisdiction
    text: You agree that you will not use the Layer5 Content accessed through cloud.layer5.io in any country or in any manner prohibited by any applicable laws, restrictions or regulations.
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
name: Meshery
provenance_date: '2026-11-10'
provider_name: Meshery
provider_slug: meshery
slug: meshery-eligibility
source_date: '2026-11-10'
source_filename: meshery-eligibility.yml
source_heading: Eligibility
source_page: https://layer5.io/company/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meshery\naid: meshery\nurl: https://layer5.io/company/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled, operated and administered by Layer5 from our offices within the USA. If you access\n    the Service from a location outside the USA, you are responsible for compliance with all local laws.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use in any jurisdiction\n  text: You agree that you will not use the Layer5 Content accessed through cloud.layer5.io in any country or in\n    any manner prohibited by any applicable laws,\
  \ restrictions or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Layer5 does not knowingly collect, either online or offline, personal information from persons under the\n    age of eighteen. If you are under 18, you may use cloud.layer5.io only with permission of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/meshery/eligibility/meshery-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Meshery's own page on 2026-11-10.
synthetic: false
tags:
- Cloud-Native
- CNCF
- Kubernetes
- Service Mesh
- Platform Engineering
- Multi-Cluster
---
