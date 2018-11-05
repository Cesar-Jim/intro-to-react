### Questions

> In your own words, explain the essential differences between props and state in React. Which is immutable or read-only, and which changes? Submit your response in the submission text area and discuss the answer with your mentor.

**A.**
Both, props and state act as the input data for the `render()` method of a given component. A component cannot change its `props`. This characteristic makes `props` **immutable** or, in other words, that `props` will not change. On the other hand, `state` suffers changes or **mutations** which are mainly triggered by user events. So this is one essential difference between `props` and `state`.

Another essential difference is that **state** is a private feature and it strictly belongs to a single component. Whereas **props** can be passed by a parent component to its children.

**State** is referred to the local state of the component that can only be used and modified inside the component. **Props** give components the ability to receive data from the parent component.  

From [reactjs.org](reactjs.org):

* React is pretty flexible but it has a single strict rule: **all React components must act like pure functions with respect to their props.** Which means it never modifies its own props...  


> Read the React official documentation on components and props, and brush up on JavaScript ES6 **classes**

**A.**
I have read and understood the topics regarding components and props, and also have revisited the classes (ES6) topic.


> Build upon your component from the previous checkpoint's assignment, add in state and props to make sure you have fully mastered these core React properties.

**A.**

###### *Submitted by Cesar Jimenez*
