UI: User Interface; what the user interacts with

UX: User Experience; what the user experiences

HTML: Hypertext Markup Language; HTML elements and constructs, which exhibit inheritance, compose the structure of a document that can be rendered by a web browser. Ideally, presentational & semantic HTML are in harmonious balance.

CSS: Cascading Style Sheets (style sheet language); dictates presentation of structural components using a hierarchical cascade of style inputs.  

CSS Selector Specificity: *universal < elements < .classes, :pseudo-classes, \[attributes\] < #IDs < inline styles < !important

Box Model: Content ] Padding ] Border ] Margin

Flexbox: A CSS module that enables responsivity for spatial presentation of components

CLI - Command Line Interface

Git - Distributed version control system

Web Design Layouts - 
    Fixed: no change in layout size/design across screen dimensions
    Fluid: elements shrink + grow proportionally to screen dimension changes
    Adaptive: breakpoints change layout at select screen sizes
    Responsive: combination of fluid sizing + breakpoints for optimally dynamic web design

LESS - Dynamic preprocessor style sheet language that can be compiled to CSS

JavaScript Variable Declation - 
    var: function scoped; mutable; allows variable redeclaration; depreciated
    let: block scoped; mutable; throws an error for duplicate declaration if you use same variable name twice; use for iterators & conditionals
    const: block scope; immutable

JavaScript Literals - 
    const objectLiteral = { key: "value", type: "pairs" }
        dot notation:      objectLiteral.key = "value"
        bracket notation:  objectLiteral\["type"\] = "pairs"
    const stringLiteral = "I am a string"
    const arrayLiteral = [1, 2, 3, "abc"]
    const booleanLiteral = true
    const integerLiteral = -120
    const floatLiteral = 2.4
    const templateLiteral = \`The average American family has ${floatLiteral} kids.\`

Closures - The combination of a function and the lexical environment within which that function was declared; a construct of scope that gives functions access to data defined in outer functions.

Callbacks - Callback functions are passed as arguments to higher-order functions to be invoked after the execution of the higher-order function.

`this` keyword in JavaScript - Provides a generalized reference to that changes based on its context and binding.
    Window binding: in the global scope, the value of `this` will be the window/console Object.
    Implicit binding: when a function is called by a preceding dot, the object before that dot is what `this` will refer to.
    New binding: when a constructor function is used, `this` refers to the specific instance of the object that is created and returned by the constructor function.
    Explicit binding: when JavaScript’s call or apply method is used, `this` is bound manually.

JavaScript `class` - syntactic sugar; special functions that return Objects; used in conjunction with `new` for instantiation.

DOM - Document Object Model; object representation of the html elements of a webpage;  takes the structure of a tree, with each html element being a node of the tree. DOM selectors include getElementById('id'), getElementByClassName('class'), querySelector('.class'), querySelectorAll('.class')

HTMLCollection & NodeList - array-like objects that are returned by DOM selectors. Both are zero-indexed with a length property; NodeLists has a forEach method.

Event Listeners - monitors for a specific type of event and dispatches a specified callback function when the event is detected.

JavaScript Component - a reusable unit of html, css, and javascript that improves the building process of elements with shared presentation and/or functionality.