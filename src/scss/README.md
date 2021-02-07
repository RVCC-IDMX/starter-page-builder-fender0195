# File Structure for SCSS

## SCSS Folder

* **Abstracts/**: This folder contains configuration files such as variables, functions, mixing and also helper files.

    * *_functions.scss*: Functions usually define complex operations and can only contain universal statements.

    * *_mixin.scss*: Mixin can contain their own style runs or they can also be nested in other ones.

    * *_variables.scss*: Variables contains information that can be reused later.

* **Base/**: This folder contains parts of the code that is in many places with little alteration, such as resets and typographic rules.

    * *_reset.scss*: The purpose of this file is to reduce some browser inconsistencies.

    * *_typography.scss*: This file contains typography rules to later be edited.

* **Components/**: This folder contains all the small modules, such as button, sliders and headers.

    * *_header.scss*: This file contains the style usiing in the header of the page.

* **Pages/**: This folder contains specific styles for individuals pages, such as the homepage which is usually different.

    * *_home.scss* This file contains the style for the main page pulling information from the *_variables.scss* file.


