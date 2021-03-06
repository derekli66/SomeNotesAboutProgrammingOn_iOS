# SomeNotesAboutProgrammingOn_iOS

Although I started PROGRAMMING in 2010, mainly in iOS area, the following summary is what I really get from the last two years.
Thanks for those people who share their knowledge and experience to me. I am very thankful.

### Some notes about my iOS programming for the last two years

- Don’t use underscore for **private function** or **private variable**
- Make each parameter name or argument name meaningful
- Use **Camel-Case** naming in *Objective-C* or *Swift* functions or classes
- Use **Underscore** naming in *Cpp*  functions or classes
- When making functions or methods, try to use the easiest way or algorithm to solve the problem like we think how to solve algorithm problem. Don’t make things complicated.
- The unit test should fully test each output of given function. It must test with **correct** input and **incorrect** input.
- Wrap data source in a **singleton class** to manage the insertion, deletion, querying or sorting or even saving. This makes the same data source won’t launch twice. (If we don’t use other data source management framework, like Core Data or Realm.)
- Launch the **Design Review** meeting if it is a new design or a big refactoring
- Before using **smart pointer** in *Cpp*, think about do we really need a **smart pointer** in our solution or may be the **new** and the **delete** are enough.
- Always think about can we use less **Any** or **AnyObject** in our *Swift* code to make our code more type safe and also readable.
- Before using **reference type** in *Swift*, can we replace it with **value type** ?
- Swift **protocol-oriented programming** just like we design **pure virtual** interface in Cpp. They are similar.
- Wraps **Cpp class** in **Objective-C class** if we want to carry the **Cpp class** around the whole project. Make memory management as simple as possible.
- When setting a property in Objective-C, always think carefully when to use, atomic, nonatomic, strong, weak, copy, assign.
- Are we using mutable container in a multi-threading circumstance? How to avoid it or how to protect our resource?
- **Don't let Copy and Paste be your coding habit!. Write each line of code by typing on your keyboard!**
- Get rid of code smell before you smell it.
