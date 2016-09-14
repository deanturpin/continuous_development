Notes from Jez Humble's 'Continuous Delivery' seminar:
https://www.youtube.com/watch?v=ZLBhVEo1OG4

Continuous delivery not continuous deployment

Deployment is OK for a website - deploy trunk - but not for embedded. Delivery is the ability to
create a release at any point.

## Adopting
Organisational, architectural, process

**NOT**

Tools, code, infrastructure

## Takeaways
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

## Why bother?
Increase quality, reduce cost, improve throughput.

Feedback loops: automated feedback for any change.

## Testing environments
Don't have test environments that are works of art: bear no resemblance to
production.

If the build is broken for more than ten minutes at a time you're not doing
continuous integration.

If I don't revert a bad change you're selfishly stopping everybody else from
working effectively.