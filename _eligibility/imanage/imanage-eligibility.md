---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By accessing or using the Services, you confirm that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Embargoed regions and sanctioned parties
    text: Use of the Services is prohibited in embargoed regions or by sanctioned individuals/entities.
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
name: iManage
provenance_date: '2026-11-09'
provider_name: iManage
provider_slug: imanage
slug: imanage-eligibility
source_date: '2026-11-09'
source_filename: imanage-eligibility.yml
source_heading: Eligibility
source_page: https://imanage.com/about/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iManage\naid: imanage\nurl: https://imanage.com/about/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Embargoed regions and sanctioned parties\n  text: Use of the Services is prohibited in embargoed regions or by sanctioned individuals/entities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By accessing or using the Services, you confirm that you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/imanage/eligibility/imanage-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from iManage's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Knowledge Work
- Legal Tech
- Professional Services
---
