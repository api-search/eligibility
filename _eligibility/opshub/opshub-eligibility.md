---
api_specs:
- filename: opshub-openapi-generated.yml
  format: yaml
  label: OpsHub API
  slug: opshub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opshub/openapi/_ae-authored/opshub-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - EU
    served:
    - US
    text: THE SERVICE IS OFFERED FROM THE UNITED STATES OF AMERICA AND IS NOT CURRENTLY OFFERED TO PERSONS IN THE EUROPEAN UNION OR ITS MEMBER STATES (THE "EU"). IF YOU ARE IN THE EU, YOU MAY NOT USE THE SERVICE.
  entity_types:
  - text: If you are entering into this agreement on behalf of a company or other entity, you represent that you have the authority to, and do hereby, bind such entity to this agreement
    type: business
  minimum_age:
    text: You may not access or use the Service unless you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Competitors barred
    text: IF YOU ARE A COMPETITOR OF OPSHUB, INC., OR AN EMPLOYEE, AGENT OR OTHER REPRESENTATIVE OF SUCH A COMPETITOR, YOU MAY NOT USE THE SERVICE.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- EU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OpsHub
provenance_date: '2026-11-10'
provider_name: OpsHub
provider_slug: opshub
slug: opshub-eligibility
source_date: '2026-11-10'
source_filename: opshub-eligibility.yml
source_heading: Eligibility
source_page: https://www.opshub.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpsHub\naid: opshub\nurl: https://www.opshub.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded:\n  - EU\n  text: THE SERVICE IS OFFERED FROM THE UNITED STATES OF AMERICA AND IS NOT CURRENTLY OFFERED TO PERSONS IN THE\n    EUROPEAN UNION OR ITS MEMBER STATES (THE \"EU\"). IF YOU ARE IN THE EU, YOU MAY NOT USE THE SERVICE.\nentity_types:\n- type: business\n  text: If you are entering into this agreement on behalf of a company or other entity, you represent that you have\n    the authority to, and do hereby, bind such entity to this agreement\nrestricted_uses:\n- summary: Competitors\
  \ barred\n  text: IF YOU ARE A COMPETITOR OF OPSHUB, INC., OR AN EMPLOYEE, AGENT OR OTHER REPRESENTATIVE OF SUCH A COMPETITOR,\n    YOU MAY NOT USE THE SERVICE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not access or use the Service unless you are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/opshub/eligibility/opshub-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from OpsHub's own page on 2026-11-10.
synthetic: false
tags:
- Integration
- Migration
- ALM
- ITSM
- CRM
- DevOps
- Enterprise
---
