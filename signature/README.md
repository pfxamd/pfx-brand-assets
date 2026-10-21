# PFxamd Signature

Official source-code signature for PFxamd projects. Author: Ahmed.

## Approved template

```js
/**
 * ┌──────────────────────────────────────────────┐
 * │                                              │
 * │  PFxamd                                      │
 * │  Ahmed                                       │
 * │                                              │
 * └──────────────────────────────────────────────┘
 *
 * @project     PROJECT_NAME
 * @author      Ahmed
 * @brand       PFxamd
 * @website     https://www.pfxamd.com
 * @repository  PROJECT_REPOSITORY
 * @since       PROJECT_YEAR
 * @license     PROJECT_LICENSE
 */
```

## Application instructions

1. Read the target repository's current files and applicable instructions before applying this signature.
2. Preserve the approved identity, visual frame and field order. Do not add slogans or promotional text.
3. Replace PROJECT_NAME with the actual project name from its manifest or documentation, and PROJECT_REPOSITORY with its actual canonical repository URL.
4. PROJECT_YEAR means the verified year the project began, not the year this signature is inserted. Omit @since if the year cannot be verified.
5. Read the actual license files and applicable per-file notices. Use a verified license name or SPDX identifier for PROJECT_LICENSE; omit @license if no license is established. Never invent or assign a license. A signature does not grant a license.
6. Never leave placeholder values in project source files.
7. Adapt only the comment delimiters and line prefixes to the source language: block comments for JavaScript, TypeScript and CSS; HTML comments for HTML; # line comments for Python and shell; appropriate native comments for other languages. Do not insert comments into formats that prohibit them, including strict JSON.
8. Keep shebangs, encoding declarations, required directives and existing legal notices in their required positions. Preserve all third-party copyright and license notices.
9. Apply the full signature to the project's main source entry files within the requested scope. Do not add it indiscriminately to every file or to third-party, vendored, generated, minified, lock or binary files.
10. Do not claim Ahmed authored third-party code. Preserve project behavior and verify that the edited files remain valid.
11. Copy the signature into the target project; do not introduce a runtime network dependency on this repository.
12. Updating this reference does not automatically update signatures already copied into other repositories. Modify other repositories only when requested.

## Request example

Read https://github.com/pfxamd/pfx-brand-assets and apply the approved signature in signature/README.md to the requested project's main source files, using verified project metadata.
