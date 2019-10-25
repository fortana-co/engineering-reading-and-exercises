# Fortana's Engineering Reading/Exercise List

Hello Fortana engineers! Make your own branch (with your name) in this repo and check things off as you read/do them. If you want to add, or remove, or replace, or add observations to something, submit a PR against `master`.

This list should change as the company changes. We should talk about things on this list!

## Quick Reads

### Frontend

- React
  - [ ] <https://marmelab.com/blog/2019/03/13/react-dependency-injection.html>
  - [ ] <https://reactjs.org/docs/thinking-in-react.html>
- Redux and managing state
  - [ ] <https://marmelab.com/blog/2017/02/06/react-is-slow-react-is-fast.html>
- Caching API responses
  - [ ] <https://github.com/kylebebak/talks-start-using-typescript>
- TypeScript
  - [ ] <https://github.com/fortana-co/request.js>
  - [ ] <https://github.com/fortana-co/react-dropzone-uploader>
  - [ ] <https://github.com/kylebebak/talks-start-using-typescript>
- Promises
  - [ ] <https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-promise-27fc71e77261>
  - [ ] <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise>
- GraphQL
  - [ ] <https://github.com/kylebebak/talks-start-using-typescript>
- Polling and real-time web, websockets
  - [ ] <https://www.figma.com/blog/how-figmas-multiplayer-technology-works/>, everything in this blog is worth reading
  - [ ] <https://www.figma.com/blog/realtime-editing-of-ordered-sequences/>
  - [ ] <https://github.com/elementary-robotics/cloud-frontend>, `Video.tsx` and `StreamListener.tsx`
  - [ ] <https://www.figma.com/blog/rust-in-production-at-figma/>, limitations of event loops for async servers
  - [ ] [CRDTs](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type)
- File uploads
  - [ ] <https://react-dropzone-uploader.js.org>
- HTML, CSS, SASS, Flexbox, CSS modules
- Application folder structure
  - KISS: `src` directory in root of repo, with source code
  - [ ] <https://github.com/elementary-robotics/cloud-frontend>
- Pre-rendering for SPAs
  - [ ] <https://developers.google.com/search/docs/guides/dynamic-rendering>

### Backend

- API design
  - [ ] <https://stackoverflow.com/questions/4024271/rest-api-best-practices-where-to-put-parameters>
  - [ ] <https://stackoverflow.com/questions/16086513/using-query-string-in-rest-web-services>
  - [ ] <https://stackoverflow.com/questions/3868705/implementing-url-slug-functionality-in-a-website?rq=1>
  - [ ] <https://docs.djangoproject.com/en/2.2/topics/cache/>
  - pagination, cursors: <https://www.django-rest-framework.org/api-guide/pagination/#cursorpagination>
- DRF
  - [ ] <http://www.cdrf.co/>
  - [ ] <http://www.django-rest-framework.org/>
- FastAPI, Asyncio
  - [ ] <https://stackoverflow.com/questions/49005651/how-does-asyncio-actually-work>
  - [ ] <https://github.com/kylebebak/fastapi_graphql>
- GraphQL
  - [ ] <https://github.com/kylebebak/fastapi_graphql>
- Mypy
  - [ ] <http://mypy-lang.org/>
- Redis (pub/sub, streams)
  - [ ] <https://redis.io/topics/streams-intro>
- Docker
  - [ ] <https://www.caktusgroup.com/blog/2017/03/14/production-ready-dockerfile-your-python-django-app/>

### Databases

- SQL, specifically for Postgres
  - [ ] <http://postgresguide.com/>
- Database design
  - [ ] <https://lagunita.stanford.edu/courses/Engineering/db/2014_1/about>
- Indexes, UUIDs, full-text search
  - [ ] <https://czep.net/17/full-text-search.html>
  - [ ] <http://rachbelaid.com/postgres-full-text-search-is-good-enough/>
  - [ ] <https://tomharrisonjr.com/uuid-or-guid-as-primary-keys-be-careful-7b2aa3dcb439>
- Data migrations
  - [ ] <https://docs.djangoproject.com/en/2.2/topics/migrations/#data-migrations>

### Algorithms and Performance

- Data structures (lists, queues, stacks and dicts)
  - [ ] <https://github.com/kylebebak/python_algorithms>
  - [ ] <https://wiki.python.org/moin/TimeComplexity>
  - [ ] <https://anandology.com/python-practice-book/>
- Performance (database, back end, front end)
  - [ ] <https://marmelab.com/blog/2017/02/06/react-is-slow-react-is-fast.html>
  - [ ] <https://kylebebak.github.io/post/clustering-location-history-records>
  - [ ] <https://wiki.python.org/moin/TimeComplexity>
- Algorithms
  - [ ] <https://anandology.com/python-practice-book/>
  - [ ] <https://projecteuler.net>
  - [ ] <https://algs4.cs.princeton.edu/code/>
  - [ ] <https://www.coursera.org/learn/algorithms-part1>

