## Peachy - a vegan recipe resource
##### by Lew Davidson


* Project Description:

> A vegan recipe website that allows users to create an account, search vegan recipes, save them and share them across social media.

### M.V.P Features:

~ User authentication to create a unique account per user

~ Search recipes by keyword

~ Display 10 results per page

~ Save or “star” recipes for later

### Tools, Libraries, Frameworks, Languages to be used:

~ [The Edamam API](https://developer.edamam.com/edamam-docs-recipe-api) for pulling the
needed information to search and use on the page.

~ Firebase for user authentication.

~ I will be using JavaScript, React, Redux, and CSS

#### If MVP is achieved, the additional features I would like to add are:

~ The ability to publish recipes to a user’s social media page from the app.

~ The ability for users to cross off ingredients that they have / recipe steps that they have already completed.

~ The ability to export an ingredient list to a notes section for easy grocery shopping.

#### The additional tools required to achieve these features are:
~ Twitter/ Facebook tools for pushing information to a users social media account.

---

 ## Component Structure:


 ___

 ### Notes:

```
Originally had my router in App which made the Body component useless! I created the body component for styling purposes originally and wanted to keep it, so I ended up having to move my router into body instead.

I tried to keep all of my inventory data in a separate component and import it into any component that needed it (which I still think is the way to go) but it wasn't working correctly and I couldn't get them to talk to each other, so I moved my data into the Display component and it works fine.
 EDIT: I ended up figuring out how to store my inventory object in another separate data file!

I struggled a bit with conceptualizing how to change a button depending on which area of the page you are on, but ended up messing with the props to get them to behave!

```

 ### To-Do:

 [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

 ### Break UI into a component hierarchy

[x] Build a plan for UI, what it will do, how it will look. "What do I want my user experience to feel like?"

[x] Create mock-up of that UI, thinking about routes to use and where and what will appear on which pages.

[x] Draw out component structure based on UI mock-up

[x] Add mockup and component tree to planning repo
