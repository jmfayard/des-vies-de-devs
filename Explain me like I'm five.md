![](https://dev-to-uploads.s3.amazonaws.com/i/iyoi197lziyzf2qprkui.jpg)

> If you can't explain it simply, you don't understand it well enough. 
>
> -- Albert Einstein

[#explainlikeimfive](https://dev.to/t/explainlikeimfive) is the best tag on DEV.to and you should definitely follow it

I have stolen for you some incredibly pedagogical answers on this website. Specifically I selected answers that were enlightening yet concise, and that explained with words only - no code. 

Many thanks to many authors: <a class="comment-mentioned-user" href="https://dev.to/evanplaice">@evanplaice</a>
 <a class="comment-mentioned-user" href="https://dev.to/wulymammoth">@wulymammoth</a>
 <a class="comment-mentioned-user" href="https://dev.to/bizzy237">@bizzy237</a>
 <a class="comment-mentioned-user" href="https://dev.to/buzzingbuzzer">@buzzingbuzzer</a>
 <a class="comment-mentioned-user" href="https://dev.to/xtrp">@xtrp</a>
 <a class="comment-mentioned-user" href="https://dev.to/evanoman">@evanoman</a>
 <a class="comment-mentioned-user" href="https://dev.to/sergiodxa">@sergiodxa</a>
 <a class="comment-mentioned-user" href="https://dev.to/javascripterika">@javascripterika</a>
 <a class="comment-mentioned-user" href="https://dev.to/georgeoffley">@georgeoffley</a>
 <a class="comment-mentioned-user" href="https://dev.to/ben">@ben</a>
 <a class="comment-mentioned-user" href="https://dev.to/johnmunsch">@johnmunsch</a>
 <a class="comment-mentioned-user" href="https://dev.to/triplejdev">@triplejdev</a>
 <a class="comment-mentioned-user" href="https://dev.to/aminnairi">@aminnairi</a>
 <a class="comment-mentioned-user" href="https://dev.to/derek">@derek</a>
 <a class="comment-mentioned-user" href="https://dev.to/matthewbdaly">@matthewbdaly</a>
 <a class="comment-mentioned-user" href="https://dev.to/rkichenama">@rkichenama</a>
 <a class="comment-mentioned-user" href="https://dev.to/miguelmota">@miguelmota</a>
 <a class="comment-mentioned-user" href="https://dev.to/dansherpa">@dansherpa</a>
 <a class="comment-mentioned-user" href="https://dev.to/sebbdk">@sebbdk</a>

And then I added some explanations of my own.

## Developer roles

Think of a restaurant. You have greeters (CDNs) and hostesses (reverse proxies) to direct customers (users) to their seats.

When they get there there are servers (FrontEnd Devs) who provide the customers a pleasurable experience (UX) as well as eserve them food (data).

In the back you have cooks (BackEnd Devs) doing prep work, dishwashers (SREs) making sure everything is clean and ready, as well as Kitchen Managers (DevOps) to ensure everything in the back is setup to run smoothly.

SPAs operate like a buffet in that they leave more work for the customers to do themselves and put more emphasis on the FrontEnd.

Where do FullStack devs fit in. They're the restaurant managers. They can fit into -- and accel at -- any role b/c they have likely worked in every role at one point or another.

It takes a lot of work to get good enough to be a FullStack dev. So much so that some other types of devs deny that they even exist.

The truth is, the hardest part about becoming a legit FullStack dev is pushing back against your employer so they don't keep you pigeonholed into a very narrow role.

Many devs are perfectly happy to get paid a lot to work a narrowly defined role. Pursuing FullStack is the hard path and the sacrifice in time/effort to get there may not be worth it.

Like every restaurant wants a badass restaurant manager like Gordon Ramsey, companies would really love to have badass FullStack devs on their team.

But! Very few companies will invest the time and resources to raise a dev to that level.

FullStack devs have a lot more freedom to migrate elsewhere if the work conditions are bad and they're very difficult and costly to replace.

FullStack devs have the capability to raise everybody up. But companies don't want to raise devs up to FullStack status.



## Programming

### What is programming?


Imagine that you have three person who need to design and build a peanut butter and jelly sandwich.

Alice takes care of providing the requirements: bread, peanut butter, jelly, knife, plate, etc

Bob takes care of the program, meaning the steps necessary to build the sandwich.

Charlie must follow blindly the steps of the program, meaning what is written in it instead of what its author meant.

Let say that the first step in the program was to spread the peanut butter on the bread. We immediately found the first bug. The bread was still in a bag - it had to be opened and taken out and put in the plate. The peanut butter had was unopened, etc. Go back and iterate on the program until they get it right.

Doing that will give you a great feel for how detailed a program needs to be, and that the computer only follows the instructions you give it.


### What is a programming language?

The best analogy to a programming language is, well, a natural language.

Except you might say that we are talking to computers, not people, and culture in this case could be compilers, libraries, patterns, frameworks, operating systems, databases, network, etc.

That's true but in fact as you becomes more experienced you realize that every programmer can write code that a compiler understandfds... but the good programmers focus on writing in a way that humans can understand. Because programming is a team sport.

So in fact we are doing more than you think the same job as an ambassador, translating things, trying to understand the others, asking for things, seeing what works and what doesn't, solving culture specific disputes etc.


### Git vs GitHub 

Git is like saving multiple drafts of written papers called report-v1.docx, report-v2.docx, ... but in a more structured way. Essentially it gets you an history of previous versions you can revert to like in Wikipedia. The most important difference is that developers modifies multiple files at once (a commit) while for writers work on one docuùment at a time.

Github is a social media hub for those multiple drafts of papers that other people can view, work on, and collaborate on!

### Recursion

Do you know Matryoshka dolls?

![](https://share.cleanshot.com/5hlbps+)

When you open a doll, you find another doll inside, and when you open that one, there's another one inside. The act of doing this is called recursion. Let's write code for that.

```javascript
function openDoll(doll) { 
    if(doll.isEmpty()) { 
        return doll; 
    } 
    openDoll(doll.open()); 
}
```

Recursion is a way of doing an operation over a set of values, where each value is related to the previous one, without iterating or using loops.

### Dependency Injection

When you go and get things out of the refrigerator for yourself, you can cause problems. You might leave the door open, you might get something Mommy or Daddy doesn't want you to have. You might even be looking for something we don't even have or which has expired.
What you should be doing is stating a need, "I need something to drink with lunch," and then we will make sure you have something when you sit down to eat.

[John Munsch](https://stackoverflow.com/questions/1638919/how-to-explain-dependency-injection-to-a-5-year-old/1638961#1638961)


### Promises 

You ask your mum if you can have some sweets later. She can either resolve sweets ( yes you can have some), or reject your request (no sweets for you. You’ve been naughty).
When it gets to later, if her promise resolved (ie she said you can have some) THEN you can eat them. Otherwise, you have to CATCH the tears you cry because you can’t eat sweets. Simple, huh?

A promise contains a resolve and reject. When it is actually called (the function is invoked), if it resolves, use THEN, or CATCH the rejection. 

### Async Await

I am your faithful dog JavaScript. I love you with all my heart, but normally when you go off to school. I go do other stuff. I find React the cat and bark at him. That's fun because he's getting really old. I nap. I eat. I drive the dreaded "mail man" away from our house. Then, when you get home again, we play! Hooray!

But today, you said, "Await me and I will give you this bone." So I have not moved. I am a good dog. I am a very good dog. I will stay here and not do anything else until you get back and then I will get the bone and we will play!

That, is Async/Await 

## Concepts

### Technical Debt

A software project without product features is useless.
A software project without time dedicated to the engineering of itself slowly then swiftly turns into agony.
Both Product and Engineering are essential for a software to suceeds.

At times, you can have good reasons to focus on Product. What happens then Product borrows some debt from Engineering. Later though you will need to repay that debt - in fact: Time - to Engineering.

If you don't, be prepared to have the whole projects go slowly then swiftly into a painful agony where every additional feature needs more time to be completer than the previous ones.

### Refactoring

Refactoring is what programmers do to pay off the technical debt.

It is very similar to writers who after having written their shitty first draft (Anne Lamott) rewrite it to make it better.

## Methodologies

### Lean Startup

You have a great idea. That will be huge. Building it is a challenge but you are smart and hard working. You start building it. In fact things always end up taking more time than planned so you spend six months in your cave. But finally the day arrive, your Thing is ready. You put it out there on the web, hopeful that your users will come.

Except that almost nobody comes.
The frustration is immmense.
You have built evertything right and your git commit messages are perfect.

After the four stages of grieves, you ask yourself whether you could have talked with your ideal customers early on to find out whether they actually needed your product.

That's when you stumble upon the Lean Startup methodology.

### Agile vs Waterfall

Waterfall: you're hired to build a house. the client tells you how many rooms he needs, how many windows, etc. then you build a house. then client tells you that he needs to use a living room as a plane hangar and the bedroom should be painted in purple

Agile / Scrum: you're hired to build a house. client comes by every week to tell you what he likes and doesn't like so you can make changes before it's too late. sometimes the client comes in the middle of the week and tells you that he's showing the house to his friends tomorrow and it would be nice if there was a fireplace in the living room. and most of the time the client isn't interested in technical details so spending a week making pillars to support the second floor is not a good idea because you'll have nothing to show


## Frameworks



### React

A React component is essentially just a function that returns HTML. It can accept arguments if necessary, in the form of props, and can use those to determine what it renders.

While a component can technically be a class, it still makes more sense to think of it as a function, and with the advent of Hooks it's probably not necessary to build any one component as a class nowadays.

### Angular

Angular is less popular than man React among developers. Many find it boring. Many companies find it good that Angular is boring. Indeed two Angular projects tends to relatively similar, making the onboarding of a developer in a new project more straightforward. By contrast, React projects tend to be their own unique snowflake.

### Vue

Vue is like a cameleon. Whatever the environment, it adapts. Forest, mountain, plain desert, etc... It evolves and scales accordingly. You can use a simple script to include it in a static website and create a Vue component for only the login button for instance (send a login/password to the server, receive a token, store it in localstorage). Or create a full Vue application involving a router (VueRouter), a more complex data exchange system (VueX), with reusable components just like React. You can do 15%, 50% a whole application in Vue due to its incredibly simple integration. It uses concepts that are known to Web developers, no new syntax for writing Virtual DOM: it is just HTML that is cleverly converted to JavaScript. It just feels like writing yet another HTML page, with some JavaScript and CSS. But it was a Vue component! Haha you just got pranked...

### CSS

CSS is the thing that maked webpages look good, except when backend developers like me try to write it because for the life of me we don't understand CSS.

## DevOps

### What is DevOps?



It is winter, and one cold evening, a fairy visits you.

"You've got three wishes", the fairy says.

"I want a machine that throws snowballs", you say.
And puff, there's the machine. And the fairy disappears.

You invite your friend Simone over, and tell her what happened.
"Wow", says Simone. "How do you use the machine?"
"I have no idea. It's got like 1000 buttons.
It is way to complicated."
"Oh my god", says Simone. "What a pity."

That night, you sit in your room crying.
Suddenly, the fairy appears again.
"What's up? Why are you crying?"
"Well, you gave me that awesome machine, but I can't use it.
Simone can't use it either. It's too complicated."
"Well, you didn't say it needs to be simple. But remember.
You've got 2 wishes left."
"Ok. My friend Simone and me, we want to know which buttons to press. So that the machine builds snowballs, and throws them."
"Your wish is my command", says the fairy, and disappears.

You invite Simone over. But now, there is another problem:
you know exactly which buttons to press to make the machine build a snowball. But only that. You're kind of like the developer of snowballs.

Your friend Simone knows which buttons to press to make the machine throw a snowball. But only that. She's kind of like the operator of the machine.

If Simone and you work together, you can make the machine build and throw a snowball. But neither of you knows the whole story. Neither of you can use the machine alone. You always need Simone around. And while you can build snowballs that look really good, Simone often complains that they are too heavy and don't fly far enough.

But you're friends. You observe each other, and talk about the machine a lot. Because it's the most fascinating thing you know. And over time, you learn which buttons to press to operate the machine. And Simone learns to build a snowball with the machine.

You were a developer, and learned to operate the machine.
Simone was an operator, and learned to develop snowballs.
So now both of you are a developer, and an operator. You are DevOps.

One winter evening, you visit Simone.
Suddenly, the fairy appears again.
"You've got one whish left", the fairy says.
"It's your turn", you say to Simone.
Simone sits on her chair silently for a minute.
Suddenly, she jumps up.

And with a smile on her face, she says:
"I want a button on the machine that builds and throws a snowball.
And both my friend here and I can use it.
Don't trick us again. We are DevOps after all."


### Containers, Virtual Machines, Docker, Kubernetes

A Container is a box with all the pieces required to use a single toy. You can have multiple containers to combine your toys and create more better toys. Some boxes only have the pieces and you need to have multiple boxes to create a single toy.

A virtual machine is like having a box with the pieces to use a toy, but you all need eat your vegetables first each time you want to use the toy.

Docker is the name of a possible boxes where your toy can come. Is the most used and looks like a whale.

Kubernetes is like the maestro that make sure the whole orchestra of docker containers play together in an harmonious way.


## Networking

### DNS

If you're familiar with a modern smart phone with a "contact list" or "phone book", ask yourself when the last time you've had to recall the actual digits of the phone number are for a friend/family member. Hardly? If ever?

The Internet is made up of IP (Internet Protocol) addresses, the phone numbers of the internet -- an address is simply the location representing an entity and/or resource. It's hard to remember compared to your friend's name or the URL of a site, like Dev.to whose IP from where I am, resolves to 151.101.130.217. That would be difficult to remember each time I wanted to visit this site.

A DNS aka domain name service, provides translation of the URL (top-level domain) to an IP address in a decentralized, semi-federated, fashion that provides essentially a map to take what we can remember and translate it to something that we don't (the actual IP address)

### TCP vs UDP

You and a friend need to share a toy:

You ask a friend if he can play with the toy.
Your friend asks you if you actually asked him for the toy.
You tell your friend that you asked for that toy.
He gives you the toy.

That's TCP, aka [Transmission Control Protocol - Wikipedia](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)

Your friend throws a toy at you and walks away.

That's UDP aka the [User Datagram Protocol - Wikipedia](https://en.wikipedia.org/wiki/User_Datagram_Protocol)

### REST vs GraphQL

A weather app on your smartphone needs to fetch weather information from the weather specialists somewhere in the internet. Its job is merely to display it in a smart way, for example to warn you when you need to take your umbrella.

Both REST and GraphQL are standard internet protocols that enables the smartphone app and the meteorologists to exchange information. 

REST, much like a language like Javascript, is based on the principle of duck typing 

> If it walks like a duck and it quacks like a duck, then it must be a duck

GraphQL on the other hand is based on static types, much like a programming language such as Java

> Inputs and outpus in GraphQL have a static type with a distinct name that becomes a shared language accross the front end and the backend.
