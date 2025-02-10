# Unexpected CSS Specificity Behavior

This repository demonstrates a subtle but important CSS specificity issue.  A pseudo-element's style unexpectedly overrides a class style, highlighting the need for careful consideration of CSS selector specificity.

## Bug Description

A class is expected to override the styles of a pseudo-element when both are applied to the same element. However, this example shows a scenario where the pseudo-element's style takes precedence, even when a more specific class selector is used. This is due to the way CSS specificity is calculated. 

## Bug Solution

The solution explains how the specificity issue arises and presents alternative approaches to achieve the desired styling behavior, prioritizing the class styles over the pseudo-element styles.