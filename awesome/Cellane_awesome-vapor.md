# Information comes from [Cellane/awesome-vapor](https://github.com/Cellane/awesome-vapor)
# Awesome Vapor [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="img/vapor-logo.png" align="right" width="150">](https://vapor.codes)

[Vapor](https://vapor.codes) is currently one of the most popular server-side Swift frameworks. It allows you to take the language you already know if you ever developed an iOS application and use it in a whole new way, to develop fast, scalable and reliable back-end systems that integrate easily with a wide range of third party services. This is a curated list of:

- modern libraries that easily integrate with Vapor and follow Vapor’s philosophy of providing simple, clean yet powerful APIs;
- well-written tutorials, books, videos and education materials;
- tools to make your development process simpler and more enjoyable;
- and more!

## Contents

- [How to use](#how-to-use)
- [Libraries](#libraries)
- [Tools](#tools)
- [Services](#services)
- [Education](#education)
  - [Articles](#articles)
  - [Books](#books)
  - [Newsletters](#newsletters)
  - [Videos](#videos)
- [Open-source Projects](#open-source-projects)
- [License](#license)

## How to use

Simply press <kbd>Command</kbd> + <kbd>F</kbd> to search for a keyword. If you’re only interested in entries related to [Vapor 2](https://github.com/Cellane/awesome-vapor/blob/filtered/vapor-2.md) or only to [Vapor 3](https://github.com/Cellane/awesome-vapor/blob/filtered/vapor-3.md), you may use the automatically generated filtered lists available on the `filtered` branch by visiting the links in this sentence.

## Libraries

- ![v3](img/vapor-3.png) [API Error Middleware](https://github.com/skelpo/APIErrorMiddleware) – Vapor middleware for converting thrown errors to JSON responses.
- ![v3](img/vapor-3.png) [APNS](https://github.com/vapor-community/apns) – Vapor APNS for iOS.
- ![v2](img/vapor-2.png) [AWS](https://github.com/nodes-vapor/aws) – Swift wrapper around AWS API.
- ![v2](img/vapor-2.png) ![v3](img/vapor-3.png) [Bugsnag](https://github.com/nodes-vapor/bugsnag) – Report errors with Bugsnag.
- ![v3](img/vapor-3.png) [CouchDB Client](https://github.com/makoni/couchdb-vapor) – Simple CouchDB client for Vapor.
- ![v3](img/vapor-3.png) [CrudRouter](https://github.com/twof/VaporCRUDRouter) – Automatic RESTful CRUD router generation for any Fluent Model.
- ![v3](img/vapor-3.png) [CSRF](https://github.com/vapor-community/CSRF) – A package to add protection to Vapor against CSRF attacks.
- ![v3](img/vapor-3.png) [CSV Framework](https://github.com/skelpo/CSV) – A simple framework to read and write CSV files.
- ![v3](img/vapor-3.png) [Ferno](https://github.com/vapor-community/ferno) – Vapor Firebase Realtime database provider.
- ![v2](img/vapor-2.png) ![v3](img/vapor-3.png) [Flash](https://github.com/nodes-vapor/flash) – Flash messages between views.
- ![v3](img/vapor-3.png) [FluentQuery](https://github.com/MihaelIsaev/FluentQuery) – Build complex raw SQL queries while still using Swift keypaths.
- ![v2](img/vapor-2.png) [Forms](https://github.com/nodes-vapor/forms) – Tools for working with Forms in Vapor.
- ![v2](img/vapor-2.png) [Gatekeeper](https://github.com/nodes-vapor/gatekeeper) – Rate limiting middleware for Vapor.
- ![v3](img/vapor-3.png) [Google Cloud Provider](https://github.com/vapor-community/google-cloud-provider) – Interact with Google Cloud Platform APIs from your Vapor project.
- ![v3](img/vapor-3.png) [Guardian](https://github.com/Jinxiansen/Guardian) – Modern rate-limiting middleware.
- ![v3](img/vapor-3.png) [Imperial](https://github.com/vapor-community/Imperial) – Federated Authentication with OAuth providers.
- ![v2](img/vapor-2.png) ![v3](img/vapor-3.png) [JWT Keychain](https://github.com/nodes-vapor/jwt-keychain) – Easily scaffold a keychain using JWT for Vapor.
- ![v3](img/vapor-3.png) [JWT Middleware](https://github.com/skelpo/JWTMiddleware) – Middleware to Authenticate and Authorize Requests in Vapor.
- ![v3](img/vapor-3.png) [Leaf Error Middleware](https://github.com/brokenhandsio/leaf-error-middleware) – Serve up custom 404 and server error pages for your Vapor App.
- ![v2](img/vapor-2.png) ![v3](img/vapor-3.png) [Leaf Markdown](https://github.com/vapor-community/leaf-markdown) – Markdown renderer for Vapor.
- ![v2](img/vapor-2.png) [Lingo Vapor](https://github.com/vapor-community/Lingo-Vapor) – Vapor provider for Lingo – the Swift localization library.
- ![v3](img/vapor-3.png) [Local Storage](https://github.com/gperdomor/local-storage) – Storage driver using local filesystem.
- ![v3](img/vapor-3.png) [MailCore](https://github.com/LiveUI/MailCore) – Sending e-mails via SMTP, MailGun and SendGrid.
- ![v2](img/vapor-2.png) ![v3](img/vapor-3.png) [Meow](https://github.com/OpenKitten/Meow) – An alternative codable ORM for MongoDB.
- ![v2](img/vapor-2.png) ![v3](img/vapor-3.png) [MongoKitten](https://github.com/OpenKitten/MongoKitten) – MongoDB driver in Swift.
- ![v3](img/vapor-3.png) [Pagination](https://github.com/vapor-community/pagination) – Simple Vapor 3 Pagination.
- ![v2](img/vapor-2.png) [Paginator](https://github.com/nodes-vapor/paginator) – Query pagination for Vapor and Fluent.
- ![v3](img/vapor-3.png) [S3](https://github.com/LiveUI/S3) – Library for accessing the Amazon S3 service (and compatible) with support for most commonly used operations.
- ![v3](img/vapor-3.png) [S3 Storage](https://github.com/anthonycastelli/s3-storage) – Library for simple access to the Amazon S3 service.
- ![v2](img/vapor-2.png) ![v3](img/vapor-3.png) [Sanitize](https://github.com/gperdomor/sanitize) – Powerful model extraction from Vapor JSON requests.
- ![v2](img/vapor-2.png) [Sanitized](https://github.com/nodes-vapor/sanitized) – Safely extract and validate Vapor models from requests.
- ![v2](img/vapor-2.png) ![v3](img/vapor-3.png) [SendGrid Provider](https://github.com/vapor-community/sendgrid-provider) – SendGrid-powered mail backend for Vapor.
- ![v3](img/vapor-3.png) [SimpleFileLogger](https://github.com/hallee/vapor-simple-file-logger) – A simple file logging provider for Vapor.
- ![v2](img/vapor-2.png) [Slugify](https://github.com/nodes-vapor/slugify) – Convenience for sluggifying your strings.
- ![v2](img/vapor-2.png) [Storage](https://github.com/nodes-vapor/storage) – Eases the use of multiple storage and CDN services.
- ![v2](img/vapor-2.png) ![v3](img/vapor-3.png) [Stripe Provider](https://github.com/vapor-community/stripe-provider) – Stripe Provider for Vapor.
- ![v3](img/vapor-3.png) [Submissions](https://github.com/nodes-vapor/submissions) – Conveniences for creating forms and validating (form) submissions.
- ![v2](img/vapor-2.png) ![v3](img/vapor-3.png) [Sugar](https://github.com/nodes-vapor/sugar) – A package of sugar for Vapor.
- ![v3](img/vapor-3.png) [SwifQL](https://github.com/MihaelIsaev/SwifQL) – Easily build flexible and type-safe SQL with pure Swift.
- ![v2](img/vapor-2.png) ![v3](img/vapor-3.png) [SwiftyBeaver Provider](https://github.com/vapor-community/swiftybeaver-provider) – SwiftyBeaver Logging Provider for Vapor, the server-side Swift web framework.
- ![v2](img/vapor-2.png) ![v3](img/vapor-3.png) [Telesign Provider](https://github.com/vapor-community/telesign-provider) – A Telesign provider for Vapor.
- ![v2](img/vapor-2.png) [UAPusher](https://github.com/nodes-vapor/push-urban-airship) – Send push notifications using Urban Airship.
- ![v3](img/vapor-3.png) [Vapor Mailgun Service](https://github.com/vapor-community/VaporMailgunService) – A service to be used with Vapor to send emails.
- ![v2](img/vapor-2.png) [Vapor OAuth](https://github.com/brokenhandsio/vapor-oauth) – OAuth2 Provider Library for Vapor.
- ![v2](img/vapor-2.png) [Vapor OAuth Fluent](https://github.com/brokenhandsio/vapor-oauth-fluent) – Fluent Implementations For Vapor OAuth.
- ![v3](img/vapor-3.png) [Vapor reCAPTCHA](https://github.com/gotranseo/vapor-recaptcha) – Validate Google reCAPTCHAs using Vapor.
- ![v3](img/vapor-3.png) [Vapor Request Storage](https://github.com/skelpo/vapor-request-storage) – A replacement for `request.storage` which was available in Vapor 1 & 2.
- ![v2](img/vapor-2.png) ![v3](img/vapor-3.png) [Vapor Security Headers](https://github.com/brokenhandsio/VaporSecurityHeaders) – Harden Your Security Headers For Vapor.
- ![v3](img/vapor-3.png) [Vapor Test Tools](https://github.com/LiveUI/VaporTestTools) – Helper designed to make testing your endpoints in Vapor 3 pain-free.
- ![v2](img/vapor-2.png) [VaporAPNS](https://github.com/matthijs2704/vapor-apns) – Simple APNS Library for Vapor (Swift).
- ![v3](img/vapor-3.png) [VaporExt](https://github.com/vapor-community/vapor-ext) – A collection of Swift extensions for wide range of Vapor data types and classes.
- ![v3](img/vapor-3.png) [WKHTMLTOPDF](https://github.com/MihaelIsaev/wkhtmltopdf) – Build PDF files from Leaf templates or web pages through the `wkhtmltopdf` CLI tool.
- ![v3](img/vapor-3.png) [XMLCoding](https://github.com/LiveUI/XMLCoding) – XML encoder and decoder.

## Tools

- [Ether](https://github.com/Ether-CLI/Ether) – A Command-Line Interface for the Swift Package Manager.
- [Heroku buildpack: curl with HTTP/2 support](https://github.com/vzsg/heroku-buildpack-curl-http2) :star:5
- [Ice](https://github.com/jakeheis/Ice) – A developer friendly package manager for Swift; 100% compatible with Swift Package Manager.
- [Sourcery](https://github.com/krzysztofzablocki/Sourcery) – Meta-programming for Swift, stop writing boilerplate code.
- ![v2](img/vapor-2.png) [Sourcery Templates](https://github.com/nodes-vapor/sourcery-templates) – Building Vapor projects using meta programming with Sourcery.
- ![v3](img/vapor-3.png) [Sublimate](https://github.com/gabrielepalma/sublimate) – Fast prototyping with synchronization and authentication based on Sourcery.
- [Swifter](https://github.com/LiveUI/Swifter) – A macOS tool to help you manage your Xcode projects and give you a quick access to DerivedData folder cleaning and management.

## Services

- [Vapor Cloud](https://vapor.cloud)

## Education

### Articles

- ![v3](img/vapor-3.png) [Deep Dive into Setup and Deployment for Heroku and Ubuntu](https://learningswift.brightdigit.com/vapor-heroku-ubuntu-setup-deploy/)
- ![v3](img/vapor-3.png) [Developing and deploying Vapor 3 with Docker](https://tobygriffin.dev/2018/05/14/developing-deploying-vapor-docker.html)
- ![v2](img/vapor-2.png) [Fluent And Controllers - Part 1](https://geeks.brokenhands.io/blog/posts/fluent-and-controllers-part-1/)
- ![v2](img/vapor-2.png) [Fluent Part 2 - Parent-Child Relationships](https://geeks.brokenhands.io/blog/posts/fluent-part-2-parent-child-relationships/)
- ![v2](img/vapor-2.png) [Fluent Part 3 - Sibling Relationships](https://geeks.brokenhands.io/blog/posts/fluent-part-3-sibling-relationships/)
- ![v2](img/vapor-2.png) [Fluent Part 4 - Persistence With MySQL And Fluent Patterns](https://geeks.brokenhands.io/blog/posts/fluent-part-4-persistence-with-mysql-and-fluent-patterns/)
- ![v2](img/vapor-2.png) [Getting started with Vapor](https://geeks.brokenhands.io/blog/posts/getting-started-with-vapor/)
- ![v3](img/vapor-3.png) [How to test controllers by mocking dependencies in Vapor 3 and Swift](https://mikemikina.com/blog/how-to-test-controllers-by-mocking-dependencies-in-vapor-3-and-swift/)
- ![v2](img/vapor-2.png) [Leaf Part 1 - Getting Started](https://geeks.brokenhands.io/blog/posts/leaf-part-1-getting-started/)
- ![v2](img/vapor-2.png) [Vapor 2 with Docker](https://tobygriffin.dev/2018/01/24/vapor-2-with-docker.html) – Definitive Docker guide for Vapor 2.
- ![v3](img/vapor-3.png) [Vapor 3 with Docker](https://tobygriffin.dev/2018/01/24/vapor-3-with-docker.html) – Definitive Docker guide for Vapor 3.
- ![v3](img/vapor-3.png) [Vapor 3 Tutorials](https://mihaelamj.github.io/Vapor%20%203%20Tutorial/) – Big collection of small tutorials.
- ![v3](img/vapor-3.png) [Transforming from Vapor 2 to Vapor 3](https://www.skelpo.com/blog/vapor2-to-vapor3/) – Transitioning from Vapor 2 to Vapor 3 with a real world project.
- ![v3](img/vapor-3.png) [Tutorials for Beginner to Advanced](https://medium.com/@martinlasek) – Written tutorials for Beginner to Advanced.
- ![v3](img/vapor-3.png) [Using the dependency injection framework for testing in Vapor 3 and Swift](https://mikemikina.com/blog/using-the-dependency-injection-framework-for-testing-in-vapor-3-and-swift/) – How to use dependency injection framework which will help you manage dependencies and mock them inside your tests.
- ![v3](img/vapor-3.png) [Watermarking photos with ImageMagick, Vapor 3 and Swift on macOS and Linux](https://mikemikina.com/blog/watermarking-photos-with-imagemagick-vapor-3-and-swift-on-macos-and-linux/) – Tutorial on how to use the ImageMagick library in Swift.

### Books

- ![v3](img/vapor-3.png) [Server Side Swift with Vapor](https://store.raywenderlich.com/products/server-side-swift-with-vapor)
- ![v3](img/vapor-3.png) [Server-Side Swift (Vapor Edition)](https://www.hackingwithswift.com/store/server-side-swift)

### Newsletters

- [VaporNation](http://vapornation.news) – Weekly Vapor newsletter with all things Vapor.

### Videos

- ![v3](img/vapor-3.png) [Server Side Swift with Vapor](https://www.raywenderlich.com/4493-server-side-swift-with-vapor/lessons/1)
- ![v3](img/vapor-3.png) [Vapor - Beginner to Advanced](https://www.youtube.com/channel/UCoLEXFUHIKXunm9QJjsAftw/videos)

## Open-source Projects

- ![v2](img/vapor-2.png) [CocoaHeads Russia](https://github.com/cocoaheadsru/server) – Server side API for the CocoaHeads Russia app.
- ![v2](img/vapor-2.png) [Server-side Swift Racing](https://github.com/MartinLasek/serversideswift.racing) – Statistics on growth trend of all major server-side swift frameworks.
- ![v2](img/vapor-2.png) [Starred Search](https://github.com/mjmsmith/starredsearch) – Search READMEs in starred GitHub repositories.
- ![v2](img/vapor-2.png) ![v3](img/vapor-3.png) [SteamPress](https://github.com/brokenhandsio/SteamPress) – A Blogging Engine and Platform written in Swift for use with the Vapor Framework.
- ![v3](img/vapor-3.png) [User Manager Service](https://github.com/skelpo/UserManager) – A small, useful user manager made for production application setups.
- ![v2](img/vapor-2.png) [VaporBerlin](https://github.com/MartinLasek/vaporberlinBE) – The backend of meetup website for VaporBerlin.
- ![v2](img/vapor-2.png) [Vapor Chat](https://github.com/vapor-community/chat-example) – A real-time chat client built with Vapor that features an iOS app.
- ![v2](img/vapor-2.png) [ServerSide.swift](http://www.serversideswift.info/) – Conference website for the world wide server-side Swift conference.
- ![v3](img/vapor-3.png) [Swifttube](https://github.com/ahmetws/swifttube) –  Curates iOS conference videos in one place.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, _Milan Vit_ has waived all copyright and related or neighbouring rights to this work.

