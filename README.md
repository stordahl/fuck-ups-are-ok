# Fuck Ups Are Ok

All engineers, programmers, coders, and developers make both big & small mistakes in the code they write. I think [Ben Vinegar](https://syntax.fm/show/434/ben-vinegar-distributed-tracing-and-typescript-migrations#t=06:56) put it best when he said, "Code is messy...That is the univeral experience."

This repo is aimed at logging those mistakes as a resource for new engineers.

## OOPS

- 4/13/22: A small error in some conditional logic I wrote caused hours of debugging for myself and two colleagues 
- 6/30/22: I discovered that a spec of Cypress tests I had written were failing in CI because did not stub the data at all and allowed the tests to rely on production data, which obviously changed
