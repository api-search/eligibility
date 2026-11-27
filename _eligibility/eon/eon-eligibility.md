---
api_specs:
- filename: eon-accounts-api-openapi.yml
  format: yaml
  label: Eon Accounts API
  slug: eon-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eon/openapi/eon-accounts-api-openapi.yml
- filename: eon-actionapprovals-api-openapi.yml
  format: yaml
  label: Eon Action Approvals API
  slug: eon-actionapprovals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eon/openapi/eon-actionapprovals-api-openapi.yml
- filename: eon-auth-api-openapi.yml
  format: yaml
  label: Eon Auth API
  slug: eon-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eon/openapi/eon-auth-api-openapi.yml
- filename: eon-backups-api-openapi.yml
  format: yaml
  label: Eon Backups API
  slug: eon-backups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eon/openapi/eon-backups-api-openapi.yml
- filename: eon-billing-api-openapi.yml
  format: yaml
  label: Eon Billing API
  slug: eon-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eon/openapi/eon-billing-api-openapi.yml
- filename: eon-dashboard-api-openapi.yml
  format: yaml
  label: Eon Dashboard API
  slug: eon-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eon/openapi/eon-dashboard-api-openapi.yml
- filename: eon-iam-api-openapi.yml
  format: yaml
  label: Eon Iam API
  slug: eon-iam-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eon/openapi/eon-iam-api-openapi.yml
- filename: eon-jobs-api-openapi.yml
  format: yaml
  label: Eon Jobs API
  slug: eon-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eon/openapi/eon-jobs-api-openapi.yml
- filename: eon-resources-api-openapi.yml
  format: yaml
  label: Eon Resources API
  slug: eon-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eon/openapi/eon-resources-api-openapi.yml
- filename: eon-snapshots-api-openapi.yml
  format: yaml
  label: Eon Snapshots API
  slug: eon-snapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eon/openapi/eon-snapshots-api-openapi.yml
- filename: eon-vaults-api-openapi.yml
  format: yaml
  label: Eon Vaults API
  slug: eon-vaults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eon/openapi/eon-vaults-api-openapi.yml
- filename: eon-backup-policies-api-openapi.yml
  format: yaml
  label: Eon Backup Policies API
  slug: eon-backup-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eon/openapi/eon-backup-policies-api-openapi.yml
- filename: eon-database-snapshots-api-openapi.yml
  format: yaml
  label: Eon Database Snapshots API
  slug: eon-database-snapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eon/openapi/eon-database-snapshots-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only intended for individuals aged thirteen (13) years or older.
    type: individual
  - text: you represent and warrant that you have the authority to bind the Company to this Agreement.
    type: business
  minimum_age:
    text: The Site is only intended for individuals aged thirteen (13) years or older.
    value: '13'
  restricted_uses:
  - summary: Competitive purposes
    text: use the Site for competitive purposes, and/or on behalf of any person or entity that competes with the activities, services, or products offered by Eon
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
name: Eon
provenance_date: '2026-11-09'
provider_name: Eon
provider_slug: eon
slug: eon-eligibility
source_date: '2026-11-09'
source_filename: eon-eligibility.yml
source_heading: Eligibility
source_page: https://www.eon.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eon\naid: eon\nurl: https://www.eon.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals aged thirteen (13) years or older.\n- type: business\n  text: you represent and warrant that you have the authority to bind the Company to this Agreement.\nrestricted_uses:\n- summary: Competitive purposes\n  text: use the Site for competitive purposes, and/or on behalf of any person or entity that competes with the activities,\n    services, or products offered by Eon\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Site is only intended for individuals aged thirteen (13) years or older.\n"
source_yaml_url: https://artifacts.apis.io/eon/eligibility/eon-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Eon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Backup
- Data Protection
- Disaster Recovery
- Ransomware Protection
- Backup
- Cloud Storage
- Data Lake
- Multi-Cloud
- Amazon Web Services
- Microsoft Azure
- Google Cloud
---
