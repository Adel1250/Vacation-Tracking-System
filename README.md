# Vacation Tracking System

## 1. Requirements

### 1.1 Vision

A **Vacation Tracking System** (VTS) will provide individual employees with the
capability to manage their own **vacation time**, **sick leave**, and **personal time off**, without having to be an expert in company policy or the local facility’s leave policies.

The main goal of this application is to **improve the internal business processes** of this organization, at least with respect to the time it takes to **manage vacation time requests**.

### 1.2 Functional Requirements

+ Implements a flexible **rules-based system** for validating and verifying leave time requests.

+ Enables **manager approval**.

+ Provides **access to requests** for the previous calendar year, and allows requests to be made up to a year and a half in the future.

+ Uses **e-mail notification** to request manager approval and notify employees of request status changes.

+ Uses existing hardware and middleware.

+ Is implemented as an extension to the **existing intranet portal system**, and
uses the **portal’s single-sign-on mechanisms** for all authentication.

+ Keeps **activity logs** for all transactions.

+ Enables the HR and system administration personnel to **override all actions restricted by rules**, with logging of those overrides.

+ Allows managers to **directly award personal leave time** (with system-set limits).

+ Provides a **Web service interface** for other internal systems to query any given employee’s vacation request summary.

+ Interfaces with the **HR department legacy systems** to retrieve required employee information and changes.
