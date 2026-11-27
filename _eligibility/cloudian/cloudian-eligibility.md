---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: this Site is intended for use only within the U.S.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and legal compliance
    text: You may not access, download, use or export the Site, any products available through the Site, or content on the Site in violation of U.S. export laws or regulations, or in violation of any other applicable laws or regulations.
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
name: Cloudian
provenance_date: '2026-11-09'
provider_name: Cloudian
provider_slug: cloudian
slug: cloudian-eligibility
source_date: '2026-11-09'
source_filename: cloudian-eligibility.yml
source_heading: Eligibility
source_page: https://cloudian.com/disclosures/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cloudian\naid: cloudian\nurl: https://cloudian.com/disclosures/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: this Site is intended for use only within the U.S.\nentity_types: []\nrestricted_uses:\n- summary: Export and legal compliance\n  text: You may not access, download, use or export the Site, any products available through the Site, or content\n    on the Site in violation of U.S. export laws or regulations, or in violation of any other applicable laws or\n    regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cloudian/eligibility/cloudian-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Cloudian's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Storage
- Object Storage
- Artificial Intelligence
- Enterprise
---
