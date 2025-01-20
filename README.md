# Uncommon HTML Error: Misinterpreted < and > symbols

This repository demonstrates a common yet easily overlooked error in HTML: the misinterpretation of less-than (`<`) and greater-than (`>`) symbols within text content.  The browser may attempt to parse these symbols as HTML tags, even when they are intended to be part of the text itself. This can result in broken layouts, unexpected behavior, or even security vulnerabilities if the text is dynamically generated.

The `bug.html` file shows the erroneous code, while `bugSolution.html` provides a corrected version.  The key is to escape these symbols using their HTML entities: `&lt;` and `&gt;`, respectively.

This example illustrates the importance of proper input sanitization and escaping when handling user-supplied content or data fetched from external sources.