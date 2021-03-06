# Switchboard

[![Build Status](https://travis-ci.org/thusfresh/switchboard.svg?branch=master)](https://travis-ci.org/thusfresh/switchboard)

Switchboard is a framework for processing email. It consists of a core that
maintains a connection to an IMAP server and routes event notifications to a
set of workers. The workers interact with the IMAP server through a simple API
exposed by the Switchboard core.

## Features

- Totally open source &mdash; developers can extend Switchboard or use
  the API to create workers specific to their product.
- Switchboard handles the boilerplate, leaving the logic to you
  &mdash; Switchboard frees you from the plumbing of server-side email
  monitoring and fetching, allowing you to focus on your products
  and services.
- You deploy it &mdash; by running persistent processes on your own server,
  Switchboard can help you avoid mobile OS backgrounding restrictions
  and heavy battery consumption, freeing up the client and leaving
  you in control.

## Documentation

To begin using Switchboard, refer to the website documentation. This will take you from installation, to setting up a Switchboard worker or client.

To get Switchboard up and running, take a look at the [install](http://switchboard.spatch.co/install/) page.

To see an example of how Switchboard can be used, see the [Examples](http://switchboard.spatch.co/examples/) page with examples and walkthroughs on:

- Sending email push notifications
- Storing email image attachments to a Dropbox folder

To see documenation of the Switchboard core Erlang modules and functions, see the [API Docs](http://switchboard.spatch.co/doc/).

## License

Switchboard may be redistributed according to the [BSD 3-Clause License](LICENSE).

Copyright 2014, ThusFresh, Inc.
