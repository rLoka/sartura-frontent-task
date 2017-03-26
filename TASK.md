1. Set up app with minimal structure using webpack as module bundler.
  - Have 1 entry JS file. Also single HTML file
  - Also have single LESS file for styling, configure webpack to extract it into separate CSS file
  - Go on with installing Vue.js core, Vue Router, extend you webpack config to support `.vue` files
  - Use ES2015 if you are familiar

2. Create page to display data in graphs.
  - This is SPA, so use Vue Router for pages
  - Install novus/nvd3
  - Create 2 functions to generate random data every second (any kind of data with any structure of your choice, e.g. fake CPU monitoring)
  - Create reusable "graph" Vue component
  - Show 2 graphs: one lineChart and one areaChart. Use your reusable "graph" Vue component. Update graphs every second
  - Implement ability to change update interval (e.g. 1 second, 5 seconds..) for each of graphs

3. Create page to list/view "items".
  - Choose any fake data of your choice, e.g. https://jsonplaceholder.typicode.com/users and save them as JSON
  - Fetch items via AJAX (from that JSON file) and list them in table. Fine to use some third party Ajax lib, like Vue Resource, but avoid jQuery, if only for "ajax"
  - Implement ability to view each item separately
  - Separate your code into reusable components (so that you can reuse for next task)

4. Integrate Vuex into app.
  - Install and setup Vuex (vuejs/vuex)
  - Create store with "items" collection (similar to previous task, but another page). Fetch initial data using AJAX to populate "items" collection in your store and show them in table (reusable component). Give ability to edit items via form and deleting them from table
  - Create several form fields on top of table to filter items by various params
  - Create simple pagination for your table

5. Give your app some styling with LESS. Optionally create simple menu to navigate.

6. Write short README about setting up your app.

If possible, no semicolons and use tabs for indentation. Work on GIT repo and make commits often.
