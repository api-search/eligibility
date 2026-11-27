---
api_specs:
- filename: controlplane-about-api-openapi.yml
  format: yaml
  label: ControlPlane About API
  slug: controlplane-about-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/controlplane/openapi/controlplane-about-api-openapi.yml
- filename: controlplane-artifacts-api-openapi.yml
  format: yaml
  label: ControlPlane Artifacts API
  slug: controlplane-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/controlplane/openapi/controlplane-artifacts-api-openapi.yml
- filename: controlplane-audit-api-openapi.yml
  format: yaml
  label: ControlPlane Audit API
  slug: controlplane-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/controlplane/openapi/controlplane-audit-api-openapi.yml
- filename: controlplane-controlplane-api-api-openapi.yml
  format: yaml
  label: ControlPlane ControlPlane API
  slug: controlplane-controlplane-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/controlplane/openapi/controlplane-controlplane-api-api-openapi.yml
- filename: controlplane-docker-api-openapi.yml
  format: yaml
  label: ControlPlane Docker API
  slug: controlplane-docker-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/controlplane/openapi/controlplane-docker-api-openapi.yml
- filename: controlplane-health-api-openapi.yml
  format: yaml
  label: ControlPlane Health API
  slug: controlplane-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/controlplane/openapi/controlplane-health-api-openapi.yml
- filename: controlplane-helm-api-openapi.yml
  format: yaml
  label: ControlPlane Helm API
  slug: controlplane-helm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/controlplane/openapi/controlplane-helm-api-openapi.yml
- filename: controlplane-org-api-openapi.yml
  format: yaml
  label: ControlPlane Org API
  slug: controlplane-org-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/controlplane/openapi/controlplane-org-api-openapi.yml
- filename: controlplane-quota-catalog-api-openapi.yml
  format: yaml
  label: ControlPlane Quota Catalog API
  slug: controlplane-quota-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/controlplane/openapi/controlplane-quota-catalog-api-openapi.yml
- filename: controlplane-quota-increase-requests-api-openapi.yml
  format: yaml
  label: ControlPlane Quota Increase Requests API
  slug: controlplane-quota-increase-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/controlplane/openapi/controlplane-quota-increase-requests-api-openapi.yml
- filename: controlplane-resources-api-openapi.yml
  format: yaml
  label: ControlPlane Resources API
  slug: controlplane-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/controlplane/openapi/controlplane-resources-api-openapi.yml
- filename: controlplane-signups-api-openapi.yml
  format: yaml
  label: ControlPlane Signups API
  slug: controlplane-signups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/controlplane/openapi/controlplane-signups-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An account is set up by an individual human who accepts the Terms personally or on behalf of the account entity
    type: individual
  minimum_age:
    text: A User must be at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Cryptocurrency mining
    text: or is used to mine cryptocurrencies in any way.
  - summary: Exploit delivery or malware
    text: contains or installs any active malware or exploits, or uses our Platform for exploit delivery (such as part of a command and control system)
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
name: ControlPlane
provenance_date: '2026-11-09'
provider_name: ControlPlane
provider_slug: controlplane
slug: controlplane-eligibility
source_date: '2026-11-09'
source_filename: controlplane-eligibility.yml
source_heading: Eligibility
source_page: https://controlplane.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ControlPlane\naid: controlplane\nurl: https://controlplane.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An account is set up by an individual human who accepts the Terms personally or on behalf of the account\n    entity\nrestricted_uses:\n- summary: Cryptocurrency mining\n  text: or is used to mine cryptocurrencies in any way.\n- summary: Exploit delivery or malware\n  text: contains or installs any active malware or exploits, or uses our Platform for exploit delivery (such as\n    part of a command and control\
  \ system)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: A User must be at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/controlplane/eligibility/controlplane-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ControlPlane's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud
- Virtualization
- Artificial Intelligence
- DevOps
---
