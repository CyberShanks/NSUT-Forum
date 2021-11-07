Phases of the Project

Phase 1

    Step 1-> 
    Landing Page (HTML and CSS encoded), all relevant assests found
    To be added: footer with contact us details. Our vision maybe. Better background

    Step 2-> 
    Signup/Login Page (HTML and CSS, no JS)


    Step 3->
    Home/Discussions Page (Html and CSS, no JS)

Notes Landing Page Style

    1)  color: inherit -> it specifies that the color should be inherited from the parent.
    2)  background: no-repeat center/cover -> is saying place a background image in the element, but only show one instance of it (no-repeat) the   image in the vertical centre, and horizontal centre of the element. This is related to the background-position property. By using the be cover value you are saying scale the background image to be as large as possible so that the background area is completely covered by the background image.
    3)  transform: sacle(o.98) -> defines a transformation that resizes an element on the 2D plane. It can take two(x and y) or one(same x and y) parameters in vector form.
    4)  transition: background 0.5s ease-in-out -> transition allows elements to change values over a specified duration, animating the property changes, rather than having them occur immediately. Background specifies that only the backround has to be changed. Apart from background we can have "all" or "padding" etc.
    5)  background-attachment:fixed  -> sets whether a background image scrolls with the rest of the page, or is fixed.
    6)  z-index: 10  -> The z-index property specifies the stack order of an element. An element with greater stack order is always in front of an element with a lower stack order.

Notes Landing Page Body

Navigation and Main Display 

    1) data-spy="scroll" data-target="#navbar" data-offset="72" class="position-relative";
    Updates navigationbased on scroll position to indicate which link is currently active. To add scroll behavior to the navigation bar, add data-spy="scroll" to the element you want to spy on (most typically this would be the <body>). Then add the data-target attribute with the ID or class of the parent element of any Bootstrap with .nav component. This should always have a relative postion class to work.

    2) nav class="navbar navbar-expand-lg navbar-dark fixed-top bg-purple" id="mainNav";
    Navbars require a wrapping .navbar with .navbar-expand{-sm|-md|-lg|-xl|-xxl} for responsive collapsing and color scheme classes. Their contents are fluid and responsive by default. Navbar-dark/light sets the text color to white or black. Fixed-top tells that the navigation bar should scroll along with the page fixed at the top.

    3) class= "container" or "container-fluid" or "container-fluid-max"
    These contain, pad, and align your content within a given device or viewport. The .container, which sets a max-width at each responsive breakpoint. The container-fluid, which is width: 100% at all breakpoints and .container-{breakpoint} which is width: 100% until the specified breakpoint.

    4) class="navbar-brand" href="#home"><img src="#" alt="..." />NSUT FORUM
       button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarResponsive"
       aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation"

    Navbar-brand allows us to insert and image in the navbar and sets its dimensions accordingly. We create a button with "navbar-toggler" with the name "menu". Add data-bs-toggle="collapse" and a data-bs-target (line 115 in code) to the element to automatically assign control of one or more collapsible elements. The data-bs-target attribute accepts a CSS selector to apply the collapse to. The aria attributes explicitly conveys the current state of the collapsible element tied to the control to screen readers and should be specified.

    5) class="fas fa-bars ms-2"
    This is and inline element for "Menu" that used font awesome to add three bars beside the text saying menu. ms-2 specifies the spacing between the text and the bars.

    6) d-flex is used to display a flex container. vh-100 is the sizing of the display. cover and hero are defined in the CSS. class="row" is used mainly to hold columns in it. Bootstrap divides each row into a grid of 12 virtual columns. For example, under row, col-md-6 div will have the width of 6/12 of the "row"s div, meaning 50%. The col-md-4 will hold 33.3%, and the col-md-2 will hold the remaining 16.66%.




  