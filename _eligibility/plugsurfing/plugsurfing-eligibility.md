---
api_specs:
- filename: plugsurfing-charging-key-orders-api-openapi.yml
  format: yaml
  label: Plugsurfing Charging Key Orders API
  slug: plugsurfing-charging-key-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plugsurfing/openapi/plugsurfing-charging-key-orders-api-openapi.yml
- filename: plugsurfing-charging-keys-api-openapi.yml
  format: yaml
  label: Plugsurfing Charging Keys API
  slug: plugsurfing-charging-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plugsurfing/openapi/plugsurfing-charging-keys-api-openapi.yml
- filename: plugsurfing-drive-api-api-openapi.yml
  format: yaml
  label: Plugsurfing Drive API
  slug: plugsurfing-drive-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plugsurfing/openapi/plugsurfing-drive-api-api-openapi.yml
- filename: plugsurfing-emp-charging-keys-api-openapi.yml
  format: yaml
  label: Plugsurfing EMP Charging Keys API
  slug: plugsurfing-emp-charging-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plugsurfing/openapi/plugsurfing-emp-charging-keys-api-openapi.yml
- filename: plugsurfing-emp-fleets-api-openapi.yml
  format: yaml
  label: Plugsurfing EMP Fleets API
  slug: plugsurfing-emp-fleets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plugsurfing/openapi/plugsurfing-emp-fleets-api-openapi.yml
- filename: plugsurfing-emp-geosearch-api-openapi.yml
  format: yaml
  label: Plugsurfing EMP Geosearch API
  slug: plugsurfing-emp-geosearch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plugsurfing/openapi/plugsurfing-emp-geosearch-api-openapi.yml
- filename: plugsurfing-emp-orders-api-openapi.yml
  format: yaml
  label: Plugsurfing EMP Orders API
  slug: plugsurfing-emp-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plugsurfing/openapi/plugsurfing-emp-orders-api-openapi.yml
- filename: plugsurfing-emp-sessions-api-openapi.yml
  format: yaml
  label: Plugsurfing EMP Sessions API
  slug: plugsurfing-emp-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plugsurfing/openapi/plugsurfing-emp-sessions-api-openapi.yml
- filename: plugsurfing-geosearch-api-openapi.yml
  format: yaml
  label: Plugsurfing Geosearch API
  slug: plugsurfing-geosearch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plugsurfing/openapi/plugsurfing-geosearch-api-openapi.yml
- filename: plugsurfing-payment-options-api-openapi.yml
  format: yaml
  label: Plugsurfing Payment Options API
  slug: plugsurfing-payment-options-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plugsurfing/openapi/plugsurfing-payment-options-api-openapi.yml
- filename: plugsurfing-remote-charging-api-openapi.yml
  format: yaml
  label: Plugsurfing Remote Charging API
  slug: plugsurfing-remote-charging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plugsurfing/openapi/plugsurfing-remote-charging-api-openapi.yml
- filename: plugsurfing-sessions-api-openapi.yml
  format: yaml
  label: Plugsurfing Sessions API
  slug: plugsurfing-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plugsurfing/openapi/plugsurfing-sessions-api-openapi.yml
- filename: plugsurfing-user-groups-api-openapi.yml
  format: yaml
  label: Plugsurfing User Groups API
  slug: plugsurfing-user-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plugsurfing/openapi/plugsurfing-user-groups-api-openapi.yml
- filename: plugsurfing-users-api-openapi.yml
  format: yaml
  label: Plugsurfing Users API
  slug: plugsurfing-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plugsurfing/openapi/plugsurfing-users-api-openapi.yml
- filename: plugsurfing-vouchers-api-openapi.yml
  format: yaml
  label: Plugsurfing Vouchers API
  slug: plugsurfing-vouchers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plugsurfing/openapi/plugsurfing-vouchers-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer, this limitation does not apply to you.
    type: individual
  - text: If you are a businessperson and if the potential dispute with Plugsurfing is attributable to the conducting of your trade or any business activity, the courts of Berlin, Germany, are competent for any legal disputes arising from these Terms of Use.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Plugsurfing may require additional verification before restoring account access.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Plugsurfing
provenance_date: '2026-11-10'
provider_name: Plugsurfing
provider_slug: plugsurfing
slug: plugsurfing-eligibility
source_date: '2026-11-10'
source_filename: plugsurfing-eligibility.yml
source_heading: Eligibility
source_page: https://plugsurfing.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plugsurfing\naid: plugsurfing\nurl: https://plugsurfing.com/legal/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer, this limitation does not apply to you.\n- type: business\n  text: If you are a businessperson and if the potential dispute with Plugsurfing is attributable to the conducting\n    of your trade or any business activity, the courts of Berlin, Germany, are competent for any legal disputes\n    arising from these Terms of Use.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: Plugsurfing may require additional verification before restoring account access.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/plugsurfing/eligibility/plugsurfing-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from Plugsurfing's own page on 2026-11-10.
synthetic: false
tags:
- Company
- EV Charging
- Roaming
- Europe
---
