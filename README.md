# nextJsOrg
nextjs relies on DOM manipulation and React
DOM includes the updated page content

imperative = steps for how the user interface should be updated

declarative can be faster = ordering pizza without the recipe

React is declarative library of snippets ( UI trees and the render method sections in the React Documentation.)

To do React:

    <script src="https://unpkg.com/react@17/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@17/umd/react-dom.development.js"></script>

 in the project above the script! (html > react scripts > script)

Instead of directly manipulating the dom (append this  blah blah blah), just use ReactDOM.reder from react-dom to render that h1 FOR YOU, sib!

but ... javascript won't parse HTML so JSX is added to the broswer through the Javascript compiler, Babel, my dear Watson. JSX is that fake HTML in React scripts.

So Babel goes inthe scripts right under the React Scripts

 ## React
 components - functions that return UI elements. could be as simple as a function that creates an image in JSX (nesting, JSX looks like tags, capitalize them)
 props - Travel down the tree parent to child - an OBJECT of all the properties passed to a component, 
            object destructuring { aPropertyExample } //=>the value
            javascript expression is {} within JSX - it must evaluate to a single value (like a map or object or text or something)
                    it could be a returned value of a funciton {functionName(variable)} 
                        a template literal{`The best ${title}`}
                        an object property with dot notation
                        or a ternary operator // EX { isLoaded ? title : "...loading"}
 state -  the argument of useState is the inital value.  cosnt [] = is array destructuring
            Keep the logic for updating the state in the component of origin
            
