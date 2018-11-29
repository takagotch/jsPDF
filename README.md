### jsPDF
---
https://github.com/MrRio/jsPDF

```
<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/1.4.1/jspdf.debug.js" integrity="sha384-XXX/XXXXXXXXXXXXXx">

<script src="http://unpkg.com/jspdf@latest/dist/jspdf.min.js"></script>
```

```
yarn add jspdf
npm install jspdf --save

import * as jsPDF from 'jspdf'
import jsPDF from 'jspdf';
meteor add jspdf: core
```

```js
var doc = new jsPDF()
doc.text('Hello', 10, 10)
doc.save('a4.pdf')

var doc = new jsPDF('Hello', 1, 1)
doc.text('Hello', 1, 1)
doc.save('two-by-four.pdf')
```
