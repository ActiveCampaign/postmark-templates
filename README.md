<img src="http://assets.wildbit.com/postmark/misc/starter-templates-icon@2x.png" alt="Postmark Transactional Email Templates" width="147" height="147">
# Postmark Transactional Email Templates
Content ready, mobile friendly, and beautiful across all major email clients.

#### What's this for?

*Postmark Transactional Email Templates* are rock-solid email templates that render beautifully in tons of email clients. They provide the foundation of our [Postmark Templates](http://blog.postmarkapp.com/post/125849089273/special-delivery-postmark-templates) feature, and we're glad to provide them as Open Source to the wider community.

These templates are built and maintained using [MailMason](https://github.com/wildbit/mailmason), a grunt-based framework to help streamline the process of developing, testing, and maintaining a set of related transactional email templates. If you want to create or customize your own set of email templates, you can use MailMason to extend the existing emails or start from scratch to build an entirely new set.

## CSS & Inlining

There are two sets of templates here. The first set is in the `/templates` folder and contains the base templates with the CSS all contained in a style block. In this state, they're easier to edit, but they'll have limited compatibility with email clients. The other set in `/templates_inlined` has the same templates but with the CSS already inlined. They'll be a bit more tedious to make changes to, but you won't need to use anything to inline the CSS.

### Inline the CSS
For client compatibility, HTML emails should always be inlined before sending. Here are a couple of tools for doing that:

* [Postmark Style Merge](https://github.com/wildbit/style-merge)
* [Premailer](https://github.com/peterbe/premailer)

If you choose to send your emails with [Postmark](http://postmarkapp.com), each time you send we will automagically inline the CSS for you.

## The Templates

### Welcome

* [Welcome email best practices guide](https://postmarkapp.com/guides/welcome-email-best-practices)
* [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/welcome.html)
* [Litmus test results &rarr;](#)

### Reset password

* [Reset password best practices guide](https://postmarkapp.com/guides/password-reset-email-best-practices)

* Reset Password
  * [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/password_reset.html)
  * [Litmus test results &rarr;](#)
* Reset Password Help
  * [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/password_reset_help.html)
  * [Litmus test results &rarr;](#)

### Receipts/Invoices

[Receipt and invoices best practices guide](https://postmarkapp.com/guides/receipt-and-invoice-email-best-practices)

* Receipt
  * [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/receipt.html)
  * [Litmus test results &rarr;](#)
* Invoice
  * [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/invoice.html)
  * [Litmus test results &rarr;](#)

### Comment notification

* [Comment notification best practices guide](https://postmarkapp.com/guides/notification-email-best-practices)
* [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/comment_notification.html)
* [Litmus test results &rarr;](#)

### Trial expiration

[Trial expiration email best pracitces](https://postmarkapp.com/guides/trial-expiration-email-best-practices)

* Trial Expiring
  * [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/trial_expiring.html)
  * [Litmus test results &rarr;](#)
* Trial Expired
  * [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/trial_expired.html)
  * [Litmus test results &rarr;](#)

### User Invitation

* [User invitation email best practices](https://postmarkapp.com/guides/user-invitation-email-best-practices)
* [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/user_invitation.html)
* [Litmus test results &rarr;](#)
