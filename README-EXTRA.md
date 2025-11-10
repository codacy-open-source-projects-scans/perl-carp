# License  file

The project had no explicit license information. There is a short note in the README file and on the project page:

```
This module is free software; you can redistribute it and/or modify it under the same terms as Perl itself.
```

I added the explicit license file so that GitHub can detect and return the license correctly via API.

```bash
curl https://raw.githubusercontent.com/Perl/perl5/refs/heads/blead/Copying > License
```

# But why?

This software is widely used, but none of the popular Perl community organisations have it:

- https://github.com/Dual-Life
- https://github.com/Perl-Toolchain-Gang

Finally, I have found it frustrating when it comes to analysing software for
the SourceMation platform I'm working on. I can create an additional source
downloader for CPAN, but it's safer and easier to have it as a separate
git-based repository.
