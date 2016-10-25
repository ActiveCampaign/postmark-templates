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

The templates are listed below and have all been tested for consistency in the following email clients:

* Desktop
  * Apple Mail 8, 9, 10
  * Outlook 2007, 2010, 2011, 2013, 2016
  * Windows 10 Mail
* Mobile
  * Gmail App (Android)
  * iPhone 5s (iOS 8)
  * iPhone 6s
  * iPhone 6s plus
  * iPad (Retina)
  * iPad Mini
* Web
  * AOL
  * Gmail
  * Outlook.com
  * Yahoo

### Welcome

Send a welcome email to users after they sign up.

* [Welcome email best practices guide](https://postmarkapp.com/guides/welcome-email-best-practices)
* [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/welcome.html)
* [Litmus test results &rarr;](https://litmus.com/pub/24f5dc8)

### Reset password

* [Reset password best practices guide](https://postmarkapp.com/guides/password-reset-email-best-practices)

#### Reset Password

  Send users a link to reset their password.
  
  * [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/password_reset.html)
  * [Litmus test results &rarr;](https://litmus.com/pub/3d48973)

#### Reset Password Help

  Help users reset their password if they can’t remember their email.

  * [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/password_reset_help.html)
  * [Litmus test results &rarr;](https://litmus.com/pub/5c3766d)

### Receipts/Invoices

[Receipt and invoices best practices guide](https://postmarkapp.com/guides/receipt-and-invoice-email-best-practices)

#### Receipt

  Send a receipt to users after they made a purchase.

  * [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/receipt.html)
  * [Litmus test results &rarr;](https://litmus.com/pub/4778613)

#### Invoice

  Request payment from a user.

  * [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/invoice.html)
  * [Litmus test results &rarr;](https://litmus.com/pub/eed3e67)

### Comment notification

Notify users of new comments by other users.

**Note:** Comment notification isn't the prettiest preview because it's just Mustachio. Since almost all content in these emails is dynamic, they don't look good without real content. So don't worry though, that's how they're supposed to look.

* [Comment notification best practices guide](https://postmarkapp.com/guides/comment-notification-email-best-practices)
* [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/comment_notification.html)
* [Litmus test results &rarr;](https://litmus.com/pub/7ea5b37)

### Trial expiration

[Trial expiration email best pracitces](https://postmarkapp.com/guides/trial-expiration-email-best-practices)

#### Trial Expiring

  Let users know when their trial is about to expire.
  
  * [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/trial_expiring.html)
  * [Litmus test results &rarr;](https://litmus.com/pub/80d7c42)

#### Trial Expired

  Let users know when their expired trial.

  * [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/trial_expired.html)
  * [Litmus test results &rarr;](https://litmus.com/pub/4412f89)

### User Invitation

  Help users invite others to use your software.

* [User invitation email best practices](https://postmarkapp.com/guides/user-invitation-email-best-practices)
* [Preview &rarr;](http://assets.wildbit.com/postmark/templates/dist/user_invitation.html)
* [Litmus test results &rarr;](https://litmus.com/pub/6a3336f)