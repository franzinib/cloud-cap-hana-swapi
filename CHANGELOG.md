# Change Log

All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](http://keepachangelog.com/).

## [1.1.10] - 2023-04-07

**Changed**

- SAP CAP updated to 6.7 March 2023 Rel
- SAPUI5 update to 1.112.1
- Add dev dependency to [new SQLite Service](https://cap.cloud.sap/docs/releases/march23#new-sqlite-service)
- Changed to [cds-serve command](https://cap.cloud.sap/docs/releases/march23#change-your-start-script-to-cds-serve)

## [1.1.8] - 2023-02-28

**Changed**

- SAP CAP updated to 6.6 Feb 2023 Rel
- Fixes in the convertData to avoid issues with parallelization and DB constrains
- SAPUI5 update to 1.111.0

## [1.1.5] - 2022-12-19

**Changed**

- SAP CAP updated to 6.4 Dec 2022 Rel
- Switch to @cap-js/graphql [Open Source GraphQL Adapter](https://cap.cloud.sap/docs/releases/dec22#open-source-graphql-adapter)
- SAPUI5 update to 1.109.3

## [1.1.5] - 2022-11-28

**Changed**

- SAP CAP updated to 6.3
- SAPUI5 update to 1.108.2
- New Node.js minimal version is 14.18

## [1.1.4] - 2022-08-11

**Changed**

- SAP CAP updated to 6.1
- SAPUI5 update to 1.105.0
- Kyma Helm Charts updated for new functionality in CAP 6.1

**Added**

- Update to SAP Cloud Application Programming Model 6.0.x - Yearly Major Release
- Add Support for Node.js 18.x
- Added Helm Charts support for deployment on Kyma/K8S

## [1.1.0] - 2022-07-05

**Changed**

- GraphQL support is now GA by switching to the @sap/cds-graphql dependency.  Removal of old GraphQL dependencies.
- Remove Support Node.js 12.x, minimal version now 14.15 as enforced by @sap/cds itself
- SAPUI5 update to 1.103.0

**Added**

- Update to SAP Cloud Application Programming Model 6.0.x - Yearly Major Release
- Add Support for Node.js 18.x
- Added Helm Charts support for deployment on Kyma/K8S

## [1.0.7] - 2022-04-14

**Changed**

- Dark Theme loading optimization thanks to [Marian Zeis](https://github.com/marianfoo) [PR #4](https://github.com/SAP-samples/cloud-cap-hana-swapi/pull/4)

**Added**

- Added async bootstrap for UI5 in preparation for [Patch-Level Independent Bootstrap](https://blogs.sap.com/2022/04/14/sapui5-patch-level-independent-bootstrap) - although I couldn't switch yet as it doesn't seem to work for version 1.100

## [1.0.6] - 2022-03-30

**Changed**

- Update to [CAP March 2022 5.9](https://cap.cloud.sap/docs/releases/mar22)
- Update to [SAPUI5 1.100](https://sapui5.hana.ondemand.com/1.100.0/#/topic/5deb78f36022473487be44cb3a71140a)
- Reactivated experimental GraphQL support. Use from test application with /graphql
- [People App](/people/webapp/index.html) now uses OS setting and adjusts to dark theme - new sap_horizon_dark

**Added**

- New Changelog - You are looking at it
- [Database Integrity Constraints](https://cap.cloud.sap/docs/releases/mar22#database-integrity-constraints)
- People Entity Name Attribute Fuzzy Search via [Native Database Clauses](https://cap.cloud.sap/docs/releases/mar22#native-database-clauses)
- New tallestPerson view uses [Native HANA Functions with non-standard syntax](https://cap.cloud.sap/docs/releases/mar22#native-hana-functions-with-non-standard-syntax)
