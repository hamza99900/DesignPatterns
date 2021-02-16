# DesignPatterns


1-Singleton Pattern

The Singleton design pattern ensures that only one instance exists for a given class and that there’s a global access point to that instance. It usually uses lazy loading to create the single instance when it’s needed the first time.

An instance of a class is traditionally known as an object.

Note: Apple uses this approach a lot. For example: UserDefaults.standard, UIApplication.shared, UIScreen.main, FileManager.default all return a Singleton object.

first consider other ways to accomplish your task, singletons are not appropriate if you’re simply trying to pass information from one view controller to another. Instead, consider passing models via an initializer or property.

Singleton are create ways to organize your code that needs to initialize only once and available every where inside application or code. It initializes your class instance single time only with static property and it will share your class instance globally.
