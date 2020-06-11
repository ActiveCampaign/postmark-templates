<img src="http://assets.wildbit.com/postmark/misc/templates-logo@2x.png" alt="Postmark Transactional Email Templates" width="148" height="148" align="right">

# Postmark Transactional Email Templates
Brought to you by
<a href="http://postmarkapp.com"><img src="http://assets.wildbit.com/postmark/misc/postmark.svg" alt="Postmark"></a>

**Content ready, mobile friendly, and beautiful across all major email clients.**

#### What's this for?

*Postmark Transactional Email Templates* are rock-solid email templates that render beautifully in tons of email clients. They provide the foundation of our [Postmark Templates](https://postmarkapp.com/blog/special-delivery-postmark-templates) feature, and we're glad to provide them as Open Source to the wider community.

These templates are built and maintained using [MailMason](https://github.com/wildbit/mailmason), a grunt-based framework to help streamline the process of developing, testing, and maintaining a set of related transactional email templates. If you want to create or customize your own set of email templates, you can use MailMason to extend the existing emails or start from scratch to build an entirely new set.

## CSS & Inlining

There are two sets of templates here. The first set is in the `/templates` folder and contains the base templates with the CSS all contained in a style block. In this state, they're easier to edit, but they'll have limited compatibility with email clients. The other set in `/templates-inlined` has the same templates but with the CSS already inlined. They'll be a bit more tedious to make changes to, but you won't need to use anything to inline the CSS.

### Inline the CSS
For client compatibility, HTML emails should always be inlined before sending. Here are a couple of tools for doing that:

* [Postmark Style Merge](https://github.com/wildbit/style-merge)
* [Premailer](https://github.com/premailer/premailer)

If you choose to send your emails with [Postmark](http://postmarkapp.com), each time you send we will automagically inline the CSS for you.

## The Templates

Each template comes in three different generic layout variations: Basic, Basic full, and Plain. This gives you a starting point so that you can customize your templates to match your brand.

<img src="https://github.com/wildbit/postmark-templates/raw/master/media/starter-templates@2x.png" max-width="100%" alt="Starter templates side-by-side: Basic, basic full, and plain">
<img src="https://github.com/wildbit/postmark-templates/raw/master/media/dark-mode@2x.png" max-width="100%" alt="Dark mode compatibility">


### Welcome

  Send a welcome email to users after they sign up.

  * 💌 Preview with layout: [Basic](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic/welcome/content.html), [Basic full](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic-full/welcome/content.html), [Plain](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/plain/welcome/content.html)
  * 📔 [Welcome email best practices guide](https://postmarkapp.com/guides/welcome-email-best-practices)

### Reset Password

  Send users a link to reset their password.

  * 💌 Preview with layout: [Basic](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic/password-reset/content.html), [Basic full](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic-full/password-reset/content.html), [Plain](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/plain/password-reset/content.html)
  * 📔 [Reset password best practices guide](https://postmarkapp.com/guides/password-reset-email-best-practices)

### Reset Password Help

  Help users reset their password if they can’t remember their email.

  * 💌 Preview with layout: [Basic](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic/password-reset-help/content.html), [Basic full](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic-full/password-reset-help/content.html), [Plain](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/plain/password-reset-help/content.html)
  * 📔 [Reset password best practices guide](https://postmarkapp.com/guides/password-reset-email-best-practices)

### Receipt

  Send a receipt to users after they made a purchase.

  * 💌 Preview with layout: [Basic](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic/receipt/content.html), [Basic full](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic-full/receipt/content.html), [Plain](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/plain/receipt/content.html)
  * 📔 [Receipt and invoices best practices guide](https://postmarkapp.com/guides/receipt-and-invoice-email-best-practices)

### Invoice

  Request payment from a user.

  * 💌 Preview with layout: [Basic](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic/invoice/content.html), [Basic full](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic-full/invoice/content.html), [Plain](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/plain/invoice/content.html)
  * 📔 [Receipt and invoices best practices guide](https://postmarkapp.com/guides/receipt-and-invoice-email-best-practices)

### Comment notification

Notify users of new comments by other users.

**Note:** Comment notification isn't the prettiest preview because it's just [Mustachio](https://github.com/wildbit/mustachio). Since almost all content in this email is dynamic, it won't look good without real content. Don't worry though, that's how it's supposed to look.

  * 💌 Preview with layout: [Basic](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic/comment-notification/content.html), [Basic full](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic-full/comment-notification/content.html), [Plain](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/plain/comment-notification/content.html)
  * 📔 [Comment notification best practices guide](https://postmarkapp.com/guides/comment-notification-email-best-practices)

### Trial Expiring

  Let users know when their trial is about to expire.

  * 💌 Preview with layout: [Basic](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic/trial-expiring/content.html), [Basic full](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic-full/trial-expiring/content.html), [Plain](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/plain/trial-expiring/content.html)
  * 📔 [Trial expiration email best practices](https://postmarkapp.com/guides/trial-expiration-email-best-practices)

### Trial Expired

  Let users know when their expired trial.

  * 💌 Preview with layout: [Basic](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic/trial-expired/content.html), [Basic full](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic-full/trial-expired/content.html), [Plain](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/plain/trial-expired/content.html)
  * 📔 [Trial expiration email best pracitces](https://postmarkapp.com/guides/trial-expiration-email-best-practices)

### User Invitation

  Help users invite others to use your software.

  * 💌 Preview with layout: [Basic](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic/user-invitation/content.html), [Basic full](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/basic-full/user-invitation/content.html), [Plain](https://s3.amazonaws.com/assets.wildbit.com/postmark/templates/dist/plain/user-invitation/content.html)
  * 📔 [User invitation email best practices](https://postmarkapp.com/guides/user-invitation-email-best-practices)


We've also made sure that these have been tested for consistency in the following email clients:

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
