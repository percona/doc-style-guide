# Release notes structure guidelines

The release notes filename should follow the [file naming guidelines](file-naming-SEO.md).

## Title

| Section | Section guidelines | Example |
|---|---|---|
| Title | Product name and version number (YYYY-MM-DD) | Percona Server for MongoDB 5.0.11-10 (2022-09-01) |

### Required sections

These sections can be included in the release notes. If you do not have content for these sections, add either "None for this release" or "<this product> has not changed since the previous release." 

The required sections are:

| Section name | Description |
|---|---|
| Date <br> Install <br> Download | The release date, and links to the product installation doc and the Percona download page |
| Product blurb | No heading required. <br> Based on our Marketing material, this section is a general description of the product benefits. Has information about our professional services. |
| Release highlights | **Voice: Active, Present** <br> Added features in this release from Percona. <br>A list of features that are now GA as of this release. <br> A list of features that are tech preview <br>A general description of the upstream release notes, including a link. <br> Information about deprecated or removed items. <br>If this is a CVE release, include the following text:<br>This release fixes the security vulnerability CVE<number>. <br> Add a link to the CVE page that documents this fix.|
| Bug fixes | **Voice: Active, Past** <br>A list of bug fixes with links to the Jira ticket. <br>Begin the summary with a past-tense verb. <br> Do not repeat "Fixed".
| Useful links | GitHub location <br> Contribute to documentation |

### Optional sections

Use sentence-style capitalization for headings
Use unordered bullet lists for items within a section. If there is only one item, show the item as regular text.

The following sections are optional:

| Optional sections | Description |
|---|---|
| New features | **Voice: Active, present** <br> New features added by Percona. |
| Improvements | **Voice: Active, present** <br> Improvements to existing features |
| Deprecated and removed | **Voice: Active, present** <br> Items that are deprecated or removed in this release. |
| Platform support | **Voice: Active, present** <br> The platforms that are no longer supported or added to support. List only the relevant information.  |
| Documentation changes | **Voice: Active, present** <br> Additions or updates of significant content to the documentation.|
| Known issues | **Voice: Active, present** <br> Workaround methods for issues.|

## Format

Use sentence-style capitalization for headings.

Use unordered bullet lists for items within a section.

If there is only one item, show the item as regular text.

