- Database design
  - <https://lagunita.stanford.edu/courses/Engineering/db/2014_1/about>
- Indexes, UUIDs, full-text search
  - <https://czep.net/17/full-text-search.html>
  - <http://rachbelaid.com/postgres-full-text-search-is-good-enough/>
  - <https://tomharrisonjr.com/uuid-or-guid-as-primary-keys-be-careful-7b2aa3dcb439>
- Data migrations
  - <https://docs.djangoproject.com/en/2.2/topics/migrations/#data-migrations>
- Documentation and comments
  - <https://blog.codinghorror.com/when-good-comments-go-bad/>
  - <https://blog.codinghorror.com/coding-without-comments/>
- Algorithms
  - <https://www.coursera.org/learn/algorithms-part1>
  - <https://projecteuler.net>
  - <https://algs4.cs.princeton.edu/code/>
- Performance (database, back end, front end)
  - <https://marmelab.com/blog/2017/02/06/react-is-slow-react-is-fast.html>
  - <https://kylebebak.github.io/post/clustering-location-history-records>
  - <https://wiki.python.org/moin/TimeComplexity>
- React
  - <https://marmelab.com/blog/2019/03/13/react-dependency-injection.html>
  - <https://reactjs.org/docs/thinking-in-react.html>
- Data structures (lists, queues, stacks and dicts)
  - <https://wiki.python.org/moin/TimeComplexity>
- API design
  - <https://stackoverflow.com/questions/4024271/rest-api-best-practices-where-to-put-parameters>
  - <https://stackoverflow.com/questions/16086513/using-query-string-in-rest-web-services>
  - <https://stackoverflow.com/questions/3868705/implementing-url-slug-functionality-in-a-website?rq=1>
- DRF, FastAPI
  - <http://www.cdrf.co/>
  - <http://www.django-rest-framework.org/>
  - <https://github.com/kylebebak/fastapi_graphql>
- Pagination, cursors
  - <https://www.django-rest-framework.org/api-guide/pagination/#cursorpagination>
- SQL, specifically for Postgres
  - <http://postgresguide.com/>
- Redux and managing state
  - <https://marmelab.com/blog/2017/02/06/react-is-slow-react-is-fast.html>
- Caching API responses
  - <https://docs.djangoproject.com/en/2.2/topics/cache/>
- TypeScript
  - <https://github.com/fortana-co/request.js>
  - <https://github.com/fortana-co/react-dropzone-uploader>
  - <https://github.com/kylebebak/talks-start-using-typescript>
- Promises
  - <https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-promise-27fc71e77261>
  - <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise>
- Asyncio
  - <https://stackoverflow.com/questions/49005651/how-does-asyncio-actually-work>
  - <https://github.com/kylebebak/fastapi_graphql>
- Mypy
  - <http://mypy-lang.org/>
  - <https://github.com/kylebebak/fastapi_graphql>
- Debugging
  - more than anything, this depends on experience, and setting up a really short feedback loop for doing experiments with your code
  - it's worth the up-front cost to set up short feedback loops in your dev environment
- GraphQL
  - <https://github.com/kylebebak/fastapi_graphql>
  - <https://github.com/kylebebak/talks-start-using-typescript>
- HTML, CSS, SASS, Flexbox, CSS modules
- Polling and real-time web, websockets
- Text editor
  - <https://web.archive.org/web/20170401165039/https://fluff.info/terrible/>
- Git
  - rewriting history and undoing mistakes: `log`, `reflog`, `branch`, `diff`, `checkout`, `reset`, `reset --hard`, `reset --soft`, `cherry-pick`, `revert`, `stash`, `stash pop`, and just maybe `rebase`
  - forking projects: `remote`, `remote add`, `remote remove`
- Docker
  - <https://www.caktusgroup.com/blog/2017/03/14/production-ready-dockerfile-your-python-django-app/>
- Application folder structure
  - keep it as simple as possible
  - `src` directory in root of repo, with source code
- Redis (pub/sub, streams)
  - <https://redis.io/topics/streams-intro>
- Video streaming
  - <https://redis.io/topics/streams-intro>
- File uploads
  - <https://react-dropzone-uploader.js.org>
- Testing
- API testing, integration tests
  - <https://www.django-rest-framework.org/api-guide/testing/>
  - <https://rbcs-us.com/documents/Why-Most-Unit-Testing-is-Waste.pdf>
- Testing reducers and front-end utils
- Philosophy of testing
  - <https://kylebebak.github.io/post/cargo-cult-testing>
- Pre-rendering for SPAs
  - <https://developers.google.com/search/docs/guides/dynamic-rendering>
- Heuristics for choosing 3rd party libraries
  - number of **meaningful** contributors, number of issues, ratio of open issues to closed issues, recent commits, handling of important issues, documentation, live examples, TypeScript compatibility
  - clone the repo, open it in your text editor, and `yarn start` or `yarn dev` or whatever
- Philosophy of programming
  - <https://web.archive.org/web/20170401165039/https://fluff.info/terrible/>
  - <https://www.python.org/dev/peps/pep-0020/>
  - <https://blog.bradfieldcs.com/you-are-not-google-84912cf44afb>
  - <https://www.dreamsongs.com/RiseOfWorseIsBetter.html>
  - <https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/>
  - <http://stackoverflow.com/questions/2998215/if-python-is-interpreted-what-are-pyc-files/2998544>
  - <https://eev.ee/blog/2012/04/09/php-a-fractal-of-bad-design/>
- Security (CORS, SOP, CSRF, XSS)
  + <https://security.stackexchange.com/questions/97825/is-cors-helping-in-anyway-against-cross-site-forgery>
  + <https://softwareengineering.stackexchange.com/questions/216605/how-do-web-servers-enforce-the-same-origin-policy>
  + <https://stackoverflow.com/questions/13897472/how-do-third-party-tracking-cookies-work>
  + <https://kylebebak.github.io/post/browser-security-worse-is-better>
  + <http://cryto.net/~joepie91/blog/2016/06/13/stop-using-jwt-for-sessions/>
  + <https://blogs.msdn.microsoft.com/ieinternals/2009/08/28/same-origin-policy-part-1-no-peeking/>
  + <https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS#Access-Control-Allow-Origin>
  + <https://www.owasp.org/index.php/Cross-site_Scripting_(XSS)>
  + <https://blog.codinghorror.com/protecting-your-cookies-httponly/>

## Courses

- Algorithms, Part I and Part 2: <https://www.coursera.org/learn/algorithms-part1>
- Introduction to Databases: <https://lagunita.stanford.edu/courses/Engineering/db/2014_1/about>

## Books

- The Mythical Man Month (Fred Brooks)
  + a classic on the human aspects of software development
- Symbols, Signals and Noise (J.R. Pierce)
  + an overview of [information theory and its founder Claude Shannon](https://en.wikipedia.org/wiki/Claude_Shannon); storage, compression, and transmission of information
- Sets, Functions, and Logic (Keith Devlin)
  + sets, logic, number theory, __problem-solving__
- How to Prove It (Daniel J. Velleman)
  + deeper dive into sets, logic, number theory and __problem-solving__
- Don't Make Me Think (Steve Krug)
  + a classic on product design and UX
