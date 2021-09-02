# Survey questions

## About you

See [who](./design/who.md).

The following are primarily for cohort analysis, secondarily for understanding the shape of the community.

Are you a Rust user

- I have used for Rust for any reason in the past three months
- I have used Rust in the past, but not in the past three months
- I have never used Rust

TODO is three months the right amount of time
TODO move to section about Rust?

Do you identify with an underrepresented group in the technology industry?

- yes
- no
- I prefer not to say (could just be an optional question)

TODO should we ask which group? 

Are you a full- or part-time student?

- yes
- no

Are you employed in full- or part-time work (including paid internships)?

- yes, in tech
- yes, in finance
- yes, in government
- yes, in education
- yes, other
- no

If you are work, which category best describes the domain in which *you* work?

- server networking, desktop application, mobile application, web application, embedded, etc.

TODO categories

Do you write or design software in your work?

- yes, primarily as an IC
- I primarily manage others who do
- no

If you write or design software, or manage others who do so, how long have you done so professionally?

- <= 5 years
- <= 10 years
- <= 15 years
- <= 20 years
- > 20 years

Excluding Rust, which programming languages are you experienced with (TODO define level of experience)

- Assembly language of any variety
- C or C++
- Java, Go, Objective C, C#, or similar object-oriented language
- Haskell, Lisp, ML, or other functional language
- Scala, Swift, Kotlin, or other modern, strongly-typed language
- Javascript, Ruby, Python, or other dynamically-typed language

TODO are these the right categories?

How long have you been programming (in any language, for fun, learning, work, any reason)?

- < 1 year
- < 3 years
- < 5 years
- < 10 year
- > 10 years


Which operating systems do you use regularly for software development (not just Rust)?

- *nix
- Windows
- Mac OS
- other

Which operating systems do you develop software for?

- *nix (desktop or server)
- Windows
- Mac OS
- embedded platforms
- other

TODO should we ask if people develop for cross-platform vs a specific platform?


Where do you live?

- North America
- Central America
- South America
- Europe
- Middle East
- Africa
- West, central, or south Asia
- east or south-east Asia
- Australasia or the pacific

TODO are these the categories we care about? Do we want to separate China from east asia given the distinct communities?

Level of English (select all which apply)

- Can have a technical conversation
- Can understand most technical documentation
- Can understand a technical talk (e.g., at a conference or meetup)
- Some everyday English

What is your preferred language for technical communication

- English
- Chinese
- Hindi
- Spanish
- Russian
- Japanese
- Other

TODO other questions to understand the community
  - ask community and core team, foundation
TODO other questions for cohort analysis?

## Your Rust experience

Which operating systems do you use regularly for Rust development?

- *nix
- Windows
- Mac OS
- other

Which operating systems do you develop Rust software for?

- *nix (desktop or server)
- Windows
- Mac OS
- embedded platforms
- other

TODO should we ask if people develop for cross-platform vs a specific platform?

Which tools do you use (at least once per month), either directly or in CI when doing Rust development

- an IDE or editor with plugin doing more than syntax highlighting
- debugger
- println debugging
- profiler
- clippy
- rustfmt
- Cargo
- Rustup (TODO regualar updates vs advanced use like switching channels?)
- code coverage
- rustdoc


TODO lots more in this section:

* Stability of the language
  * Do people feel that their code is being broken?
  * How often and what is the severity of this breakage?
  * In general, do people feel like Rust's stability guarantees are upheld?
  * How often do people *need* to reach for nightly for the compiler or core tooling?
* The Rust compiler as a productive tool
  * Is the perception of {compile times, binary size, artifact disk space (i.e., the target folder)} getting better or worse over time?
* What are "core tools" for users (i.e., they are an indispensable part of the Rust programming experience?)
* How is the IDE experience with Rust?
* How reliable is tooling and how happy are people in general with the user experience?
* Do people find the edition experience relatively uneventful?
* Does Rust work well for the platform they are targeting (i.e., the compile target)?
* Can people usually find the library their looking for? If not, what domains seemed to be the most underserved?
* Questions which gauge attitudes to potential new features.


Which of the following apply to you (TODO possibly multiple questions for past month, past year, ever, + would you like to do ):

- I have contributed (in any way) to a crate published on crates.io TODO separate issues from PRs/other productive stuff?
- I am maintainer of a Rust project outside of the core project
- I have contributed (in any way) to a core Rust project (part of the rust-lang GH org)
- I'm a member of a Rust team or WG
- I've read the Rust blog
- I've read TWiR
- I've read GH rust-lang org/Zulip/Discord/internals/users/r/rust (separate answers or one answer?)
- I've written a comment/post on GH rust-lang org/Zulip/Discord/internals/users/r/rust (separate answers or one answer?)
- Attended a meetup (including virtual)
- participated in a private Rust community (e.g., work Slack, private messages)

Have you tried but failed to complete any of the following?

- GH issue (Rust)
- GH PR (Rust)
- discuss an RFC
- write an RFC
- discuss Rust on GH rust-lang org/Zulip/internals/Discord
- publish a crate

How welcome do you feel when interacting with the Rust community in the following ways? (1/2/3/NA?) TODO in the last year

- other social media (twitter, facebook, other sites 'outside' core Rust, e.g., r/programming, HN - TODO one or two answers)
- rust-lang GH
- other GH Rust project
- Zulip/internals/Discord
- users/stack overflow
- r/rust
- Rust conferences
- Local Rust events, e.g., meetups

