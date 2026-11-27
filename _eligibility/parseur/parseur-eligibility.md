---
api_specs:
- filename: parseur-async-api-openapi.yml
  format: yaml
  label: Parseur Async API
  slug: parseur-async-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseur/openapi/parseur-async-api-openapi.yml
- filename: parseur-bootstrap-api-openapi.yml
  format: yaml
  label: Parseur Bootstrap API
  slug: parseur-bootstrap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseur/openapi/parseur-bootstrap-api-openapi.yml
- filename: parseur-document-api-openapi.yml
  format: yaml
  label: Parseur Document API
  slug: parseur-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseur/openapi/parseur-document-api-openapi.yml
- filename: parseur-parser-api-openapi.yml
  format: yaml
  label: Parseur Parser API
  slug: parseur-parser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseur/openapi/parseur-parser-api-openapi.yml
- filename: parseur-template-api-openapi.yml
  format: yaml
  label: Parseur Template API
  slug: parseur-template-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseur/openapi/parseur-template-api-openapi.yml
- filename: parseur-webhook-api-openapi.yml
  format: yaml
  label: Parseur Webhook API
  slug: parseur-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parseur/openapi/parseur-webhook-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'No software from the Services may be downloaded, exported or re-exported: Into any European Union and/or U.S. embargoed countries'
  entity_types:
  - text: Customers subscribing to Enterprise plans may elect to pay by bank wire transfer and/or purchase order
    type: business
  minimum_age:
    text: The use of any of our Services by anyone under the age of 18 is prohibited.
    value: '18'
  restricted_uses:
  - summary: High-risk uses
    text: for any high risk use where failure or fault of the Services could lead to death or serious bodily injury of any person
  - summary: Special category data
    text: It shall not use the Services to collect, store or process any special category data
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The Company is entitled to refuse any order placed by a Customer. If an order is accepted, the Company will confirm acceptance via email.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Parseur
provenance_date: '2026-11-10'
provider_name: Parseur
provider_slug: parseur
slug: parseur-eligibility
source_date: '2026-11-10'
source_filename: parseur-eligibility.yml
source_heading: Eligibility
source_page: https://parseur.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Parseur\naid: parseur\nurl: https://parseur.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'No software from the Services may be downloaded, exported or re-exported: Into any European Union and/or\n    U.S. embargoed countries'\nentity_types:\n- type: business\n  text: Customers subscribing to Enterprise plans may elect to pay by bank wire transfer and/or purchase order\nrestricted_uses:\n- summary: High-risk uses\n  text: for any high risk use where failure or fault of the Services could lead to death or serious bodily injury\n    of any person\n- summary: Special category\
  \ data\n  text: It shall not use the Services to collect, store or process any special category data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The Company is entitled to refuse any order placed by a Customer. If an order is accepted, the Company will\n    confirm acceptance via email.\nminimum_age:\n  value: '18'\n  text: The use of any of our Services by anyone under the age of 18 is prohibited.\n"
source_yaml_url: https://artifacts.apis.io/parseur/eligibility/parseur-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Parseur's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Document Parsing
- Document Processing
- Document Extraction
- Email Parsing
- OCR
- Data Extraction
- Vision AI
- Automation
- Webhook
- Mailboxes
- Software-as-a-Service
---
