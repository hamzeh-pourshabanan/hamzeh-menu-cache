# hamzeh-menu-cache

This plugin is context aware, meaning it keeps active pages while caching.

Also it is theme independent, meaning, by changing your theme, it still works
with new theme, provided menus in new theme are powered by wordpress built-in
function, wp_nav_menu().

-----------------------------

You can inspect the rendering time by inspecting menu, below the closing ul tag of 
the wordpress menu, looking for an html comment saying:

Not From menu cache in 0.03401 seconds 

if not cached, and by refreshing the page:

From menu cache in 0.00145 seconds



