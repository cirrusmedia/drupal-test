# Technical Test for Drupal Developer

This is a simple [Drupal](http://drupal.org/) 7 test. 
Please make a repository in bitbucket and share your work with a database dump to 'loganchiang' and email to Geo.jose@adg.com.au.

Successful outcomes are:
- That you have successfully completed the task and fulfill its function
- How you have achieved this task



## The Tasks

### Building

* Install site using 'minimal' profile
* Create an 'event' content type that has title, description, date, and address
* Build a view with two page displays as below
    * Upcoming events (/events/upcoming)
    * Past events (/events/past)
* Each event detail page has a form, user can submit form and get email notification to liang-han.chiang@adg.com.au with event page URL.
    * Form fields: name,email, detail(textarea)
    * Please add jQuery Validation, name, email are required
    * Don't need to save submitted data in database
    * Email type can be text or html
* Export the events content type and views to a Feature

### Theming

* Create a custom template for the event content type

### Note

* Please use mysql for database
* You can use any module as required
