---
api_specs:
- filename: podkitapp-com-admin-api-openapi.yml
  format: yaml
  label: podkitapp-com Admin API
  slug: podkitapp-com-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podkitapp-com/openapi/podkitapp-com-admin-api-openapi.yml
- filename: podkitapp-com-episodes-api-openapi.yml
  format: yaml
  label: podkitapp-com Episodes API
  slug: podkitapp-com-episodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podkitapp-com/openapi/podkitapp-com-episodes-api-openapi.yml
- filename: podkitapp-com-podcasts-api-openapi.yml
  format: yaml
  label: podkitapp-com Podcasts API
  slug: podkitapp-com-podcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podkitapp-com/openapi/podkitapp-com-podcasts-api-openapi.yml
- filename: podkitapp-com-search-api-openapi.yml
  format: yaml
  label: podkitapp-com Search API
  slug: podkitapp-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podkitapp-com/openapi/podkitapp-com-search-api-openapi.yml
- filename: podkitapp-com-usage-api-openapi.yml
  format: yaml
  label: podkitapp-com Usage API
  slug: podkitapp-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/podkitapp-com/openapi/podkitapp-com-usage-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for use by developers, no-code automation platforms (e.g. Zapier, Make, n8n), and AI/agent applications.
    type: developer
  minimum_age:
    text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive use
    text: Use the Service for any unlawful purpose, or to transmit malware, or to violate the intellectual property or privacy rights of any third party
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Service beyond public/unauthenticated pages, you need an API key, obtained either via our free-tier signup or by subscribing to a paid plan through checkout.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: podkitapp-com
provenance_date: '2026-11-10'
provider_name: podkitapp-com
provider_slug: podkitapp-com
slug: podkitapp-com-eligibility
source_date: '2026-11-10'
source_filename: podkitapp-com-eligibility.yml
source_heading: Eligibility
source_page: https://podkitapp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: podkitapp-com\naid: podkitapp-com\nurl: https://podkitapp.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: for use by developers, no-code automation platforms (e.g. Zapier, Make, n8n), and AI/agent applications.\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: Use the Service for any unlawful purpose, or to transmit malware, or to violate the intellectual property\n    or privacy rights of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Service beyond public/unauthenticated\
  \ pages, you need an API key, obtained either via our free-tier\n    signup or by subscribing to a paid plan through checkout.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/podkitapp-com/eligibility/podkitapp-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from podkitapp-com's own page on 2026-11-10.
synthetic: false
tags:
- Podcasts
- Data
- Developers
- Audio
---
