!SLIDE center

General Tips for Reviewees

* Code Review is like editing a rough draft
* Smaller Pull Requests are better. It is much easier to do ten 100-line reviews than one 1000-line review.
* “Pre-review” your code. Take a quick glance over your code and see if there’s anything you would push back on if you were reviewing this code and fix it before sending for review.
* Don't take every suggestion as a mandate
* Be prepared to defend a decision
* You are not your code

!SLIDE center

Creating a Pull Request

* The ealier the better
* Creating a meaningful title will help the reviewer
* Clearly layout a QA plan
  * Try to include steps for other paths besides the happy path
* Think about any requirements for deploying this code
  * What would you need to know if you were deploying it

!SLIDE center transition=uncover

Tips for Code Reviewers

# Point out the good stuff

* Pointing out good code can be just as benificial to an engineer as
finding something wrong


# Don't be afraid to review changes to code you've never seen before

* Just because you aren't fimilar with the way something works doesn't
mean you aren't qualified to review a piece of code.
* Reviewing something new is a easy way to learn about that code

# Review in a timely manner

* It takes team-wide discipline to review in a timely manner
* Leting a PR get stale makes it harder to release

# Encourage discussion during review

* Asking why a particular code choice was made is often better than
dictating a change

# Devalue code on your team, people are worth way more

* Freshly-written code can be thrown out; it happens, it should happen.

# Favor Clarity over Cleverness
* Stop early if you don’t understand something. If you can’t understand it as reviewer, the next casual visitor to the code definitely won’t understand it.

# Don’t require perfection.
* Law of deminishing returns
* Code wants to be shipped
* Don't be afraid to bring in another opinion


