# Types of prerendering and data fetching
1. Static Generation
  - Without data
  - with data
  - Incremental Static Generation
  - dynamic parameters when fetching data
2. Server Side Rendering
  - data fetching 
3. Client-side data fetching
4. Combining pre-rendering with cient-side data fetching
# Why Pre-render ?
1. Pre-render improves performance?
  - In a React app, you need to write for the javascript to be executed
  - Perhaps fetch data from an external API and then render the UI
  - There is a wait time for the user
  - with a pre-rendered page, the HTML is already generated and loads faster
2. Pre-rendering with SEO
  - if you are building a blog or e-commerce site, SEO is a concern
  - with a React app, if the search enging hits your page, it's only see a div tag with id equal to root
  - if search enginee hit's pre-rendered page through, all the contend is present in the source code which will help index that page.
  - if SEO is of concern for your app, pre-rendering is what you want.
  - pre-rendering refers to the process of generating HTML with the necessary data for a page in our applicaiton.
  - Pre-rendering can result in better performance adn SEO
