---
api_specs:
- filename: nuki-openapi-generated.yml
  format: yaml
  label: Nuki API
  slug: nuki-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nuki/openapi/_ae-authored/nuki-openapi-generated.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: (b) you are a person barred from using or receiving the APIs under the applicable laws of Austria or other countries including the country in which you are resident or from which you use the APIs.
  entity_types:
  - text: you are not of legal age to form a binding contract with NUKI
    type: individual
  - text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind that entity to the Terms
    type: business
  minimum_age:
    text: you are not of legal age to form a binding contract with NUKI
    value: null
  restricted_uses:
  - summary: Life-critical or safety-critical use
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
  - summary: Unlawful gambling or disruptive advertising
    text: Promote or facilitate unlawful online gambling or disruptive commercial messages or advertisements.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to access certain APIs you may be required to provide certain information (such as identification or contact details) as part of the registration process
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nuki
provenance_date: '2026-11-10'
provider_name: Nuki
provider_slug: nuki
slug: nuki-eligibility
source_date: '2026-11-10'
source_filename: nuki-eligibility.yml
source_heading: Eligibility
source_page: https://nuki.io/en/legal/terms-of-use-nuki-apis
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nuki\naid: nuki\nurl: https://nuki.io/en/legal/terms-of-use-nuki-apis\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: (b) you are a person barred from using or receiving the APIs under the applicable laws of Austria or other\n    countries including the country in which you are resident or from which you use the APIs.\nentity_types:\n- type: individual\n  text: you are not of legal age to form a binding contract with NUKI\n- type: business\n  text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind\n    that entity to the Terms\n\
  restricted_uses:\n- summary: Life-critical or safety-critical use\n  text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\n- summary: Unlawful gambling or disruptive advertising\n  text: Promote or facilitate unlawful online gambling or disruptive commercial messages or advertisements.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to access certain APIs you may be required to provide certain information (such as identification\n    or contact details) as part of the registration process\nminimum_age:\n  value: null\n  text: you are not of legal age to form a binding contract with NUKI\n"
source_yaml_url: https://artifacts.apis.io/nuki/eligibility/nuki-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Nuki's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Smart Lock
- IoT
- Home Automation
- Security
---
