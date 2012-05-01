# New Organizing Institute New Media Bootcamp Wrapper

This repository contains the basic New Media Bootcamp website and email wrapper used by the [New Organizing Institute](http://neworganizing.com) alongside other training organizations who teach New Media best practices.

It is vital that this template is **easy to modify by very inexperienced web developers** and **easy to understand with limited explanation**.

## Setup Information

These wrappers are built to work with individual [BSDTools](http://bsdtools.com) instances and as such include fields and links used by the BSDTools platform.

Each instance needs to be pre-loaded with the websitetemplate.html loaded as the default 'Page Wrapper' and emailtemplate.html setup as the default 'Mailing/Message Template.'

There needs to be a homepage called 'home' located at {instance domain}/page/content/home/ and a default signup form that has 'email' and 'zip' as required fields located at {instance domain}/page/s/. These two links will be incorporated in the navigation and quick-signup fields on the website template.

The mailer needs a default Message Template that needs to include BSD-relevant unsubscribe information.

Static content such as example logos and javascript needs to be externally hosted, either in BSD (recommended for the website logos which allow relative URLs) or on a central file storage service such as Amazon S3.

All content must include disclaimers specifying that they are part of a simulation and fictional. At no point should the open-source wrapper imply endorsement by any one organization, although adding an organization name to the disclaimer would be acceptable.

## Credits

Nick Catalano ([NickCatal](https://github.com/nickcatal) / [@nickcatal](http://twitter.com/nickcatal)

Jared ([imjared](https://github.com/imjared))

(feel free to insert your name here)

## License

Unless otherwise noted the templates in this project are in the public domain and can be used in any way. Some elements such as social tags and logos may have alternative licensing restrictions. This code is provided AS IS.