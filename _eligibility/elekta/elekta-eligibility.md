---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The site contains information about products which may or may not be available in any particular country
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Certain parts of this web-site may only be available through use of a password, provided by Elekta for certain services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Elekta
provenance_date: '2026-11-09'
provider_name: Elekta
provider_slug: elekta
slug: elekta-eligibility
source_date: '2026-11-09'
source_filename: elekta-eligibility.yml
source_heading: Eligibility
source_page: https://www.elekta.com/legal-notices/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Elekta\naid: elekta\nurl: https://www.elekta.com/legal-notices/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The site contains information about products which may or may not be available in any particular country\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Certain parts of this web-site may only be available through use of a password, provided by Elekta for certain\n    services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/elekta/eligibility/elekta-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from Elekta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Oncology
- Medical Devices
- Radiotherapy
---
