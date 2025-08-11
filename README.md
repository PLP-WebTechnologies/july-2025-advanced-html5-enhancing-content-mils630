Enhanced HTML5 Content & Forms
Overview
This project demonstrates the use of advanced HTML5 elements to create a well-structured multi-section web page containing lists, tables, media, and a fully functional form. The page is built using only HTML5, without any CSS or JavaScript, to focus on semantic markup and native browser features.

Assignment Requirements and How They Are Met
1. Use lists and tables effectively to organize content for clarity and accessibility
Unordered List (<ul>) — Shows examples of web technologies.

Ordered List (<ol>) — Displays steps in a development process.

Description List (<dl>) — Explains key web development terms.

Table (<table>) — Presents a course schedule with <thead>, <tbody>, and <tfoot> for semantic clarity.

2. Embed media content using semantic HTML5 elements
Image — Included inside a <figure> with <figcaption>.

Audio — Added using the <audio> element with a sample MP3 file.

Video — Added using the <video> element with a sample MP4 file.

Fallback text provided for browsers that cannot play the media.

3. Build structured HTML5 forms that are both usable and visually intuitive
Form grouping — Uses <fieldset> and <legend> to separate personal information, account details, and preferences.

Labels — All inputs are paired with <label> elements for accessibility.

Multiple input types — Includes text, email, tel, password, select, and checkbox.

4. Apply various HTML5 form attributes to improve user interaction
Attributes used:

placeholder — Guides users on expected input.

required — Ensures fields must be completed.

autocomplete — Suggests previously entered information.

readonly — Can be applied for fixed values (not used in this form but supported).

5. Use built-in validation techniques without relying on JavaScript
Validation examples:

required — Prevents empty submissions.

type="email" — Ensures valid email formatting.

pattern="[0-9]{10}" — Enforces a 10-digit phone number format.

minlength / maxlength — Controls input length.

File Structure
-enhanced-form.html — Main HTML file containing lists, tables, media, and the form.

**README.md — Documentation and explanation of assignment compliance.**

**Usage**
-Open enhanced-form.html in any modern web browser.
-View the example lists, tables, and embedded media.
-Fill out the form to experience HTML5’s native validation features.
-Submit the form to see the browser’s built-in feedback for missing or incorrectly formatted data.

**Browser Compatibility**
-Works in all major modern browsers (Chrome, Firefox, Edge, Safari, Opera).
-Audio and video playback depends on the browser’s supported file formats.
-Fallback messages appear if the media cannot be played.

Author
mils630
