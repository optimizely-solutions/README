# Code Promotion Process README
This README is designed to illustrate the code promotion process for the Optimizely Solutions organization.

11/2/2017

Author: Spencer Smitherman

## Purpose

This code promotion process was developed for two primary purposes:

1. Provide clarity across the organization on how custom code samples are supported and who supports the code samples.

2. Ensure that teams within Services and Success can create code samples and feel confident about audience exposure.

## Process

All code samples developed and pushed to the `optimizely-solutions` organization are considered semi-private. The repository the developer creates should be public so it can be shared with customers on an as needed basis. The code samples within this organization should be used with discretion since they are not officially supported by Optimizely. If you would like to use a code sample from this organization, then you should check with the original developer(s) first before sharing externally.

*Warning: Some of these code samples may break or cause problems with a customer's site!*

The code promotion process can begin once the following conditions have been met:

1. The code sample is QA'd
2. The code sample is reviewed for sufficient browser support (if client-side web)
3. Validated with at least one customer in production
4. The code sample should be *generalized* beyond a single customer use case.
5. The code sample is well documented and includes the following items.
 * Description
 * Use cases
 * Expected Behavior
 * Prerequisites
 * Implementation
 * Limitations
 * Support

NOTE: There is a template available below to help the developer(s) get started.

Assuming these conditions are satisfied, then the developer(s) can choose to upload this sample to any of Optimizely's public technical resources:

* Knowledge Base
* Addons Library
* Developer Documentation

The Technical Support Engineering (TSE) team is responsible for all externally-facing code samples. Before deploying the code sample to the above resources the developer(s) should facilitate at least one training session with members of the TSE team to ensure they can sufficiently support the code sample. In an ideal state, the developer(s) would also present to the Solutions Architect team as well to help socialize the solution further.

NOTE: The above process is designed to give future developers an outline of the custom code sample promotion process. There may be other steps which the developer must follow before completing a full promotion of their code sample. For example, it may be necessary to create a ticket with engineering to review a code sample that is deployed to the developer documentation.

## Code Support

Code samples living within the `optimizely-solutions` repository should be supported by the developer(s) who created them. Since many of these code samples may not work as expected it's important to handle them carefully especially when deploying them to customer applications.

Should a code sample become "orphaned" when someone leaves the team/company, then another person is welcome to take ownership of the code sample. There is no obligation on the original developer(s) to transfer ownership of code samples within `optimizely-solutions`.

Once the code sample is promoted beyond this organization, then the TSE team is responsible for identifying problems with the code via customer feedback and helping fix the solution. The Solutions Architect team and ADEPT will serve as escalation points should the code sample prove to be too difficult to fix.

---

## Documentation Template

### Description

### Use Cases

### Expected Behavior

### Prerequisites (if any)

### Implementation

### Limitations

### Support

If you have questions about this integration or if you're experiencing unexpected behavior, please submit a support ticket via the Help menu on the left side of the Optimizely Dashboard.
