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
# Pre-rendering in Next-js
Next-js support two type of pre-rendering
  - Static Generation
  - Server side Rendering
# Static Generation
- Method of pre-rendering where the HTML pages are generated at build time
- The HTML with all the data that makes up the content of the web page are generated in advance when you build your application
- Recommented method to pre-render pages whenever possible
- Page can be build once, Cached by a CDN and served to the clinet almost instantly
- EX- Blog pages, e-commerce product pages, documentation and marketing pages
# Static Generation - How ?
 - Next JS, by default will pre-render every page in out app 
 - The HTML for every page will automatically be statically generated when we build our applicaiton


 <b>Prod-Server</b> - on Optimized build is created once and you deploy that build. You don't make code changes on the go once it is deployed
 <b>Dev-Server</b> - We should be able to make changes in our code and we want that code to immediatly reflect in the brower
 <p>For Production Builds, a pages will be re-rendered once when we run the build command </p>
 <p>In developemnt mode, the page is pre-rendered fro every request you make</p>
 