### Web Security (CORS, SOP, CSRF, XSS)

- [ ] <https://security.stackexchange.com/questions/97825/is-cors-helping-in-anyway-against-cross-site-forgery>
- [ ] <https://softwareengineering.stackexchange.com/questions/216605/how-do-web-servers-enforce-the-same-origin-policy>
- [ ] <https://stackoverflow.com/questions/13897472/how-do-third-party-tracking-cookies-work>
- [ ] <https://kylebebak.github.io/post/browser-security-worse-is-better>
- [ ] <http://cryto.net/~joepie91/blog/2016/06/13/stop-using-jwt-for-sessions/>
- [ ] <https://blogs.msdn.microsoft.com/ieinternals/2009/08/28/same-origin-policy-part-1-no-peeking/>
- [ ] <https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS#Access-Control-Allow-Origin>
- [ ] <https://www.owasp.org/index.php/Cross-site_Scripting_(XSS)>
- [ ] <https://blog.codinghorror.com/protecting-your-cookies-httponly/>

### Testing

- API testing
  - [ ] <https://www.django-rest-framework.org/api-guide/testing/>
- Integration tests  
  - [ ] <https://github.com/kylebebak/Requester/tree/master/tests>
  - [ ] <https://rbcs-us.com/documents/Why-Most-Unit-Testing-is-Waste.pdf>
  - [ ] <https://kylebebak.github.io/post/cargo-cult-testing>
  - if you want good coverage __you need integration tests__
- Tests that never fail don't tell you anything
- Test behavior, not implementation
- Test coverage percentage is meaningless on its own, and there's no such thing as 100% test coverage
- Prioritize unit tests for functions that are subtle, difficult, or crucial to the system

### General

- Text editor
  - **master your text editor**, because you use it more than anything else
  - [ ] <https://web.archive.org/web/20170401165039/https://fluff.info/terrible/>
- Git
  - after your text editor, Git is probably the most important tool to master
  - compare files, travel through time, rewrite history and undo mistakes: `log`, `reflog`, `branch`, `diff`, `checkout`, `reset`, `reset --hard`, `reset --soft`, `cherry-pick`, `revert`, `stash`, `stash pop`, and just maybe `rebase`
  - forking projects: `remote`, `remote add`, `remote remove`
- Debugging
  - more than anything, this depends on experience, and setting up a really short feedback loop for doing experiments with your code
  - it's worth the up-front cost to set up a __good dev environment__
- Choosing libraries
  - number of **meaningful** contributors, number of issues, ratio of open issues to closed issues, handling of important issues, recent commits, documentation, live examples, TypeScript compatibility
  - clone the repo, open it in your text editor, and `yarn start` or `yarn dev` or whatever
- Documentation and comments
  - [ ] <https://blog.codinghorror.com/when-good-comments-go-bad/>
  - [ ] <https://blog.codinghorror.com/coding-without-comments/>
  - comments explain __why__, not __how__ (the code explains how)
- What makes software good (or bad)?
  - [ ] <https://web.archive.org/web/20170401165039/https://fluff.info/terrible/>
  - [ ] <https://www.python.org/dev/peps/pep-0020/>
  - [ ] <https://blog.bradfieldcs.com/you-are-not-google-84912cf44afb>
  - [ ] <https://www.dreamsongs.com/RiseOfWorseIsBetter.html>
  - [ ] <https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/>
  - [ ] <https://eev.ee/blog/2012/04/09/php-a-fractal-of-bad-design/>
  - [ ] <https://rbcs-us.com/documents/Why-Most-Unit-Testing-is-Waste.pdf>
  - [ ] <http://calteches.library.caltech.edu/51/2/CargoCult.htm>
- Other
  - [ ] <http://stackoverflow.com/questions/2998215/if-python-is-interpreted-what-are-pyc-files/2998544>

## Courses

- [ ] Algorithms, Part I and Part 2: <https://www.coursera.org/learn/algorithms-part1>
- [ ] Introduction to Databases: <https://lagunita.stanford.edu/courses/Engineering/db/2014_1/about>

## Books

- [ ] The Mythical Man Month (Fred Brooks)
  - a classic on the [human elements of software development](https://en.wikipedia.org/wiki/The_Mythical_Man-Month)
- [ ] Symbols, Signals and Noise (J.R. Pierce)
  - an overview of [information theory and its founder Claude Shannon](https://en.wikipedia.org/wiki/Claude_Shannon); storage, compression, and transmission of information
- [ ] Sets, Functions, and Logic (Keith Devlin)
  - sets, logic, number theory, **problem-solving**
- [ ] How to Prove It (Daniel J. Velleman)
  - deeper dive into sets, logic, number theory and **problem-solving**
- [ ] Don't Make Me Think (Steve Krug)
  - a classic on product design and UX
