# Accessibility Code Refactor

I was given a website for a marketing agency and tasked with refactoring it to meet accessbility standards.

To complete this task, the following issues needed to be addressed:
* Everything was a div.  I replaced everything with best practice semantic tags.
* The HTML had a number of unecessary classes, which I removed.  The relevant CSS stylings were refactored to use the new semantic tags.
* Several redundant CSS styling rules were consolidated.
* None of the img tags had alt attributes.  I added descriptive alt attributes to each img element.
* I updated the title element to something more descriptive than "website".
* I added commenting to the document, which was heretofore devoid of it.
* I ensured all header elements followed in sequential order.
    * Since the sidebar only used h3, I added an h2 at the top.  This simultaneously fixed the header situation and made the sidebar as long as the main section.

## View the page here:
> https://nvanbaak.github.io/code-refactor/