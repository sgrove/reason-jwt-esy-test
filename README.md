# reason-jwt-test


[![CircleCI](https://circleci.com/gh/yourgithubhandle/reason-jwt-test/tree/master.svg?style=svg)](https://circleci.com/gh/yourgithubhandle/reason-jwt-test/tree/master)


**Contains the following libraries and executables:**

```
reason-jwt-test@0.0.0
│
├─test/
│   name:    TestReasonJwtTest.exe
│   main:    TestReasonJwtTest
│   require: reason-jwt-test.lib
│
├─library/
│   library name: reason-jwt-test.lib
│   namespace:    ReasonJwtTest
│   require:
│
└─executable/
    name:    ReasonJwtTestApp.exe
    main:    ReasonJwtTestApp
    require: reason-jwt-test.lib
```

## Developing:

```
npm install -g esy
git clone <this-repo>
esy install
esy build
```

## Running Binary:

After building the project, you can run the main binary that is produced.

```
esy x ReasonJwtTestApp.exe 
```

## Running Tests:

```
# Runs the "test" command in `package.json`.
esy test
```
# reason-jwt-esy-test
