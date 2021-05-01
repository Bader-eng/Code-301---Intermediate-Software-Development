# EJS:
* simply stands for Embedded JavaScript templates, and we can use it both server-side or client-side. At this story, we’ll focus on the server-side.

* A template engine enables you to use static template files in your application. At runtime, the template engine replaces variables in a template file 
with actual values, and transforms the template into an HTML file sent to the client. This approach makes it easier to design an HTML page.

## Basic Syntax(Tags):

    <% 'Scriptlet' tag, for control-flow, no output
    <%= Outputs the value into the template (HTML escaped)
    <%- Outputs the unescaped value into the template
    
## File Structure

Here are the files we’ll need for our application. We’ll do our templating inside of the views folder and the rest is pretty standard Node practices.

* - views
* ----- partials
* ---------- footer.ejs
* ---------- head.ejs
* ---------- header.ejs
* ----- pages
* ---------- index.ejs
* ---------- about.ejs
* - package.json
* - server.js
