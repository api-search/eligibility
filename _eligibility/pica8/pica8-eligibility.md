---
api_specs:
- filename: pica8-backup-api-openapi.yml
  format: yaml
  label: Pica8 Backup API
  slug: pica8-backup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pica8/openapi/pica8-backup-api-openapi.yml
- filename: pica8-configuration-api-openapi.yml
  format: yaml
  label: Pica8 Configuration API
  slug: pica8-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pica8/openapi/pica8-configuration-api-openapi.yml
- filename: pica8-configurationfile-api-openapi.yml
  format: yaml
  label: Pica8 Configuration File API
  slug: pica8-configurationfile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pica8/openapi/pica8-configurationfile-api-openapi.yml
- filename: pica8-group-api-openapi.yml
  format: yaml
  label: Pica8 Group API
  slug: pica8-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pica8/openapi/pica8-group-api-openapi.yml
- filename: pica8-job-api-openapi.yml
  format: yaml
  label: Pica8 Job API
  slug: pica8-job-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pica8/openapi/pica8-job-api-openapi.yml
- filename: pica8-license-api-openapi.yml
  format: yaml
  label: Pica8 License API
  slug: pica8-license-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pica8/openapi/pica8-license-api-openapi.yml
- filename: pica8-playbook-api-openapi.yml
  format: yaml
  label: Pica8 Playbook API
  slug: pica8-playbook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pica8/openapi/pica8-playbook-api-openapi.yml
- filename: pica8-settings-api-openapi.yml
  format: yaml
  label: Pica8 Settings API
  slug: pica8-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pica8/openapi/pica8-settings-api-openapi.yml
- filename: pica8-switch-api-openapi.yml
  format: yaml
  label: Pica8 Switch API
  slug: pica8-switch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pica8/openapi/pica8-switch-api-openapi.yml
- filename: pica8-template-api-openapi.yml
  format: yaml
  label: Pica8 Template API
  slug: pica8-template-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pica8/openapi/pica8-template-api-openapi.yml
- filename: pica8-token-api-openapi.yml
  format: yaml
  label: Pica8 Token API
  slug: pica8-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pica8/openapi/pica8-token-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual acting on behalf of an entity, you represent that you have the authority to bind the entity to this EULA, and all references to "you" in this EULA mean that entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control
    text: You shall not use or otherwise export or re-export the Software except as authorized by United States law.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must register with Pica8 and create an account in order to download the Software and generate license keys.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pica8
provenance_date: '2026-11-10'
provider_name: Pica8
provider_slug: pica8
slug: pica8-eligibility
source_date: '2026-11-10'
source_filename: pica8-eligibility.yml
source_heading: Eligibility
source_page: https://www.pica8.com/support/warranty-and-agreements
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pica8\naid: pica8\nurl: https://www.pica8.com/support/warranty-and-agreements\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are an individual acting on behalf of an entity, you represent that you have the authority to bind\n    the entity to this EULA, and all references to \"you\" in this EULA mean that entity.\nrestricted_uses:\n- summary: Export control\n  text: You shall not use or otherwise export or re-export the Software except as authorized by United States law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: You must register with Pica8 and create an account in order to download the Software and generate license\n    keys.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pica8/eligibility/pica8-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Pica8's own page on 2026-11-10.
synthetic: false
tags:
- Networking
- Open Networking
- Software Defined Networking
- Network Automation
- Network Operating System
- white-box-switching
- Network Management
- Campus Networking
- Data Center Networking
- RESTCONF
- NETCONF
- Telemetry
---
