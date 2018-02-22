<img src="http://assets.wildbit.com/postmark/misc/templates-logo@2x.png" alt="Postmark Transactional Email Templates" width="148" height="148" align="right">

# Postmark Transactional Email Templates
Brought to you by
<a href="http://postmarkapp.com"><img src="http://assets.wildbit.com/postmark/misc/postmark.svg" alt="Postmark"></a>

**Content ready, mobile friendly, and beautiful across all major email clients.**

#### What's this for?

*Postmark Transactional Email Templates* are rock-solid email templates that render beautifully in tons of email clients. They provide the foundation of our [Postmark Templates](https://postmarkapp.com/blog/special-delivery-postmark-templates) feature, and we're glad to provide them as Open Source to the wider community.

These templates are built and maintained using [MailMason](https://github.com/wildbit/mailmason), a grunt-based framework to help streamline the process of developing, testing, and maintaining a set of related transactional email templates. If you want to create or customize your own set of email templates, you can use MailMason to extend the existing emails or start from scratch to build an entirely new set.

## CSS & Inlining

There are two sets of templates here. The first set is in the `/templates` folder and contains the base templates with the CSS all contained in a style block. In this state, they're easier to edit, but they'll have limited compatibility with email clients. The other set in `/templates_inlined` has the same templates but with the CSS already inlined. They'll be a bit more tedious to make changes to, but you won't need to use anything to inline the CSS.

### Inline the CSS
For client compatibility, HTML emails should always be inlined before sending. Here are a couple of tools for doing that:

* [Postmark Style Merge](https://github.com/wildbit/style-merge)
* [Premailer](https://github.com/peterbe/premailer)

If you choose to send your emails with [Postmark](http://postmarkapp.com), each time you send we will automagically inline the CSS for you.

## The Templates

The templates are listed below and have all been tested for consistency in the following email clients:

* Desktop
  * Apple Mail 9, 10, 11
  * Outlook 2007, 2010, 2011, 2013, 2016
  * Windows 10 Mail
* Mobile
  * Gmail App (Android)
  * iPhones 6, 7, 8, SE, X
  * iPad (Retina)
  * iPad Mini
  * iPad Pro
* Web
  * AOL
  * Gmail
  * Outlook.com
  * Yahoo

### [Welcome](http://assets.wildbit.com/postmark/templates/dist/welcome.html)

Send a welcome email to users after they sign up.

* [Welcome email best practices guide](https://postmarkapp.com/guides/welcome-email-best-practices)
* [Litmus test results](https://litmus.com/pub/a087bdc)

### [Reset Password](http://assets.wildbit.com/postmark/templates/dist/password_reset.html) 

  Send users a link to reset their password.
  
  * [Reset password best practices guide](https://postmarkapp.com/guides/password-reset-email-best-practices)
  * [Litmus test results](https://litmus.com/pub/c4ee0e9)

### [Reset Password Help](http://assets.wildbit.com/postmark/templates/dist/password_reset_help.html)

  Help users reset their password if they can’t remember their email.

  * [Reset password best practices guide](https://postmarkapp.com/guides/password-reset-email-best-practices)
  * [Litmus test results](https://litmus.com/pub/82b4127)

### [Receipt](http://assets.wildbit.com/postmark/templates/dist/receipt.html)

  Send a receipt to users after they made a purchase.

  * [Receipt and invoices best practices guide](https://postmarkapp.com/guides/receipt-and-invoice-email-best-practices)
  * [Litmus test results](https://litmus.com/pub/dc65df0)

### [Invoice](http://assets.wildbit.com/postmark/templates/dist/invoice.html)

  Request payment from a user.

  * [Receipt and invoices best practices guide](https://postmarkapp.com/guides/receipt-and-invoice-email-best-practices)
  * [Litmus test results](https://litmus.com/pub/877016b)

### [Comment notification](http://assets.wildbit.com/postmark/templates/dist/comment_notification.html)

Notify users of new comments by other users.

**Note:** Comment notification isn't the prettiest preview because it's just [Mustachio](https://github.com/wildbit/mustachio). Since almost all content in this email is dynamic, it won't look good without real content. Don't worry though, that's how it's supposed to look.

* [Comment notification best practices guide](https://postmarkapp.com/guides/comment-notification-email-best-practices)
* [Litmus test results](https://litmus.com/pub/d7008f1)

### [Trial Expiring](http://assets.wildbit.com/postmark/templates/dist/trial_expiring.html)

  Let users know when their trial is about to expire.

  * [Trial expiration email best pracitces](https://postmarkapp.com/guides/trial-expiration-email-best-practices)
  * [Litmus test results](https://litmus.com/pub/cd363ec)

### [Trial Expired](http://assets.wildbit.com/postmark/templates/dist/trial_expired.html)

  Let users know when their expired trial.

  * [Trial expiration email best pracitces](https://postmarkapp.com/guides/trial-expiration-email-best-practices)
  * [Litmus test results](https://litmus.com/pub/30fb01d)

### [User Invitation](http://assets.wildbit.com/postmark/templates/dist/user_invitation.html)

  Help users invite others to use your software.

* [User invitation email best practices](https://postmarkapp.com/guides/user-invitation-email-best-practices)
* [Litmus test results](https://litmus.com/pub/ac67c0c)
