## Getting Started with Create React App


2.	List five significant features of React.
    a.	Virtual DOM
    b.	JSX - JavaScript Syntax Extension
    c. 	Debugging
    d.	Extensions
    e.	One-way data binding


3. 	List five major advantages of React.
    a.	Reusable components
    b.	React is easy to learn
    c.	Improved performance
    d.	Development of both web and mobile apps
    e.	Easy creation of dynamic applications


4.	What is the name of the Software Engineer that created React? Also, which company owns React?
    Jordan Walke, 
    React is owned by Meta (Formerly Facebook)


5.	What are the notable differences between HTML & JSX? Give at least 3 of them.
    A.	One of the major differences between HTML and JSX is that in JSX, you must return a single parent element, or it won't compile.

    B.	In JSX, it is possible to write JavaScript directly. You can do this by putting the JavaScript in curly braces {...}. 
        Whereas in HTML, you need a script tag or an  external JavaScript file to implement JavaScript.

    C.	Tags can self-close in JSX. That is, it is possible to have (<div></div> as <div /> and <span></span> as <span />). You don't want to do that, but it’s possible.
        Self-closing tags in HTML can self-close without the slash before the right angle bracket, that is <br /> could work as <br>. But in JSX, you need to include the slash. This should bring something to mind – JSX heavily relies on HTML 4 syntax.



6.	Why can’t browsers read JSX?
    Because JSX is not valid JavaScript, browsers can't read it directly; they do not know what to do with it, so we need a transpiler to translate it to React.
    JSX is not a valid JavaScript as they are embedded in HTML elements. As JSX is combination of HTML and JavaScript it is not supported by Browsers. So, if any file contains JSX file, Babel transpiler converts the JSX into JavaScript objects which becomes a valid JavaScript. Thus, browsers understands the code and executes. Browsers can’t read JSX because there is no inherent implementation for the browser engines to read and understand them. JSX is not intended to be implemented by the engines or browsers, it is intended to be used by various transpilers to transform these JSX into valid JavaScript code.


