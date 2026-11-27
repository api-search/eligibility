---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - RU
    - BY
    served: []
    text: citizens or companies of the Russian Federation, the Republic of Belarus and citizens or companies that conduct any commercial activities with citizens or companies of the Russian Federation or the Republic of Belarus are not allowed to register and use the service.
  minimum_age:
    text: in order to access and use the Service, the User must be an adult in accordance with the current applicable law. Minors can access and use the Service only under the supervision of a parent or guardian.
    value: adult
  restricted_uses:
  - summary: Illegal activity
    text: 'refrain from using the Service to commit illegal actions, including but not limited to: spam mailing, sending threats and insults, spreading false advertising, calling for violent actions'
  - summary: Sensitive third-party data
    text: you may not use the Service to download or transfer any data that is subject to increased privacy and security requirements
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: the Service automatically sends the User a link to the specified email address to activate the Account on the Site.
excluded_countries:
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ApiX-Drive
provenance_date: '2026-11-09'
provider_name: ApiX-Drive
provider_slug: apix-drive
slug: apix-drive-eligibility
source_date: '2026-11-09'
source_filename: apix-drive-eligibility.yml
source_heading: Eligibility
source_page: https://apix-drive.com/en/docs/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ApiX-Drive\naid: apix-drive\nurl: https://apix-drive.com/en/docs/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - RU\n  - BY\n  text: citizens or companies of the Russian Federation, the Republic of Belarus and citizens or companies that\n    conduct any commercial activities with citizens or companies of the Russian Federation or the Republic of Belarus\n    are not allowed to register and use the service.\nentity_types: []\nrestricted_uses:\n- summary: Illegal activity\n  text: 'refrain from using the Service to commit illegal actions, including but not limited to: spam mailing,\
  \ sending\n    threats and insults, spreading false advertising, calling for violent actions'\n- summary: Sensitive third-party data\n  text: you may not use the Service to download or transfer any data that is subject to increased privacy and security\n    requirements\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: the Service automatically sends the User a link to the specified email address to activate the Account on\n    the Site.\nminimum_age:\n  value: adult\n  text: in order to access and use the Service, the User must be an adult in accordance with the current applicable\n    law. Minors can access and use the Service only under the supervision of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/apix-drive/eligibility/apix-drive-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from ApiX-Drive's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Integration
- No-Code
- Automation
- Marketing
---
