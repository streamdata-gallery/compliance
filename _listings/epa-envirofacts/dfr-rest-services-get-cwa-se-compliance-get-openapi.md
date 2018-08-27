---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) Detailed Facility Report CWA SEV Compliance Service
  description: This procedure obtains data for the CWA Single Event Violations section
    of the DFR.
  contact:
    name: US EPA, OECA Integration, Targeting and Access Branch
  version: 0.0.0
host: ofmpub.epa.gov
basePath: /echo
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /dfr_rest_services.get_sdwis_compliance:
    get:
      summary: Detailed Facility Report SDWIS Compliance Service
      description: This procedure obtains data for the SDWA Compliance section of
        the DFR.
      operationId: this-procedure-obtains-data-for-the-sdwa-compliance-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-sdwis-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - SDWIS
      - Compliance
      - Service
  /dfr_rest_services.get_rcra_compliance:
    get:
      summary: Detailed Facility Report RCRA Compliance Service
      description: This procedure obtains data for the RCRA Compliance section of
        the DFR.
      operationId: this-procedure-obtains-data-for-the-rcra-compliance-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-rcra-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - RCRA
      - Compliance
      - Service
  /dfr_rest_services.get_cwa_se_compliance:
    get:
      summary: Detailed Facility Report CWA SEV Compliance Service
      description: This procedure obtains data for the CWA Single Event Violations
        section of the DFR.
      operationId: this-procedure-obtains-data-for-the-cwa-single-event-violations-section-of-the-dfr-
      x-api-path-slug: dfr-rest-services-get-cwa-se-compliance-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - CWA
      - SEV
      - Compliance
      - Service
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---