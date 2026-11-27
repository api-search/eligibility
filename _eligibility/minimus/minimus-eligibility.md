---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not access or use the Website if you are located in, organized under the laws of, or ordinarily resident in any country or territory subject to comprehensive US sancLons
  entity_types:
  - text: If you are using the Website on behalf of a company
    type: business
  minimum_age:
    text: The Website is only intended for individuals aged thirteen (13) years or older
    value: '13'
  restricted_uses:
  - summary: Export and sanctions compliance for CE Images
    text: you will not access, download, use, export, re-export, or transfer any CE Image in violaLon of such laws
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
name: Minimus
provenance_date: '2026-11-10'
provider_name: Minimus
provider_slug: minimus
slug: minimus-eligibility
source_date: '2026-11-10'
source_filename: minimus-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.prod.website-files.com/67f93369f15385dea5315c58/6a4d2b80e927baf0df8db085_Minimus_-_Website_Terms_of_Use_June_2026.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Minimus\naid: minimus\nurl: https://cdn.prod.website-files.com/67f93369f15385dea5315c58/6a4d2b80e927baf0df8db085_Minimus_-_Website_Terms_of_Use_June_2026.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not access or use the Website if you are located in, organized under the laws of, or ordinarily\n    resident in any country or territory subject to comprehensive US sancLons\nentity_types:\n- type: business\n  text: If you are using the Website on behalf of a company\nrestricted_uses:\n- summary: Export and sanctions compliance for CE Images\n  text: you will not access,\
  \ download, use, export, re-export, or transfer any CE Image in violaLon of such laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Website is only intended for individuals aged thirteen (13) years or older\n"
source_yaml_url: https://artifacts.apis.io/minimus/eligibility/minimus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Minimus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Container Images
- Container Security
- Supply Chain Security
- DevSecOps
- Compliance
- CLI
- Hardened Images
---
