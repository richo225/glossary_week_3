# Week 3 Glossary

## Projects covered

* Intro to the Web

## Web terms

* **HTTP** => How clients and servers talk to each other. Client makes a request to a server. Server sends back a response. HTTP has a defined structure for these.

* **HTTP parameters** => Key-value pairs that are passed to a server via a query string (http://path?key=value)

* **HTTP methods** =>

* **Sinatra** => Web framework. Turns your computer into a local server that can receive and respond to HTTP requests.

* **Routes** => These are ruby methods containing a block that is called every time an HTTP request matches the given route pattern. For example, sending a request using the "/intro" path would match this route below and so the route would be activated, displaying the intro message.

```
get "/intro" do
  #display intro message
end
```
* **Selenium** => Automates browsers/web apps so they can be tested.

* **Capybara** => Add on to RSpec to compose instructions. Simulates how a real user would interact with the server.

* **Automated browsers** => Can receive instructions programmatically.

* **ERB** => A template language that allows you to embed ruby code with HTML code.

```
I am <% 46/2 &> years old!
```
* **Global variables** => Never use them. Bad news!

* **Controller** => Receives HTTP requests and calls the appropriate action based on matching routes .eg. our /app.rb file.

* **Model layer** => Handles the complex OOP/data actions the controller sends it. In the battle app, the model layer consists of Class.rb files stored in the /lib folder.

* **Separation of concerns** => 
