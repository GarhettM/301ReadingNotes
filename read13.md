The `<form>` element defines how the data will be sent. All of its attributes are designed to let you configure the request to be sent when a user hits a submit button. The two most important attributes are action and method.

The `action` attribute defines where the data gets sent. Its value must be a valid relative or absolute URL. If this attribute isn't provided, the data will be sent to the URL of the page containing the form — the current page.

When specified with no attributes, as below, the <form> data is sent to the same page that the form is present on <--- this is how I've always thought html worked till now.

The `GET` method is the method used by the browser to ask the server to send back a given resource: "Hey server, I want to get this resource." In this case, the browser sends an empty body. Because the body is empty, if a form is sent using this method the data sent to the server is appended to the URL.

After the submit button is clicked the `GET` URL will appear in the browser address bar.

The `POST` method is a little different. It's the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request: "Hey server, take a look at this data and send me back an appropriate result." If a form is sent using this method, the data is appended to the body of the HTTP request.

https://developer.mozilla.org/en-US/docs/Learn/Forms/Sending_and_retrieving_form_data

Go to the above link to review.