---
claim_count: 2
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
  - summary: Unlawful or abusive submissions
    text: Submit, post or transmit any defamatory, abusive, obscene, threatening or illegal material or information
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To obtain access to certain services on our website, you may be required to register. As part of any such registration process, you will select a user name and a password.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Datacore
provenance_date: '2026-11-09'
provider_name: Datacore
provider_slug: datacore
slug: datacore-eligibility
source_date: '2026-11-09'
source_filename: datacore-eligibility.yml
source_heading: Eligibility
source_page: https://www.datacore.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Datacore\naid: datacore\nurl: https://www.datacore.com/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or abusive submissions\n  text: Submit, post or transmit any defamatory, abusive, obscene, threatening or illegal material or information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To obtain access to certain services on our website, you may be required to register. As part of any such\n    registration process, you will select a user name and a password.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/datacore/eligibility/datacore-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Datacore's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Storage
- Software-Defined Storage
- Object Storage
- Data Management
- Kubernetes
- Hyperconverged Infrastructure
- HPC
---
