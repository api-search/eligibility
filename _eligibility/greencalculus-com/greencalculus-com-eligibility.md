---
api_specs:
- filename: greencalculus-com-account-api-openapi.yml
  format: yaml
  label: greencalculus-com Account API
  slug: greencalculus-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greencalculus-com/openapi/greencalculus-com-account-api-openapi.yml
- filename: greencalculus-com-bulk-api-openapi.yml
  format: yaml
  label: greencalculus-com Bulk API
  slug: greencalculus-com-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greencalculus-com/openapi/greencalculus-com-bulk-api-openapi.yml
- filename: greencalculus-com-calculate-api-openapi.yml
  format: yaml
  label: greencalculus-com Calculate API
  slug: greencalculus-com-calculate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greencalculus-com/openapi/greencalculus-com-calculate-api-openapi.yml
- filename: greencalculus-com-discovery-api-openapi.yml
  format: yaml
  label: greencalculus-com Discovery API
  slug: greencalculus-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greencalculus-com/openapi/greencalculus-com-discovery-api-openapi.yml
- filename: greencalculus-com-factors-api-openapi.yml
  format: yaml
  label: greencalculus-com Factors API
  slug: greencalculus-com-factors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/greencalculus-com/openapi/greencalculus-com-factors-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing the platform on behalf of an organisation, you represent that you have the authority to bind that organisation to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Misleading or deceptive reporting
    text: You must not use the platform for any purpose that is unlawful, fraudulent, or harmful — including the production of outputs intended to deceive investors, regulators, or the public about an organisation’s environmental performance.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Accounts are passwordless. Access is proved by a single-use link and code sent to your email address
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: greencalculus-com
provenance_date: '2026-11-09'
provider_name: greencalculus-com
provider_slug: greencalculus-com
slug: greencalculus-com-eligibility
source_date: '2026-11-09'
source_filename: greencalculus-com-eligibility.yml
source_heading: Eligibility
source_page: https://greencalculus.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: greencalculus-com\naid: greencalculus-com\nurl: https://greencalculus.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing the platform on behalf of an organisation, you represent that you have the authority\n    to bind that organisation to these Terms.\nrestricted_uses:\n- summary: Misleading or deceptive reporting\n  text: You must not use the platform for any purpose that is unlawful, fraudulent, or harmful — including the production\n    of outputs intended to deceive investors, regulators, or the public\
  \ about an organisation’s environmental performance.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Accounts are passwordless. Access is proved by a single-use link and code sent to your email address\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/greencalculus-com/eligibility/greencalculus-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from greencalculus-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Emissions
- Data
- Sustainability
---
