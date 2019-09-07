# HW1

Create a private repo HW1-510, with TAs, and instructor as collobrators. 

## REST Client (60 points)

Ensure you have the latest version of 
https://github.com/CSC-510/REST cloned.

Update the repo to point to your HW1-510 repo:

```bash
git remote set-url origin https://github.ncsu.edu/USERNAME/REPOSITORY.git
```

Ensure you complete the following tasks:

* Write code for listBranches in a given repo under an owner. See [list branches](https://developer.github.com/v3/repos/#list-branches)
* Write code for [create a new repo](https://developer.github.com/v3/repos/#create)
* Write code for [creating an issue](https://developer.github.com/v3/issues/#create-an-issue) for an existing repo.
* Write code for [editing a repo](https://developer.github.com/v3/repos/#edit) to enable wiki support.

You can verify you have a correct implementation by running: `npm test`.

![mocha test](https://github.com/CSC-510/REST/raw/master/img/expected.png)

## REST SERVER (20 points)

Complete the rest server exercise. In a *screencast*, demonstrate that your service works following a set of commands such as these:

```bash
# Post content to server. Service returns retrieval link.
$ curl --request POST -H "Content-Type: application/json" --data '{"coffee":1,"milk":1,"sugar":1,"chocolate":1}' http://localhost:3000/share
{"success":true,"link":"http://localhost:3000/pgiPc2"}
# Retrieve content
$ curl http://localhost:3000/pgiPc2
{"coffee":1,"milk":1,"sugar":1,"chocolate":1}
# A second read will result in "Not Found" message.
$ curl http://localhost:3000/pgiPc2
{"success":false,"error":404,"message":"Not Found"}
```

## Concepts (20 points)

1. Explain some additional concerns related to using REST apis.
2. Compare and contrast the benefits and disadvantages of using a RESTful architecture vs. a graph query language. See [http://graphql.org/](http://graphql.org/) for details.

## Submission

Submit the link to your homework [here](https://forms.gle/bscyT3pr7EYN6oBc7).

* README.md describing your submission and answers.
* Your code should be executable. Include everything needed (package.json, index.js, server/index.js, etc. -- but not `node_modules/`!!!)
* Include a link to your screencast.

**Due:** Friday, Sept 13th before midnight.
