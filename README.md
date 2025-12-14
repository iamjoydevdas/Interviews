# Interviews

## Tell Me About Yourself
Yeah, so I’m a Senior Software Engineer with about 15 years of experience, mostly working on large backend systems.

At the moment, I’m at Sainsbury’s. I work on Java and Spring Boot microservices that run on AWS and Kubernetes, supporting customer-facing retail platforms. A big part of my job is making sure things run properly in production — reliability, monitoring, performance, and handling incidents when they happen.

Before that, I was at Cognizant, working on distributed systems for large enterprise clients like BNY Mellon, Mastercard, and Visa. I also spent time mentoring engineers across different teams.

In my day-to-day work, I usually own services end to end — from designing and building them to deploying, monitoring, and fixing issues, including doing root cause analysis. I work closely with product managers and other stakeholders and take responsibility for what I deliver.

I’m mainly backend-focused, but I’m comfortable working full-stack when needed and working closely with frontend teams to deliver complete customer experiences.

Overall, I enjoy building systems that teams can trust and that customers don’t really have to think about, where strong basics keep systems reliable as they grow.

## Can you tell me more about the systems you work on at Sainsbury’s?
Sure. The systems I work on are mainly backend services that support customer-facing retail platforms. They’re built as Java and Spring Boot microservices and run on AWS and Kubernetes.

Most of these services expose APIs and also communicate asynchronously with other systems, so reliability and consistency are really important. They handle everyday retail use cases, which means they need to perform well during peak traffic and behave predictably in production.

From my side, I’m involved in designing and building the services, deploying them, and making sure they’re observable once they’re live. That includes monitoring, alerting, handling incidents, and doing root cause analysis when something goes wrong.

Overall, the focus is on keeping the systems stable and scalable, because even small issues can affect a large number of users.

What is your role in the team?”

## What is your role in team?
My role in the team is mainly as a backend engineer with strong ownership of services. I design and build Java and Spring Boot microservices, and I’m responsible for taking them all the way to production.

I work closely with product managers and other engineers to understand requirements, make design decisions, and deliver features in a reliable way. Once services are live, I also take responsibility for monitoring, handling incidents, and doing root cause analysis when issues come up.

I also mentor junior engineers, help with code reviews, and support the team in maintaining good engineering standards. While I’m primarily backend-focused, I collaborate closely with frontend teams and can work full-stack when needed to deliver complete features.

## What does owning a service end to end mean in practice for you?”

For me, owning a service end to end means being responsible for it throughout its whole lifecycle, not just writing the code.

It starts with understanding the requirement and working with product to design a solution that fits the use case. I’m involved in the design and implementation, making sure the service is reliable, well-tested, and easy to operate.

I also take responsibility for getting it into production — through CI/CD, deployments, and making sure the right monitoring and alerts are in place. Once it’s live, I stay accountable for how it behaves in production, including handling incidents, investigating issues, and doing root cause analysis.

If something goes wrong, I don’t just fix the immediate problem — I make sure we put the right improvements in place so it doesn’t happen again. Overall, it means being accountable for both delivery and long-term reliability of the service.”

## Can you describe a production issue you’ve handled?”

Yes. One example was an issue where one of our backend services started slowing down during peak traffic, which affected response times for customers.

We first looked at monitoring and logs to understand what was happening and saw that memory usage was steadily increasing and the service was restarting more often than expected.

I worked with another engineer to trace the problem and found that a retry mechanism was creating too many in-memory objects under load, which led to memory pressure.

We fixed the issue by changing the retry logic and improving resource handling. After that, we added better monitoring and alerts so we could spot the problem earlier if it happened again.

Once the fix was deployed, the service stabilised, response times improved, and we didn’t see the issue recur.”

## How do you work with product managers and stakeholders?”

I try to work very closely with product managers from the start, so we’re aligned on what problem we’re solving and why it matters. I focus on understanding the business goal first, before jumping into technical solutions.

Once we’re clear on the goal, I help translate requirements into something technically realistic. That usually means discussing trade-offs like scope, timelines, and risks, and making sure everyone understands the impact of different options.

During delivery, I keep communication simple and regular. I share progress, flag risks early, and avoid surprises later in the process. If something needs to change, I explain the reason clearly and suggest alternatives rather than just saying no.

After release, I stay involved by monitoring how the system behaves in production and sharing learnings with product and stakeholders. That feedback helps us improve future decisions. Overall, I see it as a partnership, where good communication and trust are just as important as the technical work.

## You mentioned full-stack. What does that look like for you?”

For me, full-stack doesn’t mean I’m doing frontend all the time. My primary focus is backend engineering, but I’m comfortable working across the stack when it’s needed to deliver a feature end to end.

On the frontend side, that usually means understanding how APIs are consumed, helping design contracts, reviewing frontend code, and sometimes making changes myself for smaller features or fixes. I work closely with frontend engineers to make sure integrations are clean and efficient.

Most of the time, I see full-stack as being able to think beyond my own service. I understand how backend decisions affect the frontend and the overall user experience, and I’m happy to step in where it helps the team move faster.

So while I’m backend-focused, I’m not siloed. I’m comfortable owning a feature from backend through to the user-facing side when needed.”

## What do you mean by ‘strong basics’?”

By strong basics, I mean doing the fundamental things well so systems stay reliable as they grow.

That includes clear and maintainable code, sensible design decisions, proper error handling, good testing, and making sure services are observable in production.

When those basics are in place, systems are easier to scale, easier to operate, and less likely to fail in unexpected ways. In my experience, most production issues happen when these fundamentals are overlooked.”

## Do you have experience owning production systems?
Yes. I own services end-to-end — from development and deployment to monitoring, 
incident investigation, and root-cause analysis.
I regularly use New Relic, Grafana, and Kibana to track system health

## Have you worked in payments before?
Not directly in payments, but the systems I work on have very similar challenges 
— high throughput, reliability, event-driven architecture, and strict production SLAs. 

Those patterns transfer very well to payments systems.

## What are you looking for in your next role?
I’m looking for a role where I can work on large-scale, business-critical systems and continue growing in event-driven and distributed architectures.

In my current role I enjoy owning services end-to-end — 
from design and development through to production support — 
and I want to keep that level of ownership while working at even higher scale.

The Payments domain is particularly interesting to me because reliability, 
correctness, and resilience really matter, and the challenges align well with the kind of 
systems I enjoy building.

I’m also looking for a team with strong engineering practices and a culture of learning, 
where I can both contribute my experience and continue to grow technically.

## Why are you leaving xxxxxx’s?
I’ve had a positive experience at Sainsbury’s and learned a lot there.

Over time, I’ve realised that I’m looking for a role where I can work on larger-scale,
 more complex systems and continue growing technically.

I’m now at a point in my career where I want to challenge myself further and 
broaden my experience, rather than move because of any negative reasons.

## Have you used Akka or Cassandra?” (with Kafka, SQS, DynamoDB experience)

I haven’t used Akka or Cassandra directly, but I’ve worked extensively with Kafka, SQS, and DynamoDB, building distributed, event-driven systems in production.

With Kafka and SQS, I’ve designed asynchronous workflows, handled retries, idempotency, and failure scenarios, and made sure systems stay reliable under load.

With DynamoDB, I’ve worked with high-throughput data access patterns, eventual consistency, and designing services that behave predictably in a distributed environment.

Because of that experience, I’m very comfortable with the underlying principles behind tools like Akka and Cassandra, and I’m confident picking them up quickly when needed.

