# Compatibility Testing Report

## Project
Basic Web Page Compatibility Testing

## Website Tested
https://shoplane-by-lassie.netlify.app/

---

## Browsers Tested

- Google Chrome
- Mozilla Firefox
- Microsoft Edge

---

## Devices Tested

- Desktop
- iPhone
- Samsung Galaxy

---

## Test Results

| Feature | Chrome | Firefox | Edge | Mobile |
|-------|-------|-------|------|------|
| Homepage Load | Pass | Pass | Pass | Pass |
| Navigation Menu | Fail | Fail | Fail | Fail |
| Search Function | Fail | Fail | Fail | Fail |
| Add to Cart | Pass | Pass | Pass | Pass |
| Login | Pass | Pass | Pass | Pass |

---

## Issues Found

1.## Broken Links

When clicking the navigation menu items "Clothing" and "Accessories", the website displays a "Page not found" (404 error) message.

This indicates that the links are pointing to pages that do not exist or are not properly configured.

Recommendation:
Create valid pages for the navigation links or update the routing paths to ensure the links direct to the correct sections. 

2.## Functionality Issues

Search Bar Issue:
The search bar is visible on the homepage; however, entering a query and pressing the search button does not produce any results.

Observation:
The search functionality appears to be non-functional and may not have been implemented.

Recommendation:
Implement JavaScript-based search functionality to filter and display products based on user input.

3.Minor Issue:
On smaller mobile screens, product images appear slightly large which may require responsive image optimization.

---

## Recommended Fixes

- Use responsive CSS media queries
- Test UI using Flexbox/Grid
- Optimize images for mobile devices
- And above faults must be fixed

---

## Conclusion

The website is mostly compatible across browsers and devices with minor UI issues.



