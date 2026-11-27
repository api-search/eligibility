---
api_specs:
- filename: jurisign-account-api-openapi.yml
  format: yaml
  label: JuriSign Account API
  slug: jurisign-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-account-api-openapi.yml
- filename: jurisign-authentication-api-openapi.yml
  format: yaml
  label: JuriSign Authentication API
  slug: jurisign-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-authentication-api-openapi.yml
- filename: jurisign-bulk-api-openapi.yml
  format: yaml
  label: JuriSign Bulk API
  slug: jurisign-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-bulk-api-openapi.yml
- filename: jurisign-documents-api-openapi.yml
  format: yaml
  label: JuriSign Documents API
  slug: jurisign-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-documents-api-openapi.yml
- filename: jurisign-public-forms-api-openapi.yml
  format: yaml
  label: JuriSign Public Forms API
  slug: jurisign-public-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-public-forms-api-openapi.yml
- filename: jurisign-sign-requests-api-openapi.yml
  format: yaml
  label: JuriSign Sign Requests API
  slug: jurisign-sign-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-sign-requests-api-openapi.yml
- filename: jurisign-templates-api-openapi.yml
  format: yaml
  label: JuriSign Templates API
  slug: jurisign-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-templates-api-openapi.yml
- filename: jurisign-webhooks-api-openapi.yml
  format: yaml
  label: JuriSign Webhooks API
  slug: jurisign-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jurisign/openapi/jurisign-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Actes exigeant une signature avancée ou qualifiée
    text: Ce niveau n'est pas adapté aux actes juridiques imposant une signature électronique avancée ou qualifiée (actes notariés, marchés publics réglementaires, contrats d'assurance soumis à des exigences spécifiques).
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: vérifier leur identité par code à usage unique (OTP) transmis par SMS ou courriel
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: JuriSign
provenance_date: '2026-11-09'
provider_name: JuriSign
provider_slug: jurisign
slug: jurisign-eligibility
source_date: '2026-11-09'
source_filename: jurisign-eligibility.yml
source_heading: Eligibility
source_page: https://www.jurisign.fr/cgu
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JuriSign\naid: jurisign\nurl: https://www.jurisign.fr/cgu\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Actes exigeant une signature avancée ou qualifiée\n  text: Ce niveau n'est pas adapté aux actes juridiques imposant une signature électronique avancée ou qualifiée\n    (actes notariés, marchés publics réglementaires, contrats d'assurance soumis à des exigences spécifiques).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: vérifier leur identité par code à usage unique (OTP) transmis par SMS ou courriel\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jurisign/eligibility/jurisign-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from JuriSign's own page on 2026-11-09.
synthetic: false
tags:
- E-Signature
- eIDAS
- PDF
- Webhook
- OTP
- GDPR
- France
- Legal Tech
- Identity Verification
- Audit Trail
- data-residency-eu
---
