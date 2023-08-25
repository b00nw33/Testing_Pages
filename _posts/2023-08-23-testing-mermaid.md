---
layout: post
title: "Testing Mermaid"
categories: misc
---

## Testing Mermaid

Changing `<code class="mermaid">` to check if it works here. Previously tested working on Minina clone, got diagram displayed but on purple background.

<pre><code class="mermaid">sequenceDiagram
Alice -&gt;&gt; Bob: Hello Bob, how are you?
Bob--&gt;&gt;John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long&lt;br/&gt;long time, so long&lt;br/&gt;that the text does&lt;br/&gt;not fit on a row.

Bob--&gt;Alice: Checking with John...
Alice-&gt;John: Yes... John, how are you?
</code></pre>