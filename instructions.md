# Week 10: Accessible Form Practice

# Set-up:

1. Download the [Starter Code](https://github.com/UMSIComplexWebDesign/539_f26_discussion11) from GitHub Repository  
2. Read the scenario and familiarize yourself with the purpose of the form.  
3. Follow the step-by-step instructions to first fix the existing issues, then add new form elements and improve accessibility.

# Submission:

1. Create your own GitHub repository with name **“discussion11-form”**  
2. Deploy your web page (github.io) and Submit the deployed web url to Canvas.

# Scenario: Engaged Learning Student Feedback

For this semester’s client project, you have been designing a resource website for the UMSI Engaged Learning Office (ELO). Imagine that the ELO wants to add a Student Feedback Form to the website. Students can use this form to share their engaged learning experiences and suggest improvements to the resources and support available to them.

The starter code already contains some basic form elements, but it also has several missing attributes and accessibility issues.

# Steps:

## Part A: Fix the Existing Form

1. The \<form\> element is commented out and incomplete.  
   1. Uncomment it and connect the form element to a new form on [formspree.io](https://formspree.io/).  
2. Fix the labels and inputs.  
   1. Some labels are not correctly connected to their corresponding inputs. Add or correct the necessary **`for`** and `id` attributes.  
   2. Test your changes: When you click a label, does it focus or activate the correct input?  
3. Fix missing **`name`** attributes.  
   1. Check whether each form field has a meaningful name attribute. Add any missing attributes.  
   2. Hint: Think of the submitted responses as a spreadsheet. The names are the column headers.  
4. Group the radio buttons semantically.  
   1. The project stage options are visually grouped, but not semantically grouped.  
   2. Replace the current grouping with \<fieldset\> and \<legend\>.   
5. Identify required fields.  
   1. Some fields use the required attribute, but users are not informed visually.  
   2. Update the form to clearly indicate which fields are required.  
   3. Check whether the program dropdown has a clear default prompt

## Part B: Extend Your Form

6. Explore different input types.  
   1. The Email Address field currently uses **`type="text"`**. Change it to a more appropriate input type.  
   2. Add an optional Project Start Date field inside the Your Feedback fieldset, before the feedback text area. Use an appropriate input type.  
      1. Hint: Check [HTML Form Input Types](https://www.w3schools.com/html/html_form_input_types.asp) for examples. Remember to include the necessary label, for, id, and name attributes.  
7. Customize the styling of the form in style.css. We’ve already provided some starter styles for you. Feel free to change them based on your preferences\!  
   1. Use Flexbox to arrange each radio button and its corresponding label on the same line, with each option on a separate row. You may need to wrap each radio button and its label in a \<div\> to achieve this layout.  
8. Check accessibility. Run your form through Wave and aXe and fix any errors you have.  
9. Submit a test response and verify that it was successfully received in your Formspree dashboard.

## Optional

Consider how this feedback form, or similar kinds of form, could fit into your ELO client project website. You may adapt the form or integrate it into your existing project.

