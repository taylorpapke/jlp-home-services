JLP Home Services Website
=========================

This repository contains the public website for JLP Home Services, a locally
owned home improvement company serving Nashville, Clarksville, and Franklin,
Tennessee. Rural Renovations is the company's Ohio division.

The site provides information about the company and its services, including
deck building, landscaping, painting, flooring, roofing and siding, bathroom
and kitchen renovations, property preservation, winter services, investor
rehab work, and related home maintenance.

Pages
------

* index.html - Welcome page with project photos, BBB information, and customer
  testimonials.
* about.html - Company background and the Rural Renovations Ohio division.
* services.html - Complete list of available services.
* contact.html - Quote request form.

Contact form
------------

The contact page uses a custom-styled form that submits to the existing Google
Form endpoint. The form fields are mapped to the configured Google Form entry
IDs for name, email, and project comments.

Development
-----------

This is a static HTML, Sass, CSS, and JavaScript website. It can be previewed
with any static web server. For example:

    python3 -m http.server 8000

Then open http://localhost:8000/ in a browser.

Styles are maintained in assets/sass and the compiled stylesheet is available
at assets/css/main.css.

Copyright
---------

© 2025 JLP Home Services. All rights reserved.
