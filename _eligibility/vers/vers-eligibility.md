---
api_specs:
- filename: vers-commit-tags-api-openapi.yml
  format: yaml
  label: Vers Commit Tags API
  slug: vers-commit-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vers/openapi/vers-commit-tags-api-openapi.yml
- filename: vers-commits-api-openapi.yml
  format: yaml
  label: Vers Commits API
  slug: vers-commits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vers/openapi/vers-commits-api-openapi.yml
- filename: vers-deploy-api-openapi.yml
  format: yaml
  label: Vers Deploy API
  slug: vers-deploy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vers/openapi/vers-deploy-api-openapi.yml
- filename: vers-domains-api-openapi.yml
  format: yaml
  label: Vers Domains API
  slug: vers-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vers/openapi/vers-domains-api-openapi.yml
- filename: vers-env-vars-api-openapi.yml
  format: yaml
  label: Vers Env Vars API
  slug: vers-env-vars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vers/openapi/vers-env-vars-api-openapi.yml
- filename: vers-images-api-openapi.yml
  format: yaml
  label: Vers Images API
  slug: vers-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vers/openapi/vers-images-api-openapi.yml
- filename: vers-keys-api-openapi.yml
  format: yaml
  label: Vers Keys API
  slug: vers-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vers/openapi/vers-keys-api-openapi.yml
- filename: vers-public-repositories-api-openapi.yml
  format: yaml
  label: Vers Public Repositories API
  slug: vers-public-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vers/openapi/vers-public-repositories-api-openapi.yml
- filename: vers-repositories-api-openapi.yml
  format: yaml
  label: Vers Repositories API
  slug: vers-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vers/openapi/vers-repositories-api-openapi.yml
- filename: vers-system-api-openapi.yml
  format: yaml
  label: Vers System API
  slug: vers-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vers/openapi/vers-system-api-openapi.yml
- filename: vers-vm-api-openapi.yml
  format: yaml
  label: Vers Vm API
  slug: vers-vm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vers/openapi/vers-vm-api-openapi.yml
- filename: vers-vms-api-openapi.yml
  format: yaml
  label: Vers Vms API
  slug: vers-vms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vers/openapi/vers-vms-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in, under the control of, or a national or resident of any country subject to U.S. embargo, and that you are not on any U.S. government restricted party list.
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: Illegal, fraudulent or harmful use
    text: in any way is illegal, threatening, fraudulent, or harmful, or in connection with any unlawful, illegal, fraudulent, or harmful purpose or activity
  - summary: Malware and attacks
    text: Launching or facilitating distributed denial-of-service (DDoS) attacks or other network attacks
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
name: Vers
provenance_date: '2026-11-10'
provider_name: Vers
provider_slug: vers
slug: vers-eligibility
source_date: '2026-11-10'
source_filename: vers-eligibility.yml
source_heading: Eligibility
source_page: https://vers.sh/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vers\naid: vers\nurl: https://vers.sh/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in, under the control of, or a national or resident of\n    any country subject to U.S. embargo, and that you are not on any U.S. government restricted party list.\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority\n    to bind that organization to these Terms.\nrestricted_uses:\n- summary: Illegal, fraudulent or harmful use\n\
  \  text: in any way is illegal, threatening, fraudulent, or harmful, or in connection with any unlawful, illegal,\n    fraudulent, or harmful purpose or activity\n- summary: Malware and attacks\n  text: Launching or facilitating distributed denial-of-service (DDoS) attacks or other network attacks\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/vers/eligibility/vers-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Vers's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Compute
- Virtualization
- MicroVM
- Orchestration
- Infrastructure
- AI Agents
- Developer Tools
- Sandbox
- CI/CD
---
