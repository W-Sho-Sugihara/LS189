LS189 Interview Assessment Mock Questions

# Mock Interview Questions

- What is HTML?

- What is CSS?

- What is Sinatra?

- What is Rack?

- What is a Web Server? (eg. Apache, Nginx? aka: reverse proxy servers when used in conjunction with Puma, Thin, Unicorn)

- What is an application server? (aka web application server, eg. Thin, Puma, WeBrick)

- What is a web application?

- What are static assets?

- What are dynamic assets?

- What is ERB?

- What is an ERB layout?

- How is an ERB layout used within an ERB invocation?

- What is AJAX?

- What is XMLHttpRequest (XHR)?

- What is escaping html? How do we incorporate it within our program? Why is it important?

- What is Bcrypt and how does it work?

- How does Bcrypt evaluate whether a password is valid or not?

- What is a session? How do you enable it? How do you use it?

- What is a session secret? Why is it important and how do we set it?

- What is a cookie and why are they used?

- What is persistence?

- What is `params`? What does it store?

- What are view helpers and when and why are view helpers used in Sinatra?

- What are view variables? Why are they important and how are they used?

- What is a Sinatra route?

- What does a `:` within a route pattern mean? What is its functionality?

- What is SQL injection? How do we prevent it?

- What is the `exec_params` method and how does it works?

- Explain what is happening in the following code, `erb :home`.

- Explain what is happening in the following code, `redirect '/home'`.

- What is the `env` hash and why is it important?

- What is the `call` method within Rack compliant applications and why is it important?

- What is SQL?

- What three values must be returned by the call method of a Rack application which describes the response sent to the client?

- Which route can be used to process routes that are not explicitly defined within the application?

- How does Sinatra tell the browser to redirect to a new page?

- What kind of request does the browser make for the new page when handling a redirection.

- What is the benefit of a multi-threaded web server?

- What is the purpose of the `configure` method within Sinatra?

- What are resource-based routes and why are they useful?

- Why is it a good idea to reload the current view rather than redirect after an error?

- Why are params cleared and all instance variables reset after a redirect?

- Why is it important to escape user input within a web application?

- What method can Sinatra use to escape html? (not the automatic html escape setting by the erubis gem `set :erb, :html_escape => true`)

- Your application has a form that the client uses to send a GET HTTP request. Where in the request will the form input values go?

- Are there any significant security differences between GET and POST requests?

- When should you use GET requests vs POST requests? why?

- Within a Sinatra application, you want to display a particular kind of file to the client. Which Sinatra helper method can you use to do this?

- From within a route, which method call accesses the application environment settings?

- List two ways to short-circuit a route in Sinatra.

- Why is it dangerous to allow raw filenames as request parameters?

- What happends when a client sends a request to the server? (in a broad sense of client -> web server -> app server -> web application then back to client)

- How do we prevent erb templates from being escaped when we are globally escaping html within the `configure` method and using a layout?

- What are some ways that we can optimize the way an application interacts with a database?

- What do we mean by an n + 1 query and why is it bad? How do we avoid it?

# Possible Project Question

- Why did you choose the project that you did?

- Explain the cardinality of your relationship(s).

- Explain the modality of those relationships.

- What were some difficulties you faced while designing your DB and app?

- What were some difficulties you faced while executing your design?

- What were some changes that you made allong the way? How did your project evolve?

- How did you impliment persistence within your app? (eg. user staying logged in)

- Did you use the configure method? What did you use it for and why?

- In what ways did you use sessions?

- What were some challenges you faced when querying data from the DB to be later displayed on your app?

- Did you use any custom classes (other than database_persistence)? What were their uses?

- What kind of values did your methods from '@storage' or from your database_persistence class return? single values, hashes, custom class obj's, arrays, etc? why did you choose the return value type that you did?

- Continued from previous question: If you could make changes would you change the return value format or keep your methods the same?

- How did you fulfill the requirement to return to the initial url if the current user wasnt logged and needed to log in first?

- Knowing what you know now, how would you have done your project differently?

- Knowing what you know now, what wouldn't you change about your app? What do you think you did well?

- Did you include user id's (or something similar) within the URL? why or why not?

- How was your experience with validation? Did you find it difficut or easy dealing with all the needed validations for form inputs and URL requests? why or why not?

- How did you implement pagination?

- Did you have any difficulties deciding between when to reload current page vs when to redirect?

- Why did you choose path `/xxx/aa/yyyy/:bbb` for this GET route?

- Why did you choose path `/xxx/aa/yyyy/:bbb` for this POST route?

- Will this path '/zzz/yy/bbb/aaaa' match this your '/zzz/zz/bbb/aaaa' path? Why or why not?

- How did you go about validating user login? Explain all methods and paths needed for password validation.

- Did you impliment encryption, AJAX or any other functionality not required within the project? How was your experience with them? Why did you choose to use them?

- Did you forget to add any gems to your gemfile upon submitting your project? Why do you think it can be easy to do so?

- Did you learn anything new while creating your app?

- Was there anything that you had previously learned that you now have a better understanding of because of the project?

- Was there anything you learned after submitting your project and received feedback?

- How was your experience using static assets? What did you use and why?

- Did you use tests during your project? why or why not?

- Were there any challenges while optimizing your database queries? What were they and how did you ovecome them?

- Did you use any dynamic views? (content changes depending on the route or variable) If so, how did you go about doing so?

- Was there a specific focus of your project? Something that you personally wanted to accomplish other than the project requirements?

- What part of the project was most frustrating or unenjoyable for you?

- What part of the project was the most fun for you?

- Understand which routes handle different types of requests and be able to
  trace the flow of a given request in and out of your application. Be able
  to explain what is happening every step of the way.
