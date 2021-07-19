# AWS S3 Just for Storage

A guide to set up Amazon Web Services' Simple Storage Service to house some
content without using it for user uploads in an application.

## Setup

### Create your AWS S3 Bucket

Navigate to the [AWS Console], create an account if you haven't used AWS yet, or
log in if you have. Once you are logged in there, you should have arrived on the
Amazon S3 Buckets page.

![aws-s3-buckets-page]

Click on the orange button "Create Bucket", enter a name, choose a region, and
leave all other options as default. It you are planning on using this bucket to
provide hosting for some of the resources you have for seeders or something,
you'll want to uncheck the checkbox that says "**Block *all* public access**".
You'll need to also check the checkbox that appears after you've unchecked the
previous one that says that you acknowledge that the "current settings might
result in this bucket and the objects within becoming public."

Scroll to the bottom and click "Create Bucket". You might run into an error
where the name is already taken, so be sure to choose a fairly unique name. If
your bucket was created successfully, then you'll be taken back to the Amazon S3
Buckets page.



[AWS Console]: https://s3.console.aws.amazon.com/s3/home
[aws-s3-buckets-page]: ./assets/aws-s3-buckets-page.png
