---
api_specs:
- filename: mendix-apps-api-openapi.yml
  format: yaml
  label: Mendix Apps API
  slug: mendix-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mendix/openapi/mendix-apps-api-openapi.yml
- filename: mendix-environments-api-openapi.yml
  format: yaml
  label: Mendix Environments API
  slug: mendix-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mendix/openapi/mendix-environments-api-openapi.yml
- filename: mendix-logs-api-openapi.yml
  format: yaml
  label: Mendix Logs API
  slug: mendix-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mendix/openapi/mendix-logs-api-openapi.yml
- filename: mendix-packages-api-openapi.yml
  format: yaml
  label: Mendix Packages API
  slug: mendix-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mendix/openapi/mendix-packages-api-openapi.yml
- filename: mendix-tags-api-openapi.yml
  format: yaml
  label: Mendix Tags API
  slug: mendix-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mendix/openapi/mendix-tags-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: “Sanctioned Country” means a country or territory that is itself the subject or target of any comprehensive trade or economic sanctions (currently Cuba, Iran, North Korea, Syria, and the Crimea region of Ukraine).
  entity_types:
  - text: The Mendix Website aims at companies or public enterprises, such companies or enterprises are represented by the user
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-civilian / military use
    text: unless expressly authorized by MENDIX in writing, used for non-civilian purposes (e.g. armaments, nuclear technology, weapons, any other usage in the field of defense and military).
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Mendix reserves the right to deny registration to any user.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mendix
provenance_date: '2026-11-10'
provider_name: Mendix
provider_slug: mendix
slug: mendix-eligibility
source_date: '2026-11-10'
source_filename: mendix-eligibility.yml
source_heading: Eligibility
source_page: https://www.mendix.com/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mendix\naid: mendix\nurl: https://www.mendix.com/legal/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: “Sanctioned Country” means a country or territory that is itself the subject or target of any comprehensive\n    trade or economic sanctions (currently Cuba, Iran, North Korea, Syria, and the Crimea region of Ukraine).\nentity_types:\n- type: business\n  text: The Mendix Website aims at companies or public enterprises, such companies or enterprises are represented\n    by the user\nrestricted_uses:\n- summary: Non-civilian / military use\n\
  \  text: unless expressly authorized by MENDIX in writing, used for non-civilian purposes (e.g. armaments, nuclear\n    technology, weapons, any other usage in the field of defense and military).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Mendix reserves the right to deny registration to any user.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mendix/eligibility/mendix-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Mendix's own page on 2026-11-10.
synthetic: false
tags:
- Low-Code
- Application Development
- Enterprise Platform
- Application Lifecycle
- Deployment
- Governance
---
