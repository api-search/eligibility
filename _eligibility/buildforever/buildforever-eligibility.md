---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of a company, organization, or other entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  - text: If you are a U.S. government entity or accessing the Services on behalf of one, the Services are provided as "commercial items" and subject only to the rights set forth in these Terms.
    type: government
  minimum_age:
    text: You must be at least 13 years old to use the Services.
    value: '13'
  restricted_uses:
  - summary: Sanctioned or legally barred users
    text: You may not use the Services if you are barred under applicable law or subject to government sanctions.
  - summary: Export restrictions
    text: You may not use or export the Services in violation of U.S. export laws and regulations.
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
name: Buildforever
provenance_date: '2026-11-09'
provider_name: Buildforever
provider_slug: buildforever
slug: buildforever-eligibility
source_date: '2026-11-09'
source_filename: buildforever-eligibility.yml
source_heading: Eligibility
source_page: https://extra.email/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buildforever\naid: buildforever\nurl: https://extra.email/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of a company, organization, or other entity, you represent and warrant\n    that you have the authority to bind that entity to these Terms.\n- type: government\n  text: If you are a U.S. government entity or accessing the Services on behalf of one, the Services are provided\n    as \"commercial items\" and subject only to the rights set forth in these Terms.\nrestricted_uses:\n- summary:\
  \ Sanctioned or legally barred users\n  text: You may not use the Services if you are barred under applicable law or subject to government sanctions.\n- summary: Export restrictions\n  text: You may not use or export the Services in violation of U.S. export laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/buildforever/eligibility/buildforever-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Buildforever's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Email
- Consumer
- Productivity
- Gmail
- iOS
---
