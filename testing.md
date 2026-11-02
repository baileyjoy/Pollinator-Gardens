# Data Story Testing Record

## HTML Validation
- Tool: W3C HTML Validator
- Result: Passed with no reported errors.

## CSS Validation
- Tool: W3C CSS Validator
- Result: Passed with no reported errors.

## Responsive Layout
- Tested at: 320px, 768px, and 1280px.
- Result: Main content fit within the viewport. The data table could scroll horizontally on smaller screens.

## Browser Zoom
- Tested at: 200% zoom.
- Result: Content remained readable and usable.

## Image-Disabled Test
- Method: Temporarily changed the first image filename to a nonexistent file.
- Result: Alternative text appeared, and the caption remained visible.
- Revision: Restored the original image filename after testing.

## Code Defense

I reused CSS variables to maintain consistent colors,
spacing, and typography throughout the website.

The data table uses column and row headers to make the
information easier to understand. It also has a scrollable
container for smaller screens.

The SVG chart uses rectangles to represent bee counts,
with bar widths calculated at two SVG units per bee.
I corrected the SVG viewBox height after discovering that
the bottom two bars were being cut off.

I also added alternative text to photographs and an
accessible title and description to the SVG.

##AI Disclosure
I used ChatGPT to help understand the assignment requirements, and troubleshoot issues.