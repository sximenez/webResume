# 3. Web resume

✅ https://sximenez.github.io/webResume/


The ```idea``` is based on developer <a href="https://github.com/icelam/html-cv-poc">__Ice Lam__</a>'s work. 

I find his projects very inspiring and worth studying.

Since I was looking for an intership at the time of the project and needed to update my resume, I decided to tailor Lam's project to my needs.

The ```html``` has a button to convert the resume to pdf, a header with the main information, and three containers with detailed information.

I added a second page for a cover letter.

The ```css``` is based on Lam's project and tailored to the design I was looking for.

The ```js``` is Lam's work. 

Interesting to learn the syntax to open the browser's print window:

```Javascript
function showPrintDialog() {
      try {
        document.execCommand('print', false, null);
      } catch {
        window.print();
      }
    }

    (function () {
      if (window.print) {
        document.querySelector('#print-button').style.display = "initial";
      }
    })();
```