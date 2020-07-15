Some ideas for sites:

**What is this?/מה זה?**:<br>
For example if someone looks for a term in a search engine followed by **Whats this?**, the first result will be our site explaining the term.
The site will be open source just like wikipedia.

Lingo.js:
An event driven DOM parser for js that will parse the DOM more efficaintly.
It will use JQuery for DOM parsing and Vue.js for the element driven system and will combine them toghether so no need for noConfilcts and importing two libraries.
It will parse the DOM and change it using Vue so no need to break your head over it.
also it will take care of popular actions such as documnent.ready() or document.addEventListener('load',function () {}) will be dl(function() {}) also it will change the code form 
to python style.
Here is some code i wrote:
class Lingo {
    constructor(element,data){
        this.element = element;
        this.data = data;
    }
    showDataEntries() {
        const entries = Object.entries(this.data)
        for (const [key, value] of entries) {
            alert(`Key: ${key} | Value: ${value}`)
        }
    }
}

var lingo = new Lingo("ds",
{
    d:'text',
    v_lingo:'ds'
}
)

lingo.showDataEntries()
