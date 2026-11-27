---
api_specs:
- filename: kolayik-approval-process-api-openapi.yml
  format: yaml
  label: KolayIK Approval Process API
  slug: kolayik-approval-process-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-approval-process-api-openapi.yml
- filename: kolayik-calendar-api-openapi.yml
  format: yaml
  label: KolayIK Calendar API
  slug: kolayik-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-calendar-api-openapi.yml
- filename: kolayik-expense-api-openapi.yml
  format: yaml
  label: KolayIK Expense API
  slug: kolayik-expense-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-expense-api-openapi.yml
- filename: kolayik-leave-api-openapi.yml
  format: yaml
  label: KolayIK Leave API
  slug: kolayik-leave-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-leave-api-openapi.yml
- filename: kolayik-payroll-api-openapi.yml
  format: yaml
  label: KolayIK Payroll API
  slug: kolayik-payroll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-payroll-api-openapi.yml
- filename: kolayik-person-api-openapi.yml
  format: yaml
  label: KolayIK Person API
  slug: kolayik-person-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-person-api-openapi.yml
- filename: kolayik-profile-api-openapi.yml
  format: yaml
  label: KolayIK Profile API
  slug: kolayik-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-profile-api-openapi.yml
- filename: kolayik-timelog-api-openapi.yml
  format: yaml
  label: KolayIK Timelog API
  slug: kolayik-timelog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-timelog-api-openapi.yml
- filename: kolayik-training-api-openapi.yml
  format: yaml
  label: KolayIK Training API
  slug: kolayik-training-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-training-api-openapi.yml
- filename: kolayik-transaction-api-openapi.yml
  format: yaml
  label: KolayIK Transaction API
  slug: kolayik-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-transaction-api-openapi.yml
- filename: kolayik-unit-api-openapi.yml
  format: yaml
  label: KolayIK Unit API
  slug: kolayik-unit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-unit-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: www.kolayik.com internet sitesine üye olan ve bu Sözleşme’yi onaylayan kullanıcı (“Şirket”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Security threats and harm to the platform or users
    text: Ayrıca Şirket’in Platform veya Kolay İK sistemlerinin güvenliğini tehdit edebilecek ve/veya Platform, Kolay İK ve diğer kullanıcılara zarar verebilecek eylemlerde bulunması
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
name: KolayIK
provenance_date: '2026-11-09'
provider_name: KolayIK
provider_slug: kolayik
slug: kolayik-eligibility
source_date: '2026-11-09'
source_filename: kolayik-eligibility.yml
source_heading: Eligibility
source_page: https://kolayik.com/kullanici-sozlesmesi
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KolayIK\naid: kolayik\nurl: https://kolayik.com/kullanici-sozlesmesi\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: www.kolayik.com internet sitesine üye olan ve bu Sözleşme’yi onaylayan kullanıcı (“Şirket”)\nrestricted_uses:\n- summary: Security threats and harm to the platform or users\n  text: Ayrıca Şirket’in Platform veya Kolay İK sistemlerinin güvenliğini tehdit edebilecek ve/veya Platform, Kolay\n    İK ve diğer kullanıcılara zarar verebilecek eylemlerde bulunması\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kolayik/eligibility/kolayik-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from KolayIK's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Human Resources
- Payroll
- HCM
- Employee Management
- Time and Attendance
- Applicant Tracking
- Software-as-a-Service
- Turkey
---
