---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a company, sole trader, self-employed professional, association or public body that uses it for its business
    type: business
  - text: association
    type: nonprofit
  - text: public body
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Professional use only
    text: It is not offered to consumers.
  - summary: No sensitive data without agreement
    text: It does not import sensitive data (health, opinions, criminal convictions and other special categories under the GDPR) without Aetherly’s written agreement.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Customer accepts them by creating its account; each subscription constitutes acceptance of the version in force on its date.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cuevr
provenance_date: '2026-11-09'
provider_name: Cuevr
provider_slug: cuevr-com
slug: cuevr-com-eligibility
source_date: '2026-11-09'
source_filename: cuevr-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.cuevr.com/cgv
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cuevr\naid: cuevr-com\nurl: https://www.cuevr.com/cgv\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: a company, sole trader, self-employed professional, association or public body that uses it for its business\n- type: nonprofit\n  text: association\n- type: government\n  text: public body\nrestricted_uses:\n- summary: Professional use only\n  text: It is not offered to consumers.\n- summary: No sensitive data without agreement\n  text: It does not import sensitive data (health, opinions, criminal convictions and other special categories\
  \ under\n    the GDPR) without Aetherly’s written agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Customer accepts them by creating its account; each subscription constitutes acceptance of the version\n    in force on its date.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cuevr-com/eligibility/cuevr-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Cuevr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sales Proposals
- E-Signature
- RFP
- Sales Enablement
- Artificial Intelligence
- MCP
- Webhook
---
