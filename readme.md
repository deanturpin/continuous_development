Notes from Jez Humble's 'Continuous Delivery' seminar:
https://www.youtube.com/watch?v=ZLBhVEo1OG4

Continuous delivery not continuous deployment

Deployment is OK for a website - deploy trunk - but not for embedded. Delivery is the ability to
create a release at any point.

### Adopting
Organisational, architectural, process

**NOT**

Tools, code, infrastructure

### Takeaways
- Understand why you want to change: what's the business driver? (It's going to
  be painful.)
- Get measurable change fast, even if reaching your goal takes years
- Goal takes years (show measurable business improvement)
- Start with continuous integration (get the engineering house in order before
  you can fix the operations problem)
- Create culture of continuous improvement

The myth of retiring services.

The most inefficient way of testing if something is valuable is to build it.

What's the length of time from golf course to measurable customer outcome?

water-scrum-fall

Continuous delivery is about making delivery boring: reduce the cost, time and
risk of delivering incremental changes to users.

Releasing software should be boring. It should be a push-button process that
no-one cares about that you can do during normal business hours because you've
done all the hard work beforehand.

Change the economics of software delivery.

### Why bother?
Increase quality, reduce cost, improve throughput.

Feedback loops: automated feedback for any change.

### Testing environments
Don't have test environments that are works of art: bear no resemblance to
production.

If the build is broken for more than ten minutes at a time you're not doing
continuous integration.

### Everyone commits to trunk at least once a day
- If I don't revert a bad change you're selfishly stopping everybody else from
working effectively.
- If you don't want the integration phase this is the only thing that scales.

The whole of Google is in one repo and everybody works on trunk.

Anyone in Google can revert anybody else's change if it's broken.

### Demonstrating features
- Is this feature in trunk? No, then come back when it is.
- Are you going to demonstrate the feature by running the automated tests?
  Automated tests not written? Then come back when they are.

### Engineers
Engineers - breaking a problem down into small changes that keep trunk
releasable is a hard mindset change for engineers. Developers just want to sit
in their cube coding for days on a branch with their headphones on. The whole
reason people become engineers is so they don't have to talk to other people.

Optimise for how quickly we can get working features to customers not how
quickly we can have undeployable code "done" on our developer workstations.

W Edwards Demming - statistician, created total quality movement, helped
Japanese car industry

"Cease dependence on mass inspection to achieve quality. Impreove the process and
nuild quality into the product in the first place."

The cheapest way to fix a bug is not to commit it in the first place.

### Products
- Electric Cloud
- Electric Commander
