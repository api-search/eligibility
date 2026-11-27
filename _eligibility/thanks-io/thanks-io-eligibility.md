---
api_specs:
- filename: thanks-io-creatives-library-api-openapi.yml
  format: yaml
  label: Thanks.io Creatives Library API
  slug: thanks-io-creatives-library-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanks-io/openapi/thanks-io-creatives-library-api-openapi.yml
- filename: thanks-io-dynamic-images-api-openapi.yml
  format: yaml
  label: Thanks.io Dynamic Images API
  slug: thanks-io-dynamic-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanks-io/openapi/thanks-io-dynamic-images-api-openapi.yml
- filename: thanks-io-giftcards-api-openapi.yml
  format: yaml
  label: Thanks.io Giftcards API
  slug: thanks-io-giftcards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanks-io/openapi/thanks-io-giftcards-api-openapi.yml
- filename: thanks-io-handwriting-styles-api-openapi.yml
  format: yaml
  label: Thanks.io Handwriting Styles API
  slug: thanks-io-handwriting-styles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanks-io/openapi/thanks-io-handwriting-styles-api-openapi.yml
- filename: thanks-io-image-templates-api-openapi.yml
  format: yaml
  label: Thanks.io Image Templates API
  slug: thanks-io-image-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanks-io/openapi/thanks-io-image-templates-api-openapi.yml
- filename: thanks-io-mailing-lists-api-openapi.yml
  format: yaml
  label: Thanks.io Mailing Lists API
  slug: thanks-io-mailing-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanks-io/openapi/thanks-io-mailing-lists-api-openapi.yml
- filename: thanks-io-message-templates-api-openapi.yml
  format: yaml
  label: Thanks.io Message Templates API
  slug: thanks-io-message-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanks-io/openapi/thanks-io-message-templates-api-openapi.yml
- filename: thanks-io-order-estimates-api-openapi.yml
  format: yaml
  label: Thanks.io Order Estimates API
  slug: thanks-io-order-estimates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanks-io/openapi/thanks-io-order-estimates-api-openapi.yml
- filename: thanks-io-orders-api-openapi.yml
  format: yaml
  label: Thanks.io Orders API
  slug: thanks-io-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanks-io/openapi/thanks-io-orders-api-openapi.yml
- filename: thanks-io-recipients-api-openapi.yml
  format: yaml
  label: Thanks.io Recipients API
  slug: thanks-io-recipients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanks-io/openapi/thanks-io-recipients-api-openapi.yml
- filename: thanks-io-send-mailer-api-openapi.yml
  format: yaml
  label: Thanks.io Send Mailer API
  slug: thanks-io-send-mailer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanks-io/openapi/thanks-io-send-mailer-api-openapi.yml
- filename: thanks-io-webhook-events-api-openapi.yml
  format: yaml
  label: Thanks.io Webhook Events API
  slug: thanks-io-webhook-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanks-io/openapi/thanks-io-webhook-events-api-openapi.yml
- filename: thanks-io-webhooks-api-openapi.yml
  format: yaml
  label: Thanks.io Webhooks API
  slug: thanks-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanks-io/openapi/thanks-io-webhooks-api-openapi.yml
- filename: thanks-io-subaccounts-api-openapi.yml
  format: yaml
  label: Thanks.io Subaccounts API
  slug: thanks-io-subaccounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thanks-io/openapi/thanks-io-subaccounts-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If You are accepting on behalf of Your employer or another entity, You represent and warrant that: (i) You have full legal authority to bind your employer, or the applicable entity, to these terms of service'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or deceptive content
    text: Is fraudulent, deceptive, threatening, abusive, defamatory, harassing, obscene, or otherwise unlawful;
  - summary: AI-enabled deceptive impersonation
    text: Uses artificial intelligence or other features of the Services to create deceptive or unlawful impersonations, manipulated content, or other misleading materials;
  - summary: Scams or illegal products
    text: Promotes or facilitates illegal products, services, activities, scams, or fraudulent schemes;
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
name: Thanks.io
provenance_date: '2026-11-10'
provider_name: Thanks.io
provider_slug: thanks-io
slug: thanks-io-eligibility
source_date: '2026-11-10'
source_filename: thanks-io-eligibility.yml
source_heading: Eligibility
source_page: https://thanks.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Thanks.io\naid: thanks-io\nurl: https://thanks.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If You are accepting on behalf of Your employer or another entity, You represent and warrant that: (i)\n    You have full legal authority to bind your employer, or the applicable entity, to these terms of service'\nrestricted_uses:\n- summary: Unlawful or deceptive content\n  text: Is fraudulent, deceptive, threatening, abusive, defamatory, harassing, obscene, or otherwise unlawful;\n- summary: AI-enabled deceptive impersonation\n\
  \  text: Uses artificial intelligence or other features of the Services to create deceptive or unlawful impersonations,\n    manipulated content, or other misleading materials;\n- summary: Scams or illegal products\n  text: Promotes or facilitates illegal products, services, activities, scams, or fraudulent schemes;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/thanks-io/eligibility/thanks-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Thanks.io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Direct Mail
- Automation
---
