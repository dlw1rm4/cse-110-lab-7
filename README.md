# CSE 110 Lab 7
### Names: Kaitlyn Nguy, Adithya Gundlapalli

---
1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

**Within a Github action that runs whenever code is pushed**
Manually run them locally before pushing code
Run them all after all development is completed

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

**No**

<img width="1710" height="985" alt="Screenshot 2026-05-19 at 11 29 00 AM" src="https://github.com/user-attachments/assets/2c13ed1f-678d-42bc-a617-2fce3d00938a" />


3) What is the difference between navigation and snapshot mode?

**Navigation mode loads the page like a normal visitor and measures load-time performance. Snapshot mode takes a static “picture” of the page as it is right now and checks structure and accessibility, but it does not measure page-load or runtime performance.**

4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

  1. Make images by using thumbnails or new formats like WebP or AVIF. You can also use srcset so the browser downloads only what it needs. This makes the page load faster.
  2. Reduce things that block the page from loading. Only put important CSS directly on the page. This way the page becomes usable quicker. The Total Blocking Time goes down.
  3. Make the page more accessible. Ensure labels are clear. You can see which item is selected using a keyboard. This helps people using keyboards or screen readers. Improves the Accessibility score.
