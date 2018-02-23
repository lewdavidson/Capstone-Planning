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
I'm adding components that I didn't plan for, mainly for site rendering, and I'm wondering if that is okay and why it wouldn't be okay, It is mainly in order to get the UI looking the way I want it to, but it's a way that could get really tangled if i'm not affecting state through reducers. There will be callbacks everywhere!



```

### To-Do:

 Using the [Thinking in React](https://reactjs.org/docs/thinking-in-react.html) article, begin building the site using these steps:

### Break UI into a component hierarchy

[x] Build a plan for UI, what it will do, how it will look. "What do I want my user experience to feel like?"

[x] Create mock-up of that UI, thinking about routes to use and where and what will appear on which pages.

[x] Draw out component structure based on UI mock-up

[x] Add mockup and component tree to planning repo

### Build A Static Version

[ ] Using component Structure, build out a static version of the site. (Hard code anything coming in from outside sources).

[ ] Add link to static site's repo to this planning document

### Identify minimum complete representation of UI state

[ ] Consider how state will be organized

[ ] Outline any state slices needed and how they will be structured

[ ] Add a list of state slices this site requires AND how they will be structured to this document.

### Identify where state should live (lift state)

[ ] Determine WHERE state needs to live

[ ] Add a section to this document detailing where state will be lifted to.

[ ] Refactor existing components to include state and state values (don't worry about redux quite yet). Basically add state to the site.

### Inverse Data Flow

[ ] Integrate all backend logic into the UI (there will be considerably more detailed steps to this process)
