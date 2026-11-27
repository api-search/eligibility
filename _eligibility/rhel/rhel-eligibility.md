---
api_specs:
- filename: rhel-advisories-api-openapi.yml
  format: yaml
  label: Red Hat Enterprise Linux Advisories API
  slug: rhel-advisories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhel/openapi/rhel-advisories-api-openapi.yml
- filename: rhel-oval-api-openapi.yml
  format: yaml
  label: Red Hat Enterprise Linux OVAL API
  slug: rhel-oval-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhel/openapi/rhel-oval-api-openapi.yml
- filename: rhel-subscriptions-api-openapi.yml
  format: yaml
  label: Red Hat Enterprise Linux Subscriptions API
  slug: rhel-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhel/openapi/rhel-subscriptions-api-openapi.yml
- filename: rhel-systems-api-openapi.yml
  format: yaml
  label: Red Hat Enterprise Linux Systems API
  slug: rhel-systems-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhel/openapi/rhel-systems-api-openapi.yml
- filename: rhel-cves-api-openapi.yml
  format: yaml
  label: Red Hat Enterprise Linux CV Es API
  slug: rhel-cves-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhel/openapi/rhel-cves-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site may refer to Red Hat products or services that might not be available in your location.
  minimum_age:
    text: You must be over 16 years old to create an Account on the Site.
    value: '16'
  restricted_uses:
  - summary: Export-controlled destinations and end uses
    text: you represent and warrant that you are not located in, under the control of, or a national or resident of any country to which the United States has embargoed exports of goods, services, or technology.
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
name: Red Hat Enterprise Linux
provenance_date: '2026-11-10'
provider_name: Red Hat Enterprise Linux
provider_slug: rhel
slug: rhel-eligibility
source_date: '2026-11-10'
source_filename: rhel-eligibility.yml
source_heading: Eligibility
source_page: https://www.redhat.com/en/about/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Red Hat Enterprise Linux\naid: rhel\nurl: https://www.redhat.com/en/about/terms-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site may refer to Red Hat products or services that might not be available in your location.\nentity_types: []\nrestricted_uses:\n- summary: Export-controlled destinations and end uses\n  text: you represent and warrant that you are not located in, under the control of, or a national or resident of\n    any country to which the United States has embargoed exports of goods, services, or technology.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be over 16 years old to create an Account on the Site.\n"
source_yaml_url: https://artifacts.apis.io/rhel/eligibility/rhel-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Red Hat Enterprise Linux's own page on 2026-11-10.
synthetic: false
tags:
- Automation
- Compliance
- Enterprise
- Linux
- Operating System
- Red Hat
- RHEL
- Security
- Subscription Management
- Vulnerability Management
---
