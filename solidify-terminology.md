# How the Web Works

- What is HTTP?
  _Hypertext Transfer Protocol_
  It is an application layer protocol that facilitates the communication and transfer of data between clients and servers over the internet.

---

- What is a URL?
  _Uniform Resource Locator_
  It is a standardized address used to identify resources on the internet.

---

- What is DNS?
  _Domain Name System_
  It is a system used to translate human readable domains into an ip address.
  It allows for easier readability for users and a better user experience on the internet.

---

- What is a query string?
  It is used to pass additional information to a web server when requesting a specific resource.

---

- What are two HTTP verbs and how are they different?
  GET: Used to request data from a server.
  POST: Used to send data to a server or update resources.

---

- What is an HTTP request?
  A message sent by a client in order to request a particular resource or perform a specific action.

---

- What is an HTTP response?
  A message sent by a server in response to an HTTP request made by a client

---

- What is an HTTP header? Give a couple examples of request and response headers you have seen.

  Headers are metadata components that provide additional information about a request.

  - Example 1: Entity Headers: These headers provide information about the body of the message, such as its length, type, and encoding.
    <br>
  - Example 2: Request Headers: These headers are included in the client's request to the server. They provide information about the client's capabilities, preferences, and the content of the request.

---

- What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?

  - The browser uses DNS to turn the domain into an IP address. (If it finds a match it moves on to the next step)
  - The browser attempts to make a request to the IP address.
  - A response is sent (2xx, 3xx, 4xx, 5xx). A 200 signifies an "OK" response.
  - If the response is successful the DOM is created and the webpage is displayed.
