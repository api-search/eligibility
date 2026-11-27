---
api_specs:
- filename: threatlocker-application-api-openapi.yml
  format: yaml
  label: ThreatLocker Application API
  slug: threatlocker-application-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-application-api-openapi.yml
- filename: threatlocker-computer-api-openapi.yml
  format: yaml
  label: ThreatLocker Computer API
  slug: threatlocker-computer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-computer-api-openapi.yml
- filename: threatlocker-computercheckin-api-openapi.yml
  format: yaml
  label: ThreatLocker Computer Checkin API
  slug: threatlocker-computercheckin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-computercheckin-api-openapi.yml
- filename: threatlocker-computergroup-api-openapi.yml
  format: yaml
  label: ThreatLocker Computer Group API
  slug: threatlocker-computergroup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-computergroup-api-openapi.yml
- filename: threatlocker-maintenancemode-api-openapi.yml
  format: yaml
  label: ThreatLocker Maintenance Mode API
  slug: threatlocker-maintenancemode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-maintenancemode-api-openapi.yml
- filename: threatlocker-onlinedevices-api-openapi.yml
  format: yaml
  label: ThreatLocker Online Devices API
  slug: threatlocker-onlinedevices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-onlinedevices-api-openapi.yml
- filename: threatlocker-organization-api-openapi.yml
  format: yaml
  label: ThreatLocker Organization API
  slug: threatlocker-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-organization-api-openapi.yml
- filename: threatlocker-policy-api-openapi.yml
  format: yaml
  label: ThreatLocker Policy API
  slug: threatlocker-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-policy-api-openapi.yml
- filename: threatlocker-report-api-openapi.yml
  format: yaml
  label: ThreatLocker Report API
  slug: threatlocker-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-report-api-openapi.yml
- filename: threatlocker-savesearch-api-openapi.yml
  format: yaml
  label: ThreatLocker Save Search API
  slug: threatlocker-savesearch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-savesearch-api-openapi.yml
- filename: threatlocker-scheduledagentaction-api-openapi.yml
  format: yaml
  label: ThreatLocker Scheduled Agent Action API
  slug: threatlocker-scheduledagentaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-scheduledagentaction-api-openapi.yml
- filename: threatlocker-systemaudit-api-openapi.yml
  format: yaml
  label: ThreatLocker System Audit API
  slug: threatlocker-systemaudit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-systemaudit-api-openapi.yml
- filename: threatlocker-tag-api-openapi.yml
  format: yaml
  label: ThreatLocker Tag API
  slug: threatlocker-tag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-tag-api-openapi.yml
- filename: threatlocker-threatlockerversion-api-openapi.yml
  format: yaml
  label: ThreatLocker Threat Locker Version API
  slug: threatlocker-threatlockerversion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-threatlockerversion-api-openapi.yml
- filename: threatlocker-uploadrequest-api-openapi.yml
  format: yaml
  label: ThreatLocker Upload Request API
  slug: threatlocker-uploadrequest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-uploadrequest-api-openapi.yml
- filename: threatlocker-vdihyperv-api-openapi.yml
  format: yaml
  label: ThreatLocker VDI Hyper V API
  slug: threatlocker-vdihyperv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-vdihyperv-api-openapi.yml
- filename: threatlocker-action-log-api-openapi.yml
  format: yaml
  label: ThreatLocker Action Log API
  slug: threatlocker-action-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-action-log-api-openapi.yml
- filename: threatlocker-approval-request-api-openapi.yml
  format: yaml
  label: ThreatLocker Approval Request API
  slug: threatlocker-approval-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threatlocker/openapi/threatlocker-approval-request-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the client listed in the Order
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk and life support applications
    text: in any application that may involve risks of death, personal injury, severe property damage or environmental damage, or in any life support applications, devices or systems
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
name: ThreatLocker
provenance_date: '2026-11-10'
provider_name: ThreatLocker
provider_slug: threatlocker
slug: threatlocker-eligibility
source_date: '2026-11-10'
source_filename: threatlocker-eligibility.yml
source_heading: Eligibility
source_page: https://www.threatlocker.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ThreatLocker\naid: threatlocker\nurl: https://www.threatlocker.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the client listed in the Order\nrestricted_uses:\n- summary: High-risk and life support applications\n  text: in any application that may involve risks of death, personal injury, severe property damage or environmental\n    damage, or in any life support applications, devices or systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/threatlocker/eligibility/threatlocker-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from ThreatLocker's own page on 2026-11-10.
synthetic: false
tags:
- Cybersecurity
- Zero Trust
- Endpoint Security
- Application-Control
- allowlisting
- Ransomware Prevention
- Privileged Access Management
- Network Access Control
- Managed Detection and Response
- Device Management
- MSP
- Compliance
---
