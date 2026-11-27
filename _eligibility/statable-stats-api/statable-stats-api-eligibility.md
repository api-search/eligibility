---
api_specs:
- filename: statable-stats-api-bootstrap-api-openapi.yml
  format: yaml
  label: Statable Stats API Bootstrap API
  slug: statable-stats-api-bootstrap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statable-stats-api/openapi/statable-stats-api-bootstrap-api-openapi.yml
- filename: statable-stats-api-keys-api-openapi.yml
  format: yaml
  label: Statable Stats API Keys API
  slug: statable-stats-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statable-stats-api/openapi/statable-stats-api-keys-api-openapi.yml
- filename: statable-stats-api-sites-api-openapi.yml
  format: yaml
  label: Statable Stats API Sites API
  slug: statable-stats-api-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statable-stats-api/openapi/statable-stats-api-sites-api-openapi.yml
- filename: statable-stats-api-stats-api-openapi.yml
  format: yaml
  label: Statable Stats API Stats API
  slug: statable-stats-api-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statable-stats-api/openapi/statable-stats-api-stats-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - RU
    - BY
    served: []
    text: The Services are not offered in the Russian Federation or the Republic of Belarus. You may not create an Account or use the Services if you are located or established in either country.
  entity_types:
  - text: If you accept these Terms on behalf of your employer or another legal entity, you represent and warrant that you have full authority to bind that entity
    type: business
  - text: For EU/UK consumers (natural persons acting outside their trade or profession)
    type: individual
  minimum_age:
    text: The Services are not intended for, and should not be used by, anyone under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Russia/Belarus restriction
    text: The Services are not offered in the Russian Federation or the Republic of Belarus.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: We do not independently verify the identity of Customers or Account Users beyond the authentication methods offered in the Services, and we do not monitor their activity.
excluded_countries:
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Statable Stats API
provenance_date: '2026-11-10'
provider_name: Statable Stats API
provider_slug: statable-stats-api
slug: statable-stats-api-eligibility
source_date: '2026-11-10'
source_filename: statable-stats-api-eligibility.yml
source_heading: Eligibility
source_page: https://statable.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Statable Stats API\naid: statable-stats-api\nurl: https://statable.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - RU\n  - BY\n  text: The Services are not offered in the Russian Federation or the Republic of Belarus. You may not create an\n    Account or use the Services if you are located or established in either country.\nentity_types:\n- type: business\n  text: If you accept these Terms on behalf of your employer or another legal entity, you represent and warrant\n    that you have full authority to bind that entity\n- type: individual\n  text: For EU/UK consumers (natural\
  \ persons acting outside their trade or profession)\nrestricted_uses:\n- summary: Russia/Belarus restriction\n  text: The Services are not offered in the Russian Federation or the Republic of Belarus.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: We do not independently verify the identity of Customers or Account Users beyond the authentication methods\n    offered in the Services, and we do not monitor their activity.\nminimum_age:\n  value: '18'\n  text: The Services are not intended for, and should not be used by, anyone under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/statable-stats-api/eligibility/statable-stats-api-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Statable Stats API's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Web Analytics
- Cookieless
- Privacy
- GDPR
- OpenAPI
- MCP
- Llms.txt
- EU-hosted
---
