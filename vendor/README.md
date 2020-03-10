Application dependencies (managed manually or by your favorite dependency management tool like the new built-in, but still experimental, modules feature).

Don't commit your application dependencies if you are building a library.

Note that since 1.13 Go also enabled the module proxy feature (using https://proxy.golang.org as their module proxy server by default). Read more about it here to see if it fits all of your requirements and constraints. If it does, then you won't need the vendor directory at all.