# GoogleDrive blocked file download


1.Open the document of interest

2.Right-click and select "Inspect element" to open the browser's developer tools.

3.Press Ctrl + R to refresh the page.

4.In the developer tools panel, go to the "Network" tab and filter the results by "img".This way, you will get individual pages as images, with a default size of 800px on the shorter side, that can be modified in the code.

5.Load the entire document by scrolling down with the "Page Down" key until the number of results in the "Network" tab matches the number of pages in the document.
Then, switch to the "Console" tab and inject the code.
