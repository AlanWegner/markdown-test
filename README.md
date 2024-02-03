<!-- HEADINGS -->

# my title
## my second title h2
### my title h3
#### my title h4
##### my title h5
###### my title h6

<!-- italic -->
this is an *italic* text

<!-- strong -->
this is an **strong** text

<!-- strikethrough -->
this is an ~~texto~~ tachado


<!-- UL -->
* apple
    * apple 2
* orange
* etc

1. apple
2. orange
3. etc


[faztweb.com](http://www.faztweb.com)

[faztweb.com](http://www.faztweb.com "Custom title")

> this is a quote

---

___

`
console.log("hello world")
`
``` javascript
const mongoose = require('mongoose');

mongoose.set('useFindAndModify', false);
mongoose.connect('mongodb://localhost/node-notes-db', {
    useCreateIndex: true,
    useNewUrlParser: true
})
 .tech(db => console.log('DB is connected'))
 .catch(err => console.error(err));
```

```python
print("hello world")
```

```html
<h1>helloworld</h1>
```

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

![visual studio code logo](https://repository-images.githubusercontent.com/657248114/d3c7b91a-b285-4d1e-8429-5de1acc5f61e "vscode logo")

:satisfied: :smiley:

<!-- GITHUB MARKDOWN -->
* [x] Task 1
* [ ] Task 2
* [ ] Task 3
* [x] Task 4
