![Logging is hot again!](https://github.com/Munich-NET-Meetup/2019-10-02-Logging-Is-Hot-Again/blob/master/feature_image.png)

If you think logging is boring, stop yawning and think again!
---------------------------------------------------------------

Designed for the ages of monolithic synchronous applications running in data centers or on the desktop, traditional text-file-oriented logging frameworks such as log4net or nlog are becoming obsolete. New tools, best-practices and standards are emerging to make sense out of massively distributed and asynchronous applications that run in the cloud, in containers, or in mobile devices. Solutions for a world where storage and computing power are cheap and can be provisioned within minutes.
Starting with the question “what do we want to log and why?”, this talk gives a bird’s eye overview of the new logging landscape. It introduces open-source solutions like Elasticsearch, Fluentd or OpenTracing, and commercial services like Application Insights. On a code level, it shows how PostSharp can help to generate highly detailed logs with minimal efforts.
The key takeaway of this talk is a broad understanding of the business of logging and application instrumentation, so you’re ready to make choices on your own.

ABOUT THE SPEAKER
---------------------------------------------------------------
Gael Fraiteur has been passionately programming since childhood; building and selling his first commercial software at age 12. He is Founder and Principal Engineer at PostSharp Technologies based in Prague, Czech Republic. Gael is a widely recognized expert in aspect-oriented programming and pattern-aware compilers. He speaks at developer conferences in Europe and the United States.

OUTLINE
---------------------------------------------------------------
1. Logging in the cloud
- Logging is changing
- Expectations of operations vs application development
- Logging in the cloud: the log processing pipeline
- The Elastic Stack: example with Serilog
- A list of open-source and commercial solutions
- Buyer’s wish list: how to evaluate a solution
2. Automatic code instrumentation
3. Correlating distributed logs
- The OpenTracing specification
- System.Diagnostics.DiagnosticsSource
- DIY log correlation with Serilog: example with ElasticSearch
- Hierarchical ids
4. Statistical processing: semantic vs structured logging
5. Sampled logging

AGENDA
---------------------------------------------------------------
- 18:00 - Doors Open
- 18:30 - Gael Fraiteur, Logging is hot again!
- 20:00 - Questions
- 20:30 - End of event.
