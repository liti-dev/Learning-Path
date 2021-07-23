# Tia's Learning Path 

I started off learning how to code for nearly a year but haven't kept track of my progress. I was lazy. I thought what I learn each day is too trivial to be penned down. 
However, I've realised my memory was not as good, documenting my learning is crucial to retrieve such knowledge for later use. Also, this doc may be helpful for some beginners out there one day.

First, I have to admit that I'm very lucky. I won a scholarship into a local coding bootcamp and there are many people who support me. Despite this, I'd like to point out that intensive coding bootcamp was not for me. For details, please have a look at [*What I learned after quitting my coding bootcamp.*](https://tiacancode.hashnode.dev/what-ive-learned-after-quitting-my-coding-boot-camp-ckr54typw03a7sls10sa5aikt)


## Week 1 (23 -31/07/2021)
A quick review of [Markdown](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) 

I got an interview on Monday about fundamentals of HTML/CSS and JS. Here is the list of questions:
### HTML/CSS

1. Why should we use HTML5? Why semantics tags?
2. HTML best practices
3. What is BEM?
4. How to override styles written by other developers but not to affect their code
5. Flexbox 
6. How many types of CSS selectors?
7. Positions: Absolute, relative
8. Media query
9. What are common breakpoints for devices?
10. Desktop first

### JS

1. What's new in ES6?
2. Array and Object methods
3. What's the difference between forEach() and map()?
4. Local Storage, Cookies, Session Storage
5. What is dumb component and smart components?
6. Scopes
7. **Blocking and non-blocking**

    Blocking is when the execution of additional JavaScript process must wait until an operation completes. JavaScript engine is single threaded so JS is synchronous and hence blocking in nature.
    
    Non-blocking methods execute asynchronously.

8. Why do you use async/await instead of .then?
9. **Hash table**

    A hash table organizes data so you can quickly look up values for a given key

    Arrays are pretty similar to hash maps. Arrays let you quickly look up the value for a given "key" (index), but Hash maps let us use flexible keys instead of being stuck with sequential integer "indices." 

    All we need is a hashing function to convert a key into an array index (an integer)
    
    ![interviewcake.com](https://www.interviewcake.com/images/svgs/cs_for_hackers__hash_tables_lies_key_labeled.svg?bust=209 "Interviewcake.com")

    
10. **React life cycle**

    Each component in React has a lifecycle which you can monitor and manipulate during its three main phases: **Mounting**, **Updating**, and **Unmounting**.

    **Mounting** means putting elements into the DOM.

    React has four built-in methods that gets called, in this order, when mounting a component:

    1. `constructor()`
    2. `getDerivedStateFromProps()`
    3. `render()`
    4. `componentDidMount()`

    **Updating**

    A component is updated whenever there is a change in the component's `state` or `props`.

    1. `getDerivedStateFromProps()`
    2. `shouldComponentUpdate()`
    3. `render()`
    4. `getSnapshotBeforeUpdate()`
    5. `componentDidUpdate()`

    **Unmounting**

    When a component is removed from the DOM.

    - `componentWillUnmount()`

11. How many types of Hooks do you know? useMemo? useEffect? 
12. Can I pass props or state into useEffect dependency?




