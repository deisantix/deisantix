# deisantix.js

```js

const deisantix = {
    name: ['Ytalo', 'Ethan'],
    pronouns: ['he/him', 'ele/dele'],
    from: Brazil,
    
    languages: [Python, Java, HTML, CSS, JavaScript],
    learning: [VueJs, Sass, MySql, Delphi],
    
    hobbies: [cartoons, movies, books, walking],
    sports: null,
    
    speak: function() {
        return 'portuguese' || 'english';
    },
    procrastinate: function() {
        alert("Just one more minute...");
    },
    study: function() {
        alert("I'm studying" + this.learning);
    }
}

if(Date.time > 0) {
    deisantix.procrastinate();
} else {
    deisantix.study();
}
```
