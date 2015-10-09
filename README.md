# JS-Breadcrumbs

This script dynamically generates breadcrumb navigation links from a static page's URL. Essentially, it takes extracts the file path from the URL and appends each item to an unordered list.

To get started, you'll need to add the initial `<ul>` with an id of "crumbs" to your HTML where you want the breadcrumb to be. You'll also need to add the initial "Home" link as the first `<li>`. The script will then append the rest of the breadcrumb onto this list.
```
<div id="breadcrumb">
  
    <ul id="crumbs">
    
      <li><a href="#">Home</a></li>
      
    </ul>
    
</div>
```
