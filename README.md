# Cloudy Stuff

## Programming Languages

The key thing here is to just pick anything and spend time learning and getting comfortable with the programming fundamentals. Once you're comfortable, writing in another language is largely just a case of googling the syntax to achieve the construct you want and you'll quickly transition.

With that said, there are a few key players in the cloud automation space. 

---

### Python

Python is massively popular with a very wide range of uses. 
It also has a fairly forgiving syntax and is quite succinct. 
Its versatility, enormous library ecosystem, ease of learning and ability to rapidly develop prototypes make this one of the obvious first choices that casts the widest net.

---

### Golang

Relatively new, this language focuses on being extremely simple, easy to learn and straightforward to work with. Go has seen wide adoption particularly in the cloud native tooling, used widely in kubernetes, docker, hashicorp products such as terraform as well as service meshes such as istio and linkerd2. While nowhere near as widely used as python, it is definitely one to keep on your radar, particularly for learning programming fundamentals.

---

### Others

Again, the language doesn't really matter. Powershell is widely used in the cloud. Rust is making big waves particularly when the python performance is lacking and you need the power of a low level systems language. Java and its derivatives Kotlin and Scala will be around for a long time too. Programming is all very similar.

---

### Resources

Subreddits:

* https://www.reddit.com/r/programming
* https://www.reddit.com/r/learnprogramming
* https://www.reddit.com/r/Python
* https://www.reddit.com/r/learnpython

Youtube:

* https://www.youtube.com/c/CodingTech 

Public Slacks:

* DevChat
* Python Developers
* (also search for any specific language, there is probably a slack/discord community)

## Cloud Common Tools

---

### Source Control

For the most part, there is only really git used, and it MUST be known. Regardless of your field, you must learn git and always use it even if you don't intend to share your code on GitHub.

Learn the basics of the following commands for git via the commandline:

* git init
* git branch
* git checkout
* git add
* git commit
* git push
* git pull
* git merge

You can create aliases for these, best way to learn is to just print out a cheet sheet, laminate it and glue it to your desk/wall/face.

When developing code, get into the habit of making a repo in GitHub, cloning it to your machine, make a new branch for the day. commit work to the branch, push the branch to github. Raise a pull request to merge your branch to main/master, then approve the merge. Why? This is the basics of the git work flow. In the real world, your team would review your pull request, master would be locked from any direct interaction, and automation would kick off when you raise a pull request.

---

### Resources

Cheat Sheet:

* https://education.github.com/git-cheat-sheet-education.pdf
* https://try.github.io/
* https://learngitbranching.js.org/

---

### Continuous Integration/Continuous Delivery (CI/CD)

Like programming languages, there are a million CI/CD tools. They basically all do the same thing and its just a case of feature sets, licencing, SAAS vs self hosting. All of which are business lead decisions you wont really be making.

For learning, stick to Github actions. Use actions to create a yaml pipeline, this pipeline could automatically run tests when someone raises a pull request, or when a successful merge to master occurs, it could rebuild a docker image or recompile your code into some sort of package, which could then trigger another process to upload it to a web server or something. This is a CICD proccess. Continuous integration handles automated testing and compilation and packaging of code, and continuous delivery/deployment then kicks in to deploy that package into various cascading test environments, eventually into "production". This can get really complex so some videos are a good idea here.

---

### Resources

Cheat Sheet:

* https://docs.github.com/en/actions
* https://www.reddit.com/r/devops

---

### Linux

Servers are Linux, the cloud is Linux, containers are Linux. Its just all Linux. Get comfortable (you don't need to be an expert) with the linux bash terminal. Use Windows Subsystem for Linux 2 (WSL2) if you're a windows user, Mac comes with a bash terminal by default.

Skills to start:

* Install a package
* Update the OS
* navigate folder structures
* copy files
* move files
* delete files
* rename files
* execute a file
* edit a file

---

### Resources

Cheat Sheet:

* https://cheatography.com/davechild/cheat-sheets/linux-command-line/

Subreddits:

* https://www.reddit.com/r/linux
* https://www.reddit.com/r/linux4noobs
* https://www.reddit.com/r/linuxadmin
* https://www.reddit.com/r/sysadmin

---

### Cloud Provider

It doesn't matter which you pick, go and play with one. The various official docs sites are incredible for all 3 providers and a great start. All 3 provide student and professional education and certification paths. Seek out your lecturers to get cloud access and try and deploy a simple serverless web app, give it HTTPS/TLS certificate too! maybe even a custom domain name.

always set budgets first (google how), some cloud items like firewalls are massively expensive (>£1000 a month)

Each of the subreddits below has llots of resources in the side bar for further reading.

---

### Resources

Official Documentation:

* https://docs.microsoft.com/en-us/azure/?product=featured
* https://cloud.google.com/docs
* https://docs.aws.amazon.com/

Subreddits:

* https://www.reddit.com/r/azure
* https://www.reddit.com/r/gcp
* https://www.reddit.com/r/aws