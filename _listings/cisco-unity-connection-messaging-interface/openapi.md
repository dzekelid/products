swagger: "2.0"
x-collection-name: Cisco Unity Connection Messaging Interface
x-complete: 1
info:
  title: Cisco PSIRT open Vuln
  description: the-cisco-product-security-incident-response-team-psirt-openvuln-api-is-a-restful-api-that-allows-customers-to-obtain-cisco-security-vulnerability-information-in-different-machineconsumable-formats--apis-are-important-for-customers-because-they-allow-their-technical-staff-and-programmers-to-build-tools-that-help-them-do-their-job-more-effectively-in-this-case-to-keep-up-with-security-vulnerability-information-for-more-information-about-the-cisco-psirt-openvuln-api-visit-httpsdeveloper-cisco-comsitepsirtdiscoveroverviewfor-detail-steps-on-how-to-use-the-api-go-tohttpsdeveloper-cisco-comsitepsirtgetstartedgettingstarted-gspthis-is-a-beta-release-of-a-swagger-yaml-for-the-cisco-psirt-openvuln-apito-access-the-api-sign-in-with-your-cisco-cco-account-at-httpapiconsole-cisco-com-and-register-an-applicationto-recieve-a-client-id-and-a-client-secretyou-can-then-get-your-token-using-curl-or-any-other-method-you-prefer-curl-s-k-h-contenttype-applicationxwwwformurlencoded-x-post-d-client-idyour-client-id-d-client-secretyour-client-secret-d-grant-typeclient-credentials-httpscloudsso-cisco-comastoken-oauth2you-will-receive-an-access-token-as-demonstrated-in-the-following-example-access-tokeni7omwtbdaiesiux3shoxnjfuy4j6token-typebearerexpires-in3599in-swagger-click-on-change-authenticationenter-the-text-i7omwtbdaiesiux3shoxnjfuy4j6-which-is-the-token-you-receivedthen-click-on-try-this-operation
  contact:
    name: Omar Santos
    email: os@cisco.com
  version: 0.0.3
host: api.cisco.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /security/advisories/cvrf/product:
    get:
      summary: Get Security Advisories Product
      description: Used to obtain all the advisories that affects the given product
        name.
      operationId: used-to-obtain-all-the-advisories-that-affects-the-given-product-name-
      x-api-path-slug: securityadvisoriescvrfproduct-get
      parameters:
      - in: query
        name: product
        description: An product name to obtain security advisories that matches given
          product name
      responses:
        200:
          description: OK
      tags:
      - Security
      - Advisories
      - Product
  /security/advisories/oval/product:
    get:
      summary: Get Security Advisories Oval Product
      description: Used to obtain all the oval advisories that affects the given product
        name.
      operationId: used-to-obtain-all-the-oval-advisories-that-affects-the-given-product-name-
      x-api-path-slug: securityadvisoriesovalproduct-get
      parameters:
      - in: query
        name: product
        description: An product name to obtain security advisories that matches given
          product name
      responses:
        200:
          description: OK
      tags:
      - Security
      - Advisories
      - Oval
      - Product