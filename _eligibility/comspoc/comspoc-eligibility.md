---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Neither the Services of COMSPOC nor the underlying information or technology may be downloaded or otherwise provided or made available ... to anyone on the U.S. Treasury Department's list of Specially Designated Nationals
  entity_types:
  - text: By using the Content and Services you agree to be bound by these Terms, even if you are accessing our Services on behalf of a company.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You may not access, download, use or export the Services, or the Content in violation of U.S. export laws or regulations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Some of the COMSPOC Websites and Content requires that You register or otherwise provide certain information prior to gaining access.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: COMSPOC
provenance_date: '2026-11-09'
provider_name: COMSPOC
provider_slug: comspoc
slug: comspoc-eligibility
source_date: '2026-11-09'
source_filename: comspoc-eligibility.yml
source_heading: Eligibility
source_page: https://comspoc.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: COMSPOC\naid: comspoc\nurl: https://comspoc.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Neither the Services of COMSPOC nor the underlying information or technology may be downloaded or otherwise\n    provided or made available ... to anyone on the U.S. Treasury Department's list of Specially Designated Nationals\nentity_types:\n- type: business\n  text: By using the Content and Services you agree to be bound by these Terms, even if you are accessing our Services\n    on behalf of a company.\nrestricted_uses:\n- summary: Export and sanctions restrictions\n\
  \  text: You may not access, download, use or export the Services, or the Content in violation of U.S. export laws\n    or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Some of the COMSPOC Websites and Content requires that You register or otherwise provide certain information\n    prior to gaining access.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/comspoc/eligibility/comspoc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from COMSPOC's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Space
- SSA
- Software
- Data
- Research
---
