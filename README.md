# 100 Days Of Code - Log

On September 22, 2020 I committed to #100DaysOfFrontEnd where I’ll be sharing everything I’m working on related to frontend development. Personal projects, courses I'm taking, tech reads, researching, testing, and many more!

### Day 1: September 23, 2020

**Today's Progress**: Started working on the Random Quote Machine generator in React.

**Today's Learning**: Finished the React JS course from [freeCodeCamp](https://www.youtube.com/watch?v=DLX62G4lc44).

**Thoughts:** This is the first time when I try to build an application in React.
For this app, I've decided to use create-react-app. I've tried a couple of APIs to fetch data but, eventually, I decided to stick to Forismatic API. In the beginning, I've decided just to try slowly to use React, components, props, fetch and display data.

**Link to GitHub:** [Inspirational Quote Generator](https://github.com/alexandracaulea/inspirational-quote-generator)

### Day 2: September 24, 2020

**Today's Progress**: Worked on Inspirational Quote Generator project.

**Today's Learning**: I reviewed my notes from the FCC React course and I've also read through React docs. I'm planning on continuing to do so the next days as well.

**Thoughts:** Spent some time thinking more on the HTML structure since before I had a bunch of `<div>` tags. I refactored a bit the code since at the beginning I didn't know where to start with React. I decided to keep saving in the state only the information I needed. Made the "New Quote" button to generate a new random quote by making every time a new request to the API. Made the "Twitter" link work and now I am able to post the quote on Twitter.

**Link to GitHub:** [Inspirational Quote Generator](https://github.com/alexandracaulea/inspirational-quote-generator)

### Day 3: September 25, 2020

**Today's Progress**: Worked on Inspirational Quote Generator project.

**Thoughts:** Spent some time trying out different styles for the app and implementing it. Decided to try out styled components for the very first time. Deployed the app to Netlify

I’ve created in Trello a card with all the things I have to add/change to the app (eg. add loader, remove comments and unnecessary files).

**Today's Learning**: I’ve learned that styled components are a css-in-js tool and their goal is to give a flexible way to style components. It makes more sense for me when I’ve read the sentence: “When you create a styled component, you are creating a React component with styles” (source Smashing Magazine).
I’ve learned about the “createGlobalStyle” function used to style the global elements like html and body.
I’ve also set up a shortcut in VS Code in order to make the css style be sorted ascending.

I've read:

- Useful article about styled components: https://www.smashingmagazine.com/2020/07/styled-components-react/
- Docs styled components: https://styled-components.com/docs/basics

**Link to GitHub:** [Inspirational Quote Generator](https://github.com/alexandracaulea/inspirational-quote-generator)

**Link to Netlify**: [Inspirational Quote Generator](https://inspirational-quote-generator.netlify.app/)

### Day 4: September 26, 2020

**Today's Progress**: Worked on Inspirational Quote Generator project.

**Thoughts:** Today I had only 1 h to code so I decided to spend it continuing to work on the “Inspirational Quote Generator” in React. I’ve managed to configure Airbnb Style Guide and ESLint and improved the code based on the feedback received from ESLint. I’ve also removed unnecessary code and files, added meta tags, updated the title and added favicons. I still have a few things to work on and improve the app, but I’ll do it in the next period.

**Link to GitHub:** [Inspirational Quote Generator](https://github.com/alexandracaulea/inspirational-quote-generator)

**Live example**: [Inspirational Quote Generator](https://inspirational-quote-generator.netlify.app/)

### Day 5: September 27, 2020

**Today's Progress**: Worked on Inspirational Quote Generator project.

**Thoughts:**

### 1. Fixed error “SyntaxError Unexpected Token in JSON”

Today I've worked on fixing the error “SyntaxError Unexpected Token in JSON”. I've seen that from time to time, the response received from the API was a string.

As an example, whenever inside of the quoteText was a backslash, the response received from the API was a string.

```json
{
  "quoteText": "I can't imagine a person becoming a success who doesn't give this game of life everything hes got.",
  "quoteAuthor": "Walter Cronkite",
  "senderName": "",
  "senderLink": "",
  "quoteLink": "http://forismatic.com/en/342c3061d1/"
}
```

As a result of that, I've switched from the `fetch` API in using the Axios library and integrated additional logic in order to handle the "string" response received from the API.

I've spent a lot of time figuring out how to fix this issue, mainly in the console, the network tab and researching online.

### 2. Decided to start using branches instead of committing code to master.

### 3. Small improvements to the project:

- Learned how to animate the octo arm path
- Learned that we can use `css` API which allows us to construct reusable CSS blocks (I’ve created a separate file called “mixins.js” repeated styles are added.
- Learned that styled-components can incorporate animations by using the `keyframes` helper which generates a UNIQUE instance.
- Learned how to target another styled component on hover
- Learned that we can interpolate other styled-components to refer to their automatically generated class names

### **Another update for yesterday:**

1. I officially registered for Hacktoberfest 2020, I’m super excited and scared at the same time.
2. Used `git reflog` and `git reset --soft` for the very first time. I accidentally merged master into develop (What can I say? I will not code after 10 PM in the evening).

Useful Link:
[Adding CSS Animations with Styled Components](https://medium.com/@matt.readout/adding-css-animations-with-styled-components-6c191c23b6ba)

**Link to GitHub:** [Inspirational Quote Generator](https://github.com/alexandracaulea/inspirational-quote-generator)

**Live example**: [Inspirational Quote Generator](https://inspirational-quote-generator.netlify.app/)

### Day 6: September 27, 2020

**Today's Progress**: Worked on my website.

**Thoughts:** Today I've worked on my website: added relevant information for each project, improved the overall layout, removed a couple of projects and reorganized the content.

**Link to GitHub:** - (private repository)

**Live example**: [My Website](https://www.alexandracaulea.com/)

<!-- ### Day 0: February 30, 2016 (Example 1)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link to work:** [Calculator App](http://www.example.com)

### Day 0: February 30, 2016 (Example 2)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts**: I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link(s) to work**: [Calculator App](http://www.example.com)


### Day 1: June 27, Monday

**Today's Progress**: I've gone through many exercises on FreeCodeCamp.

**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.

**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence) -->
