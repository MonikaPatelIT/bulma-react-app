

## React application using Bulma CSS framework 

In this project I have created basic react app and used Bulma CSS framework 

To create react app,

`create-react-app bulma-react-app`

now to you have basic react application ready which you can see on localhost by running 

`npm start`

To add bulma css module from npm [https://www.npmjs.com/package/bulma](https://www.npmjs.com/package/bulma)

`npm i bulma` 

now import bulma into your APP.js file using 

`import 'bulma/css/bulma.css'`

In react we have to use 'ClassName' instead of 'class'

```

 <div className="App">
      <section className="hero is-primary is-medium">
        <div className="hero-head">
          <nav className="navbar">
            <div className="container">
              <div className="navbar-brand">
                <a className="navbar-item">
                  <img
                    src="https://bulma.io/images/bulma-type-white.png"
                    alt="Logo"
                  />
                </a>
                <span
                  className="navbar-burger burger"
                  data-target="navbarMenuHeroA"
                >
                  <span />
                  <span />
                  <span />
                </span>
              </div></div>
          </nav>
        </div>
        <div className="hero-body">
          <div className="container has-text-centered">
            <h1 className="title">Title</h1>
            <h2 className="subtitle">Subtitle</h2>
          </div>

          <div className="hero-foot">
          <nav className="tabs">
            <div className="container">
              <ul>
                <li className="is-active">
                  <a>Overview</a>
                </li>
                <li>
                  <a>Modifiers</a>
                </li>
                <li>
                  <a>Grid</a>
                </li>
                <li>
                  <a>Elements</a>
                </li>
                <li>
                  <a>Components</a>
                </li>
                <li>
                  <a>Layout</a>
                </li>
              </ul>
            </div>
          </nav>
        </div>
        </div>
      

        </section>
    </div>
    
```

This project made to answer [https://stackoverflow.com/questions/53127729/bulma-navbar-component-is-not-showing] (https://stackoverflow.com/questions/53127729/bulma-navbar-component-is-not-showing)
