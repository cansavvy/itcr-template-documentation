# Well-Documented Software Checklist

This checklist is meant to help you evaluate and create documentation for your tool.
Each major section has links to the chapter that discusses the section in-depth as well as a link to a template doc that you can use to develop your own documentation while following a long with the course chapters.

- [ ] The “why” of this tool is obvious on the [main page](Link to chapter that describes this).

## [Getting Started](https://jhudatascience.org/ITCR_Documentation_and_Usability/creating-a-smooth-getting-started-section.html)
[Download a template document for a Getting Started section](https://raw.githubusercontent.com/jhudsl/itcr-template-documentation/master/docs/getting_started_template.md)
- [ ] Is easy to find: clearly visible on the main page.
- [ ] Provides the user with the introductory concepts of the tool.
- [ ] Has clear steps for installation.
- [ ] Dependencies are made clear.
- [ ] Directs the user to the How-to Examples section.

## [How-to Examples/Vignettes](https://jhudatascience.org/ITCR_Documentation_and_Usability/creating-helpful-how-to-examples.html)
[Download a template document for a How-to Example](https://raw.githubusercontent.com/jhudsl/itcr-template-documentation/master/docs/how_to_examples.md)
- [ ] Is easy to find: clearly visible on the main page.
- [ ] Demonstrates examples that are the most common use case(s).
- [ ] Prerequisite knowledge needed is described.
  - [ ] Links to helpful background knowledge resources are included.
- [ ] Paste-able or directly runnable code is given and can be run as-is.
- [ ] Demonstrates a _reproducible_ example.
  - [ ] An example dataset needed is provided and introduced.
  - [ ] No additional packages and software are required beyond what is installed in the `Getting Started`.

## [Reference Guides](https://jhudatascience.org/ITCR_Documentation_and_Usability/creating-handy-reference-guides.html)
[Download a template document for a Reference Guide](https://raw.githubusercontent.com/jhudsl/itcr-template-documentation/master/docs/reference_guide_template.md)
- [ ] Is easy to find: clearly visible on the main page.
- [ ] Is searchable or at least visually easily able to be scanned.
- [ ] All items are described in clear language:

### Command line tool items
  - [ ] All functions are described.
  - [ ] All arguments of those functions are described.
  - [ ] All parameters are described and defaults explained.
  - [ ] Any additional datasets or items included in the package are documented.
  - [ ] Any input file formats are described (example file format included is ideal).
  - [ ] Any output file formats are described.

### GUI tool items
  - [ ] All buttons are described.
  - [ ] All parameters are described and defaults explained.
  - [ ] Any input file formats are described (example file format included is ideal).
  - [ ] Any output file formats are described.

## [Code documentation](https://jhudatascience.org/ITCR_Documentation_and_Usability/creating-clarifying-code-comments.html)
- [ ] The code has a healthy amount of comments -- particularly in places where the code is “quirky.”

## [Feedback](https://jhudatascience.org/ITCR_Documentation_and_Usability/obtaining-user-feedback.html)
- [ ] The user is given a clear avenue of where to direct questions or report bugs.

## Overall items
- [ ] No broken links.
  - [ ] Implement a way to get an alert about broken links.
- [ ] The documentation has been kept up to date with any updates to the code.
- [ ] Visuals are used to clearly communicate complicated concepts where possible.
