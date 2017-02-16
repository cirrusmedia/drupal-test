# Technical Test for Drupal Developer

This is a simple [Drupal](http://drupal.org/) 7 test. 
Please make a repository in bitbucket and share with your work with database dump to 'mizoshiri' and email to us.

You will be judged on following :
- That you have successfully completed the task and fulfils its function
- How you have achieved this goal
- The time it took from download of file to upload of completed work

Good luck

## The Tasks

### Building

* Install site using 'minimal' profile
* Create an 'event' content type that has title, description, date, and address
* Build a view with two page displays
    * Upcoming events (/events/upcoming)
    * Past events (/events/past)
* Each event detail page has a form, user can submit form and admin get email with event page URL.
    * Form fields: name,email, detail(textarea)
    * Please add jQuery Validation, name, email are required
    * Don't need save submit data in database
    * Email type is text or html either fine
* Export the events content type and views to a Feature

### Theming

* Create a custom template for the event content type

### Memo

* Please use mysql for database
* You can use any modules you need
