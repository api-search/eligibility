---
api_specs:
- filename: ansible-auth-api-openapi.yml
  format: yaml
  label: Ansible Auth API
  slug: ansible-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansible/openapi/ansible-auth-api-openapi.yml
- filename: ansible-credentials-api-openapi.yml
  format: yaml
  label: Ansible Credentials API
  slug: ansible-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansible/openapi/ansible-credentials-api-openapi.yml
- filename: ansible-hosts-api-openapi.yml
  format: yaml
  label: Ansible Hosts API
  slug: ansible-hosts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansible/openapi/ansible-hosts-api-openapi.yml
- filename: ansible-inventories-api-openapi.yml
  format: yaml
  label: Ansible Inventories API
  slug: ansible-inventories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansible/openapi/ansible-inventories-api-openapi.yml
- filename: ansible-job-templates-api-openapi.yml
  format: yaml
  label: Ansible Job Templates API
  slug: ansible-job-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansible/openapi/ansible-job-templates-api-openapi.yml
- filename: ansible-jobs-api-openapi.yml
  format: yaml
  label: Ansible Jobs API
  slug: ansible-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansible/openapi/ansible-jobs-api-openapi.yml
- filename: ansible-organizations-api-openapi.yml
  format: yaml
  label: Ansible Organizations API
  slug: ansible-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansible/openapi/ansible-organizations-api-openapi.yml
- filename: ansible-projects-api-openapi.yml
  format: yaml
  label: Ansible Projects API
  slug: ansible-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansible/openapi/ansible-projects-api-openapi.yml
- filename: ansible-schedules-api-openapi.yml
  format: yaml
  label: Ansible Schedules API
  slug: ansible-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansible/openapi/ansible-schedules-api-openapi.yml
- filename: ansible-users-api-openapi.yml
  format: yaml
  label: Ansible Users API
  slug: ansible-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansible/openapi/ansible-users-api-openapi.yml
- filename: ansible-workflow-job-templates-api-openapi.yml
  format: yaml
  label: Ansible Workflow Job Templates API
  slug: ansible-workflow-job-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansible/openapi/ansible-workflow-job-templates-api-openapi.yml
- filename: ansible-workflow-jobs-api-openapi.yml
  format: yaml
  label: Ansible Workflow Jobs API
  slug: ansible-workflow-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ansible/openapi/ansible-workflow-jobs-api-openapi.yml
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
  - summary: Export control
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
name: Ansible
provenance_date: '2026-11-09'
provider_name: Ansible
provider_slug: ansible
slug: ansible-eligibility
source_date: '2026-11-09'
source_filename: ansible-eligibility.yml
source_heading: Eligibility
source_page: https://www.redhat.com/en/about/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ansible\naid: ansible\nurl: https://www.redhat.com/en/about/terms-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site may refer to Red Hat products or services that might not be available in your location.\nentity_types: []\nrestricted_uses:\n- summary: Export control\n  text: you represent and warrant that you are not located in, under the control of, or a national or resident of\n    any country to which the United States has embargoed exports of goods, services, or technology.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '16'\n  text: You must be over 16 years old to create an Account on the Site.\n"
source_yaml_url: https://artifacts.apis.io/ansible/eligibility/ansible-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ansible's own page on 2026-11-09.
synthetic: false
tags:
- Ansible
- Automation
- Configuration Management
- DevOps
- Infrastructure as Code
- Open Source
- Orchestration
- Red Hat
---
