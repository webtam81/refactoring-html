# Refactoring HTML

## An exercise in refactoring HTML for accesibility

A web page has been refactored to make it more accesible and SEO friendly.

The purpose of this project to put into practice learning about HTML, CSS and semantics.

## Improvements

- Missing 'text/css' added to stylesheet tag.
- Changed DIVs with class 'header'/'footer' to header and footer tags respectively and adjusted corresponding accordingly.
- Changed class "seo" to "contrast-letters" as it's more semantic. Removed header selector for this in CSS so the class can be used elsewhere in the page too.
- Changed DIV and nested DIV tags to SECTION and ARTICLE tags.
- Changed page title to be descriptive.
- Created 'services-block' class to consolidate repeated CSS for each 3 service blocks.
- Created 'benefit-block' class to consolidate repeated CSS for each 3 benefit blocks.
- Side section made into aside.
- H2 in footer changed to P and given a class for styling. A heading in the footer is not appropriate in this situation as it's not heading anything.

## Usage

View on GitHub Pages here: [https://webtam81.github.io/refactoring-html/](https://webtam81.github.io/refactoring-html/)
    ```
## License

MIT License. See license file for further details.