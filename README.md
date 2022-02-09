# README

1. Start server, visit root path and open browser console
3. Click on a number (e.g. 50), page jumps, no request
4. Reload page with that anchor (e.g #ctn_50)
5. All further navigations to that anchor (at the top or in the h1) result in a turbo XHR fetch

5.1. Clicking a different anchor results in no fetch
5.2. Clicking the anchor that was present on page load again WILL result in fetches
