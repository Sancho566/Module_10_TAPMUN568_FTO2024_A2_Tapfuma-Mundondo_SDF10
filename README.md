## [SDF10] API Learning Reflection 🧠

Welcome to the [SDF10] API Learning Reflection! Through this exercise, you will reflect on key concepts, practical experiences, and the tools you've encountered or used in API interactions.

1. **Understanding and Application**: Reflecting on the key concepts, can you explain in your own words what an API is and its significance in software development? Provide an example of how you have used or encountered an API in a project or a practical scenario.
   
-APIs play a pivotal role in software engineering by promoting modularity, interoperability, standardization, scalability, ease of development, and third-party integration. They serve as the building blocks for creating robust, flexible, and extensible software systems.

-I wanted to display current weather information for various locations. Intead of manually collecting data for each location, I used a weather API to retrieve this information automatically.

e.g GET https://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=Cape+town.

2. **Conceptual Distinctions**: How would you differentiate between an interface and an API?
 
 -While both APIs and interfaces define how software components interact with each other, an API typically refers to a broader concept that encompasses protocols, rules, and tools for building software applications, whereas an interface refers more specifically to a contract specifying the methods and properties that a component must implement.

3. **Components and Types of APIs**: Can you identify the main components of an API and describe their roles? Reflect on the different types of APIs mentioned (e.g., Web APIs, RESTful APIs) and discuss which type you find most intriguing or useful, and why.
 
Main components of API:

(a)Endpoints: Endpoints are specific URLs or URIs that are used to access different functionalities provided by the API. Each endpoint represents a unique resource or action that can be accessed or performed through the API.
(b)Request Methods: APIs support different HTTP request methods, such as GET, POST, PUT, DELETE, etc. These methods determine the type of operation being performed on the resource identified by the endpoint. For example, GET requests are used to retrieve data, while POST requests are used to create new data.
(c)Parameters: Parameters are additional pieces of information that can be included in API requests to customize the behavior of the request or filter the results returned by the API. Parameters can be sent as query parameters in the URL, as headers, or in the request body for POST and PUT requests.

Which type you find most intriguing or useful, and why?
 
-RESTful APIs are a specific type of web API that follows the REST architectural principles. Whether a RESTful API or another type of web API is more useful depends on the specific requirements of your project, as well as factors such as simplicity, scalability, performance, and compatibility with existing systems. RESTful APIs are popular due to their simplicity, scalability, and widespread support, but the choice of API style ultimately depends on the needs and constraints of your application.

4. **Practical Application and Tools**: Reflect on your experience with API exploration and implementation. Have you used any specific tools (such as Curl or API exploration tools) or libraries to interact with APIs? 

I have used curl, I wanted to make a GET request to the OpenWeatherMap API to fetch the current weather information for a specific city.

e.g curl "https://api.openweathermap.org/data/2.5/weather?q=Capetown&appid=__"

5. **Learning and Improvement**: Considering the key concepts and your practical experiences, identify one area related to APIs where you feel confident and one area where you see a need for improvement. What steps will you take to enhance your understanding and skills in the area you wish to improve?

(a)Area of improvement:
Understanding different authentication mechanisms such as API keys, OAuth, JWT (JSON Web Tokens), and OAuth2, and how to implement them securely. Additionally, learning about authorization techniques to control access to API resources based on user roles and permissions.

(b)Area where im confident:
Eploring API's online.
