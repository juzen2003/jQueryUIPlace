### jQuery UI
* min css remove all spaces and load much faster on browser, so if we don't need to modify the styling, use min css file for better performance
* view source page could be used to checked html file and clicking on the link would help to confirm the stylesheet is the one we want
* make sure to link jquery-ui.css
* core jquery.js file has to come before jquery-ui.js in html
* To add a widget, first put the required script tag after jquery-ui.js script tag, and then follow the structure pattern in the source example for each widget (it's h3 div h3 div for accordion)
* we can always change the id of widget's div as long as it matched the jquery in the script tag in head
* we would still use own style.css to customize the widget if needed