TODO anything more objective like asking about particular incidents or kinds of incidents?
TODO ask about blockers for participation?

## Rust at work

> This section is largely in service of the [contexts](./design/contexts.md) design document.

### Are you using Rust at work

Select one:
- Yes, for the majority of my coding
- Yes, it's one of a number of languages I use and I use it regularly
- Yes, but I only use it occasionally
- No, but it is likely in the next year
- No, I use other programming languages at work
- Not applicable (i.e., I don't write software professionally, I am student, etc.)

> **justification**
>
> We want to establish what percentage of those who could possibly use Rust in a professional setting
> are using Rust in a professional setting. This is most interesting over time. 
> Answers to this question should be combined with whether the respondent has ever used Rust.

**TODO**: explain why the following questions are not asked
Is Rust used in the company where you work?

### To why extent is Rust currently being used by your company?

Select one:
- My company uses Rust for a large portion of production projects.
- My company uses Rust for a small portion of production projects.
- My company uses Rust only for non-production projects (e.g., tooling).
- My company has actively experimented with Rust for use in production projects.
- My company has actively experimented with Rust for use in non-production projects.
- My company has seriously discussed but not experimented with using Rust.
- My company has not seriously considered Rust for any use.
- I am unsure whether my company has considered using or currently uses Rust.
- I don't work for a company or my company does not develop software of any kind.

> **justification**
>
> We want to establish how reliant companies are on Rust.

### In what technology domains is Rust used at your company?

Select as many as apply:
- backend application 
- desktop application 
- mobile application 
- web application 
- embedded application
- other

> **justification**
>
> We want to known roughly what technology stacks are being most often used.
> 
> **challenges**
>
> This can be ambiguous and hard to answer. For example, if you're building an operating 
> system for a mobile phone, is that embedded, mobile, or something else.
> We want to understand the "shape" of Rust usage, and this question only gets at that 
> in one particular way.

### Do you or your company use Rust at work?

Select one:
- Yes, I work with Rust full time
- Yes, I work with Rust part time
- No, but my company uses Rust 
- No
- Not sure 
- Not applicable 

> **REMOVED**
>
> This question was removed from the survey, because it was not sufficient in gathering the information we wanted.

### For programmers - what languages, other than Rust, do you use at work?

Free form:

> **REMOVED**
>
> While this might be an interesting question, there's not too much that is directly actionable from it.

### Does your company plan to use Rust or evaluate Rust in the future?

Select one:
- Yes 
- No
- I don't know

> **REMOVED**
>
> This data is better captured in other questions.

### How could we make Rust more appealing to your company?

Free form:

> **REMOVED**
>
> This question is too vague and unlikely to yield any interesting answers.

### How may developers at your company use Rust at work?

- 1
- 2-5
- 6-10
- 11-25
- 25-100
- More than 100
- I don't know

> **REMOVED**
>
> This question fails to consider companies with different sizes. One company with 100,000 developers
> where more than 100 use Rust is different than a company with 110 developers. We can gauge the importance
> of Rust to companies through more direct questions

### Approximately how many total developers does your company employ?

- under 10
- 11-49
- 50-99
- 100-500
- 100-500
- 500-1,000
- 1,000-10,000
- 10,000-100,000
- Over 100,000

> This question is not that interesting on its own, but it can be used as a sort of co-hort for understanding how answers 
> change depending on the size of the development effort at a company.
>
> Previously this question used "employees" instead of "developers". It is more appropriate for us to ask about the amount
> of developers at a company vs. the amount of people employed in total.

### If you summed up the size of all Rust projects at work, how big would it be?

Select one:
- Less than 1,000 lines
- 1,000 to 10,000 lines
- 10,000 to 100,000 lines
- More than 100,000 lines
- I don't know

> **REMOVED**
>
> While this might be interesting, there's nothing generally actionable from this. We are curious if Rust is playing a bigger
> role in professional settings over time, and this is better served by other questions.

### Is your company planning on hiring Rust developers in the next year?

Select one:
- Yes
- No
- I don't know

> **REMOVED**
>
> This question was likely meant to gauge if the appetite for Rust developers is growing. However,
> hiring is a lagging indicator, and we can more easily tell if Rust is being used more or if it is 
> getting easier to find Rust jobs from other questions.

### What are some ways you or your company is using Rust at work?

Free form:

> **REMOVED**
>
> This question is extremely vague and has not really been useful in the past.

### How could we make Rust more accepted at your company?

Free form:

> **REMOVED**
>
> This question is vague and has not really been useful in the past.

## Rust in education

> This section is largely in service of the [contexts](./design/contexts.md) design document.

### Are you taking a course or training which uses or teaches Rust, or have you in the past year, or are you enrolled for one in the coming year?

Select one: 
- Yes
- No

### Where is the course or activity taught?

Select one: 
- University or other tertiary institute
- Bootcamp or other vocational-focussed educational institute
- A short training course offered by your employer or a contracted third party

> TODO are the latter two sufficiently differentiated?

### Which best describes your course or activity?

- A programming course which only teaches Rust
- A programming course which teaches Rust amongst other languages
- An computer science course (e.g., operating systems, algorithms, etc.) course which uses Rust with or without other languages
- Other course which uses Rust
- Individual project
- Group project
- Other activity

### Is Rust mandated for your course or activity, or did you choose it yourself?

- Compulsory
- Optional (but suggested in some way)
- Optional (completely driven by you)

