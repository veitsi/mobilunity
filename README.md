

**Objective** : create an simple email-based notification system in 3 hours or less.

Please be attentive to the architecture of the application.

**Architecture description** : Instead of sending emails manually for some actions (like user registered, feedback sent etc) we want to make it event based:

- --There will be a set of special events in system.
- --Each event will have some defined properties (like user, feedback etc), some unique event id and some logic of building email.
_(for example, user registered event should be sent to registered user&#39;s email, but feedback email should be sent to admins)_
- --When event was triggered, the corresponding email should be sent. All params should be passed from event to email&#39;s view

**Tasks** :

- --create events system based of architecture described above
- --create some tests controllers for demonstrate how the system works
- --Proceed like it&#39;s a normal project for a client

**Wishes** :

- --Use Laravel&#39;s Event/Mailable for implement architecture

**Optional:**

- Options to customize email template for specific event id. All custom templates should be stored in database. For each event id we can have not more that one custom template. If there no custom email template - event should use its default blade view
- create simple UI to manage custom templates
- Usage of jQuery.Datatable to display custom templates table
- Usages of simple WYSIWYG editor to edit templates (like Summernote)
- Bundle JS/CSS using Laravel Mix

**Please note that this part in not mandatory, so concentrate your efforts on the main part.**

**Thank you in advance for your time and forces!**

