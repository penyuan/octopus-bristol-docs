# Notes on interviews

## notes on interviews so far 2022-12-15

Some takeaways from the five real interviews so far plus three practice interviews: 

* There is a noticeable difference between the two industry researchers and the two academics: 
  * The academics talk far more about underlying values towards open research, at least as in ideal even if not achievable, such as being contractually barred by industry partners to not share key information
  * For me, the two industry interviews stand out in terms of
    * Very traditional paper focused, generally fine with it, and don't see a strong need for change. This is partly because paper authorship is not primary motivator, i.e. the companies like papers because they could demonstrate impact to shareholders/investors; attract/retain scientists; etc., but these researchers don't fundamentally rely on lots of first authors papers like academics.
    * They do observe that as statisticians/data scientists, they are sometimes viewed as fungible "plumbers" (in a negative sense), though interestingly one also viewed some other data roles as plumbing. Also an anecdote where even though they made a important quantitative analytical contribution, they only ended up in the acknowledgements. It was only not devastating because authorship isn't as important in their industry sector.
    * Unsurprisingly less inclined to share intermediate products, but very happy to make use of what others shared, like datasets.
    * If they do share, it's also for very practical reasons such as code being easier to find via a web search compared to digging through files on their computers.
* One person works at a public policy NGO
  * Focused on papers and reports
  * Main motivation is whatever demonstrates impact of their work to management and funders, and impact is defined by context
  * Teams more ad-hoc, formed for specific project at hand, and less clear division of labour
* Both the academics and NGO researcher are more willing to share, but afraid of sharing something immature or low-quality
* All interviewees are generally constrained by time when it comes to sharing anything
* Practically all cases do refer - to varying degrees - an underlying problem with uneven credit and value.
  * E.g. a physicist who is now working on magnetic resonance imaging (and similar techniques), would get called up in the middle of the night by doctors who really value their opinions on a certain method or tool, and have published heavily-scrutinised and high-impact but relatively niche papers, often end up as the middle author in more "mainstream" journals and their h-index is lower as a result. This is hard for an associate professor.
  * E.g. the case where someone ended up only in the acknowledgements.
* Division of labour is hard to discern, and descriptions are fairly high level
  * Interviewees so far work on projects where there simply isn't that much division, other than in big pharma where they are statisitcal/data science specialists, but even then there isn't detailed descriptions outside of that
  * Or, sometimes hints about division of labour come up when being asked about other things like credit, critique, or assessment
* Overwhelming consensus and consistency on the value of early feedback, especially expert critique on methodology
  * But of course the people who are interviewed might be biased towards this, need to acknowledge self-selection in report
* Everyone's "happy" with open research and want to do good science (i.e. consensus on early feedback), but no one's willing to be first mover, especially when there are other competing demands directly affecting career "success"
  * Reluctance to share/credit/critique is usually out of fear: 
    * Showing something raw or immature
    * Being scooped
    * Unequal power

Minor tweaks to interview on 2022-11-08: 

* See regular meeting notes for 2022-11-08
* Implemented
  * Part 1 - prompt research project components could be hypothesis, method, data, etc.
  * Part 2 - people still heavily focused on papers, need prompting to think beyond that
* The part 3 question on "acceptable or not acceptable to critique" is still a bit awkward.
  * This touches on Alex's points about culture i.e. "how much of this is thinking that OTHER PEOPLE might not be comfortable aand how much is a true personal feeling" -> I think it's the fear of sharing something incomplete/immature and how that's perceived; plus being scooped.

## Transcriptions

When cleaning up the transcripts, I plan to clean up words like "um", "ah", etc.

### Auto transcriptions

Zoom's auto-transcription produces closed caption `.vtt` files with timestamps in the form of: 

```
4
00:01:00.140 --> 00:01:02.430
```

To find (and replace) these lines, I used the following regular expression (generated from [RegExr](https://regexr.com)):

```
\n\d+\n\d{2}:\d{2}:\d{2}.\d{3} --> \d{2}:\d{2}:\d{2}.\d{3}
```