---
api_specs:
- filename: mon-ami-care-plans-api-openapi.yml
  format: yaml
  label: Mon Ami Care Plans API
  slug: mon-ami-care-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-care-plans-api-openapi.yml
- filename: mon-ami-client-calls-api-openapi.yml
  format: yaml
  label: Mon Ami Client Calls API
  slug: mon-ami-client-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-client-calls-api-openapi.yml
- filename: mon-ami-clients-api-openapi.yml
  format: yaml
  label: Mon Ami Clients API
  slug: mon-ami-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-clients-api-openapi.yml
- filename: mon-ami-copays-api-openapi.yml
  format: yaml
  label: Mon Ami Copays API
  slug: mon-ami-copays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-copays-api-openapi.yml
- filename: mon-ami-documents-api-openapi.yml
  format: yaml
  label: Mon Ami Documents API
  slug: mon-ami-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-documents-api-openapi.yml
- filename: mon-ami-funding-sources-api-openapi.yml
  format: yaml
  label: Mon Ami Funding Sources API
  slug: mon-ami-funding-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-funding-sources-api-openapi.yml
- filename: mon-ami-languages-api-openapi.yml
  format: yaml
  label: Mon Ami Languages API
  slug: mon-ami-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-languages-api-openapi.yml
- filename: mon-ami-people-api-openapi.yml
  format: yaml
  label: Mon Ami People API
  slug: mon-ami-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-people-api-openapi.yml
- filename: mon-ami-programs-api-openapi.yml
  format: yaml
  label: Mon Ami Programs API
  slug: mon-ami-programs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-programs-api-openapi.yml
- filename: mon-ami-provider-referrals-api-openapi.yml
  format: yaml
  label: Mon Ami Provider Referrals API
  slug: mon-ami-provider-referrals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-provider-referrals-api-openapi.yml
- filename: mon-ami-providers-api-openapi.yml
  format: yaml
  label: Mon Ami Providers API
  slug: mon-ami-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-providers-api-openapi.yml
- filename: mon-ami-services-api-openapi.yml
  format: yaml
  label: Mon Ami Services API
  slug: mon-ami-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-services-api-openapi.yml
- filename: mon-ami-sites-api-openapi.yml
  format: yaml
  label: Mon Ami Sites API
  slug: mon-ami-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-sites-api-openapi.yml
- filename: mon-ami-tasks-api-openapi.yml
  format: yaml
  label: Mon Ami Tasks API
  slug: mon-ami-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-tasks-api-openapi.yml
- filename: mon-ami-visits-api-openapi.yml
  format: yaml
  label: Mon Ami Visits API
  slug: mon-ami-visits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-visits-api-openapi.yml
- filename: mon-ami-volunteers-api-openapi.yml
  format: yaml
  label: Mon Ami Volunteers API
  slug: mon-ami-volunteers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-volunteers-api-openapi.yml
- filename: mon-ami-webhooks-api-openapi.yml
  format: yaml
  label: Mon Ami Webhooks API
  slug: mon-ami-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mon-ami/openapi/mon-ami-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that you represent)
    type: business
  minimum_age:
    text: You may not access or use the Site or accept the Terms if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Acceptable use policy restrictions
    text: You agree not to use the Site to collect, upload, transmit, display, or distribute any User Content (i) that violates any third-party right
  - summary: No unauthorized access or interference
    text: attempt to gain unauthorized access to the Site (or to other computer systems or networks connected to or used together with the Site)
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
name: Mon Ami
provenance_date: '2026-11-10'
provider_name: Mon Ami
provider_slug: mon-ami
slug: mon-ami-eligibility
source_date: '2026-11-10'
source_filename: mon-ami-eligibility.yml
source_heading: Eligibility
source_page: https://www.monami.io/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mon Ami\naid: mon-ami\nurl: https://www.monami.io/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By accessing or using the Site, you are accepting these Terms (on behalf of yourself or the entity that\n    you represent)\nrestricted_uses:\n- summary: Acceptable use policy restrictions\n  text: You agree not to use the Site to collect, upload, transmit, display, or distribute any User Content (i)\n    that violates any third-party right\n- summary: No unauthorized access or interference\n  text: attempt to gain unauthorized\
  \ access to the Site (or to other computer systems or networks connected to or\n    used together with the Site)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not access or use the Site or accept the Terms if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/mon-ami/eligibility/mon-ami-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Mon Ami's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Aging Services
- Disability Services
- Case Management
- Care Coordination
- FHIR
- HIPAA
---
