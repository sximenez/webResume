# 3. Web resume

✅ https://sximenez.github.io/webResume/


The ```idea``` is based on developer <a href="https://github.com/icelam/html-cv-poc">__Ice Lam__</a>'s work. 

I find his projects very inspiring and instructive.

Since I'm currently looking for an internship and I need to regularly update my resume, I decided to play with Lam's idea.

The ```html``` is divided in two pages, a first page with the resume containing a header with the main information, and three containers with detailed information.
And a second page with a cover letter.

On top of the documents, there's a simple button to convert the pages to pdf.

The ```css``` is based on Lam's project and tailored to the design I was looking for.

The ```js``` is Lam's work.

Interesting to learn the JS syntax to open the browser's print window:

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