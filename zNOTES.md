
FILE index.js
    contains a method CALL "render":
        ReactDOM.render(<App />, document.getElementById('root'));

FILE App.js
    contains    App component class
                method render() {}
                method CALL "return"

FILE ExampleComponent.js
    contains    ExampleComponent component class
                method render() {}
                method CALL "return"

FILE TestComponent.js
    contains    TestComponent component class
                method render() {}
                method CALL "return"




==============================

ORIGINAL in FILE src/App.js ( from inside the tag     <header className="App-header"> )

                {moment().format('MMMM Do YYYY, hh:mm:ss a')}
 
REPLACED with:  'Now'
