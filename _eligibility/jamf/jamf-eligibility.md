---
api_specs:
- filename: schema
  format: yaml
  label: Jamf Pro API
  slug: jamf-pro-api
  spec_type: OpenAPI
  url: https://your-instance.jamfcloud.com/api/schema
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing use
    text: You may not use this Site in a way that infringes on the rights of Jamf or any third party or interferes with the operation of this Site.
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
name: JAMF
provenance_date: '2026-11-09'
provider_name: JAMF
provider_slug: jamf
slug: jamf-eligibility
source_date: '2026-11-09'
source_filename: jamf-eligibility.yml
source_heading: Eligibility
source_page: https://www.jamf.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JAMF\naid: jamf\nurl: https://www.jamf.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or infringing use\n  text: You may not use this Site in a way that infringes on the rights of Jamf or any third party or interferes\n    with the operation of this Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jamf/eligibility/jamf-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from JAMF's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Apple Device Management
- MDM
- Endpoint Security
- Mobile Device Management
- IT Operations
- Identity
- Compliance
- Developer Tools
- Enterprise
---
