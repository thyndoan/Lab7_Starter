Name: Thy Doan

**Q1:** Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

**A**: Within a Github action that runs whenever code is pushed. Because we need the tests to run automatically on every push within a Github action so that bugs are caught immediately. This ensures that no broken, buggy code can reach the main branch.

**Q2:** Would you use an end to end test to check if a function is returning the correct output? (yes/no)

**A:** No, we use unit tests to test individual function outputs not E2E test.

**Q3:** What is the difference between navigation and snapshot mode?

**A:**

- Navigation Mode will reload the page and analyze the page from scratch. This measures overall performance. We should use this to test how the page performs when someone first visits the page.
- Snapshot Mode will analyze the page as it is right now without reloading the page. This mode can't measure load performance, but we should use this when we need to test specific issues in the current page.

**Q4:** Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

**A:**

From the Navigation mode and snapshot mode, we can improve 1 and 2. From timespan mode, we can improve 3.

1. Add lang="en" to fix accessibility
2. Add meta description to fix SEO
3. Add viewport meta tag to fix performance, optimize viewport for mobile, and potentially save 240ms.
