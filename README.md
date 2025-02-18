# First ReactJS web app

This is my first reactJS webapp it follows a tutorial provide by [Next.js](https://nextjs.org/learn/react-foundations). It goes over how to build a reactJs app natively followed by installing nextJS to better your workflow.

- `index_copy.html` - Is the HTML file that was created before install next.js. The type needs to be changed to JSX to render. You use `createRoot` to create the React DOM and then use `var.render` to render your component. 

- When installing the latest next.js and reactJS the code will stay virtually the same, but folder structure and layout changes quite a bit which allows for a cleaner setup for organization.
    - The app folder provides an area for all the code to be housed in one area.
    - Each file has an unique naming convention 
    - `page.jsx` - is the file that will be rendered on the page. When just using reactJs, you'd need to render the page yourself. With next.js `page.jsx` will be rendered automatically
    - `like-button.jsx` - is a component file that can be called and used throughout your project
    - `layout.jsx` - layout that is created for the root directory that is placed in. So if you'd want the layout to be different for different pages then you'd want to place them at folder level.
