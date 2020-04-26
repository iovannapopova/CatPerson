# CatPerson

The entry point for the application is the AppDelegate.init method. In this method we are creating the main objects of our application, such as controller and router. 
The Router class is responsible for creating and presenting view controllers in the application, as well as setting up their dependencies (for example, Controller).

### Controller

This class prepares viewModels from model (?) objects for displaying UI in different screens, and implements some protocols because this class has to update UI when the viewcontroller appears, when a location is selected and when  a text field is edited.

### WebService

Resource struct represents the single endpoint on the backend. We put everything we need to make a request to the server and to parse a response in this struct. Since it is a generic struct we can specify the type which will represent the server response and take advantage of Swift's strong typing. Inspired by objc.io

I think the next step for me would be increasing the tests coverage, improving the downloading of the images, using an appropriate size of them. 
