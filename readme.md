# Co ordinator layout
 the child of cordinator layout are
 1. appbarlayout
 2. scrollable view
 3. floting button

 ## Appbar layout

 App bar layout is like linear layout. It manage the behaviour of direct child.
 with parameters called.

 ## layout_scrollFlags

 layout_scrollFlags have follwoing values.

 1. scroll
 2. snap
 3. enterAlways

## AppbarLayout flags

1. SCROLL_FLAG_ENTER_ALWAYS: When entering (scrolling on screen) the view will scroll on any downwards scroll event, regardless of whether the scrolling view is also scrolling.

2. SCROLL_FLAG_ENTER_ALWAYS_COLLAPSED: An additional flag for 'enterAlways' which modifies the returning view to only initially scroll back to it's collapsed height.

3. SCROLL_FLAG_EXIT_UNTIL_COLLAPSED: When exiting (scrolling off screen) the view will be scrolled until it is 'collapsed'.

4. SCROLL_FLAG_SCROLL: The view will be scroll in direct relation to scroll events.
5. SCROLL_FLAG_SNAP: Upon a scroll ending, if the view is only partially visible then it will be snapped and scrolled to it's closest edge.




