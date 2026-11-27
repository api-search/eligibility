---
api_specs:
- filename: bulkpublish-com-openapi-generated.yml
  format: yaml
  label: BulkPublish API
  slug: bulkpublish-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bulkpublish-com/openapi/_ae-authored/bulkpublish-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of a company or another organization, you confirm that you have authority to bind it to these Terms, and "you" includes that organization.
    type: business
  minimum_age:
    text: You must be at least 16 years old, and old enough to enter into a binding contract where you live, to use the Service.
    value: '16'
  restricted_uses:
  - summary: Resale or white-labelling
    text: Resell, sublicense, or white-label the Service without our written consent
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
name: BulkPublish
provenance_date: '2026-11-09'
provider_name: BulkPublish
provider_slug: bulkpublish-com
slug: bulkpublish-com-eligibility
source_date: '2026-11-09'
source_filename: bulkpublish-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.bulkpublish.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BulkPublish\naid: bulkpublish-com\nurl: https://www.bulkpublish.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of a company or another organization, you confirm that you have authority\n    to bind it to these Terms, and \"you\" includes that organization.\nrestricted_uses:\n- summary: Resale or white-labelling\n  text: Resell, sublicense, or white-label the Service without our written consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '16'\n  text: You must be at least 16 years old, and old enough to enter into a binding contract where you live, to use\n    the Service.\n"
source_yaml_url: https://artifacts.apis.io/bulkpublish-com/eligibility/bulkpublish-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BulkPublish's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social Media
- Scheduling
- Publishing
---
