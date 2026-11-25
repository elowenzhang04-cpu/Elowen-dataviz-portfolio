| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Wireframes and Storyboards

[the current Shorthand draft](https://preview.shorthand.com/BY6nfEg5B00dY1DE)

The story begins with the moment when a passenger may be separated from their wheelchair or scooter before boarding. It then explains what federal reporting considers a mishandled device and moves into the data. The visualizations first establish the persistent difference between mobility-device and checked-baggage mishandling rates. They then show the number of reported events, the timing of the recent decline, and differences among operating carriers. The final sections show that improvement has been real but uneven and that better performance is possible.

## Storyboard Progression

| Story stage | Main content | Purpose |
|---|---|---|
| Human stakes | “A Wheelchair Is Not Luggage” | Introduce why a mishandled mobility device can have consequences beyond those of ordinary baggage |
| Passenger journey | “One Trip, Two Separate Journeys” | Show when the passenger and mobility device may be separated |
| Handling context | Device characteristics and the meaning of mishandling | Connect the passenger experience to the federal reporting data |
| Persistent disparity | Mobility-device and checked-baggage rates | Show that the difference has continued across multiple years |
| Scale | Annual reported events and the total of 62,967 | Translate the percentages into the number of reported mishandlings |
| Policy context | The January 2025 federal wheelchair rule and the monthly trend | Explain what the rule addressed without claiming that it caused the decline |
| Carrier differences | Comparison of rates in 2019 and 2025 | Examine whether improvement was broadly shared |
| Volume and performance | Carrier volume compared with mishandling rate | Test whether higher volume alone explains higher rates |
| Resolution | “Better performance is possible” | Bring the findings together and lead into the call to action |
| Call to action | Booking information and incident reporting | Give passengers and other readers clear next steps |

## Draft Visualizations

| Visualization | Question |
|---|---|
| Annual mobility-device and baggage rates | Has the disparity continued over time? |
| Annual reported mishandling events | How many reported events are behind the percentages? |
| Monthly and trailing 12-month rate | When did the recent decline begin? |
| Carrier rates in 2019 and 2025 | Was the improvement broadly shared? |
| Carrier volume and mishandling rate | Does handling more devices necessarily lead to a higher rate? |

The charts will continue to be refined and to be presented with Tableau.

# User Research

## Target Audience

The primary audience is U.S. air travelers who use wheelchairs or scooters, along with family members, friends, and travel companions who help them research or book flights. These readers have a direct reason to understand how mobility devices are handled, how reported performance differs among carriers, and what they can do if a device is lost, delayed, damaged, or pilfered.

The story may also be useful to disability advocates, airline accessibility teams, regulators, and members of the general traveling public who want to learn more about accessible air travel.

## Interview Script

### Questions

| Goal | Questions to Ask |
|---|---|
| Understand the main message | In your own words, what was the story mainly trying to communicate? |
| Evaluate the opening | Did the “two separate journeys” section help you understand why the handoff matters? |
| Evaluate the visualizations | Which chart was easiest to understand? Which chart required the most effort? |
| Test the rate and count distinction | How would you explain the difference between the annual rate and the annual number of reported events? |
| Test the policy section | What did you think the January 2025 marker meant? Did the story appear to say that the rule caused the decline? |
| Test the carrier comparison | What conclusion did you draw from the comparison between 2019 and 2025? |
| Test the scatterplot | What did the volume and mishandling-rate chart appear to show? |
| Evaluate pacing | Did any part of the story feel too long, repetitive, or too fast? |
| Evaluate the conclusion | What did “Better performance is possible” mean to you? |
| Evaluate the call to action | After reading the story, what action do you think a passenger or policymaker should take? |
| Invite further feedback | If you could change one part of the story, what would you change? |

# Interview Findings

I conducted eight conversations in total. Three of the additional participants had academic backgrounds similar to those of the interaction design, public policy, and medical participants described below. Their feedback was also very similar. To keep the findings readable, the detailed discussion focuses on five participants who represent the broadest range of perspectives. The remaining conversations were used to confirm recurring patterns.

I did not create full transcripts of the interviews. The findings are based on the notes and key phrases I recorded or remembered after each conversation. Most comments are therefore paraphrased. Short quotations are included only when I clearly remembered or recorded the wording.

## Participant 1: Interaction Design Graduate Student

- **Main message:** The participant understood that mobility devices continue to be mishandled more frequently than checked baggage, even though the reported rate has declined. The annual percentage did not seem reassuring once it was translated into thousands of reported events.
- **Opening:** The “two separate journeys” structure made the handoff easy to understand. However, the moment when the passenger and device are separated passed too quickly. The participant wanted this stage to receive more visual space and emotional weight.
- **Strongest visualization:** The annual line chart was immediately understandable because the gap between the two lines remained visible across every year.
- **Most difficult visualization:** The scatterplot required the most effort. The logarithmic scale and scattered labels interrupted the reading flow.
- **Policy marker:** The participant understood that the January 2025 marker provided context rather than proving that the rule caused the decline. The marker was still visually strong enough to appear like a turning point during a quick reading.
- **Pacing:** The middle of the story felt slightly flat because several charts followed one another without a strong visual pause.
- **Call to action:** Checking carrier performance before booking felt useful. Reporting an incident felt less specific because the process and expected result were not yet clear.
- **Main recommendation:** Create more visual rhythm between the middle charts and simplify the scatterplot.

## Participant 2: MSPPM Student

- **Main message:** The participant understood the story as evidence of persistent disparity, real but uneven improvement, and substantial differences among carriers.
- **Opening:** The handoff helped frame the issue as a gap in custody and accountability rather than an ordinary baggage problem.
- **Strongest visualizations:** The annual rate comparison and event counts worked well together. One showed the difference in reported risk, while the other showed the scale of the problem.
- **Carrier comparison:** The participant understood that improvement was broad but not universal. The chart supported the argument that lower rates are achievable rather than structurally impossible.
- **Scatterplot:** The participant valued the analytical finding that volume does not explain everything. However, the chart needed more explanation for a general audience.
- **Policy marker:** The careful causal language was appreciated. The participant recommended making the marker less prominent so that readers would not treat the rule as the main explanation for the decline.
- **Reporting language:** The participant wanted the word “reported” to appear consistently. The dataset measures reported events and cannot show whether reporting behavior changed across carriers or over time.
- **Call to action:** The booking-transparency recommendation was concrete. The passenger reporting recommendation felt weaker because passengers should not be expected to monitor the system alone.
- **Main recommendation:** Strengthen the distinction between reported performance and actual mishandling, while keeping the policy interpretation cautious.

## Participant 3: Medical Student

- **Main message:** The participant understood that a damaged or delayed wheelchair can affect a person’s ability to move independently after arriving at their destination.
- **Opening:** The handoff felt meaningful because it resembled other vulnerable transitions where responsibility moves between people or organizations.
- **Strongest elements:** The line chart and the total of nearly 63,000 reported events were the most memorable parts of the story.
- **Rate and count:** The participant understood the rate as the likelihood of an incident and the count as the number of reported events. The annual total made a seemingly small percentage feel more consequential.
- **Most difficult visualization:** The scatterplot was difficult to interpret without reading the explanation that followed it.
- **Policy marker:** The participant understood that the decline began before the new rule, but wanted a clearer explanation of what the rule changes for passengers.
- **Pacing:** The middle of the story became abstract after several data-heavy sections. The participant wanted the human consequences to return before the conclusion.
- **Call to action:** Reporting an incident seemed reasonable, but the participant questioned how realistic it would feel for someone already dealing with a damaged device and a disrupted trip.
- **Main recommendation:** Add a brief reminder of what mishandling can mean for the passenger’s day, trip, or ability to move independently.

## Participant 4: Frequent Business Traveler

- **Main message:** She understood that mobility devices remain more than twice as likely as checked baggage to be reported mishandled and that some carriers perform differently from others.
- **Opening:** The separation stage felt convincing because she had watched airlines load special items and had seen how chaotic the process could appear. She clearly distinguished the inconvenience of delayed baggage from the loss of a wheelchair.
- **Strongest elements:** The line chart communicated the disparity immediately. The total of more than 60,000 reported events was more persuasive to her than the percentages.
- **Most difficult visualization:** She largely skimmed the scatterplot. The surrounding sentence communicated the conclusion, but the chart itself did not help her reach it.
- **Carrier comparison:** The chart made her want more actionable information. She wanted to know which carrier would operate the flight and where she could check its recent rate.
- **Pacing:** Once she understood the disparity and the recent improvement, she was ready to move toward carrier choice and practical action. The later charts began to feel like additional homework.
- **Call to action:** Comparing carrier rates before booking felt natural because she already considers on-time performance, fees, and other service information. She was more skeptical about reporting because her previous airline complaints had not always produced a visible result.
- **Main recommendation:** Make the carrier information easier to use during trip planning and simplify or remove the scatterplot from the main path.

She explained that mobility-device performance could become another factor considered during booking if the information were easy to access.

## Participant 5: Data-Oriented Engineer

- **Main message:** He understood that reported mobility-device rates have remained higher than baggage rates, that the national rate has declined, and that carrier differences cannot be explained by volume alone.
- **Opening:** The passenger journey provided useful context, although he did not need it to understand the data.
- **Strongest visualizations:** The dual-line chart was the clearest comparison. The annual count chart was also useful because it prevented the percentage from being interpreted without considering scale.
- **Rate and count:** The difference was clear. He also found the 2020 annotation necessary because the fall in event counts could otherwise be mistaken for improved performance.
- **Carrier comparison:** The summary that twelve of fourteen carriers improved was reasonable. However, he wanted to see the number of devices handled by the two carriers whose rates increased. Smaller denominators could make their rates more variable.
- **Scatterplot:** He agreed with the conclusion that there was no clear positive relationship between volume and rate. However, the chart made the reader depend too heavily on the explanatory text. He suggested that a simpler table or comparison among major carriers might communicate the finding more precisely.
- **Policy marker:** The text avoided an unsupported causal claim, but the visual marker remained stronger than the evidence justified.
- **Pacing:** He was comfortable with the amount of data but found some of the interpretive sentences repetitive. He also felt that the policy section could be shorter because the data cannot isolate the rule’s effect.
- **Call to action:** Checking recent carrier rates was logical if the information was easy to find. Reporting incidents was reasonable for accountability, but the story did not yet show what happened after a report was filed.
- **Main recommendation:** Add carrier volume or a small-sample note to the carrier comparison, simplify the scatterplot, and make the treatment of the January 2025 rule visually consistent with the cautious language.

His clearest criticism of the scatterplot was that he had to trust the text more than the visual.

# Shared Findings

## The Main Message Was Clear

All five participants understood the central message. Mobility devices continue to be reported mishandled at a higher rate than checked baggage. The rate has declined, but a substantial disparity remains, and carrier performance varies.

The additional three conversations produced the same broad interpretation. None of the participants misunderstood the story as claiming that the problem had been completely resolved.

## The Opening Successfully Established the Stakes

The “two separate journeys” framing helped readers understand when the passenger loses direct control over the device. The interaction design, medical, and frequent-traveler participants found this section especially effective.

Several participants wanted the separation stage to receive more visual emphasis. They also wanted the human consequences to return later in the story so that the middle would not become entirely focused on rates and methodology.

## The Line Chart and Annual Count Were the Strongest Visuals

The annual rate comparison was the clearest chart for every type of participant. Readers could see the persistent gap without needing a long explanation.

The total of nearly 63,000 reported events was also memorable. It helped participants understand why a rate near one percent can still represent a significant recurring problem.

The distinction between rate and count was clear. The 2020 annotation was considered important, although it could be made slightly easier to notice.

## The Scatterplot Was the Weakest Visualization

Every participant identified some difficulty with the scatterplot. The public policy participant valued its analytical purpose, and the engineer agreed with its conclusion. However, even these data-oriented participants felt that the visual required too much support from the surrounding text.

The logarithmic scale, sparse labels, and dispersed points made the chart difficult to verify quickly. The frequent traveler and medical participant understood the conclusion mainly from the explanatory paragraph rather than the chart.

## The Policy Section Was Careful but Visually Prominent

Participants generally understood that the January 2025 rule was included as context. They did not think the story explicitly claimed that the rule caused the decline.

However, several participants noted that the vertical marker was visually prominent. A reader who skimmed the section could still mistake the rule for the turning point. Some participants also wanted a clearer but shorter explanation of what the rule changes for passengers.

## The Carrier Comparison Created Interest in Actionable Information

Participants understood that most continuing carriers improved while two did not. They also understood that improvement was broad but not uniform.

The frequent traveler wanted an easier way to check current carrier performance before booking. The engineer wanted additional information about the number of devices handled, especially for carriers with smaller denominators. Together, these comments suggest that the comparison is useful but needs more context before it can support a travel decision.

## The Middle of the Story Needs a Stronger Rhythm

Most participants felt that the middle became slightly repetitive or data-heavy. The engineer was comfortable with the amount of analysis but still noticed repeated interpretation. Other participants were ready to return to the passenger experience sooner.

The issue was the sequence of several analytical charts without enough change in pace or purpose.

## The Conclusion Worked

All five detailed participants understood “Better performance is possible” as evidence that lower rates are already being achieved and that poor outcomes are not inevitable.

The conclusion felt hopeful without suggesting that the problem had been solved.

## The Passenger Call to Action Needs More Support

Checking carrier performance before booking was considered useful across several interviews. Reporting an incident received a more skeptical response.

Participants questioned whether passengers would know how to report, whether they would have the time and energy to do so after a disrupted trip, and what effect an individual complaint would have. The final story should provide a clear reporting link without presenting reporting as the passenger’s responsibility alone.

# Conflicting Feedback

| Design Question | Different Reactions | Direction for Part III |
|---|---|---|
| How much emotional context should remain in the story? | The interaction design, medical, and frequent-traveler participants wanted the human stakes to remain visible. The engineer viewed the opening mainly as context for the data. | Keep the opening and add one brief human reminder later. Avoid adding a long hypothetical story that would slow the analysis. |
| Should the scatterplot remain? | The public policy participant valued the analytical finding. The engineer agreed with the conclusion but preferred a simpler comparison. The other participants found the chart difficult or unnecessary. | Test a simplified alternative. Move the full scatterplot to an optional section if it still requires a long explanation. |
| How much policy detail is needed? | The policy participant and engineer wanted precise causal and reporting language. Other participants were more interested in the passenger and carrier implications. | Keep a short explanation of the rule in the main story and place technical qualifications in a smaller note. |
| Should carriers be named more prominently? | The frequent traveler wanted actionable carrier names. The design participant appreciated that the chart did not feel like a ranking. The engineer wanted denominators before drawing stronger conclusions. | Keep carrier names visible, but avoid labeling carriers as simply best or worst. Add recent volume and rate information where possible. |
| How data-heavy should the middle remain? | The engineer was comfortable with the analytical density. The other participants wanted a faster path to the practical meaning. | Preserve the essential evidence but remove repeated interpretation and create a clearer transition into the carrier findings. |
| Who should carry the call to action? | Some participants valued practical passenger resources. Others emphasized that airlines and regulators should carry more responsibility. | Use two levels of action. Give passengers clear resources while presenting transparency and accountability as institutional responsibilities. |

# Identified Changes for Part III

| Research Finding | Planned Change for Part III |
|---|---|
| The separation stage was clear but passed too quickly. | Give the “Separated” stage more visual space and strengthen the transition between the passenger journey and the data. |
| Participants wanted the human stakes to remain visible later in the story. | Add one short reminder after the annual count or policy section that a damaged or delayed device can leave a passenger without independent mobility at their destination. |
| The line chart and total event count were the clearest parts of the story. | Keep these as the first two major data findings and remove unnecessary explanation around them. |
| The 2020 annotation was useful but easy to overlook. | Make the annotation slightly more visible and keep it close to the 2020 bar. |
| The rate and count distinction was clear but repeated too often. | Shorten later paragraphs that repeat the small-rate and large-count message. |
| The policy marker may still imply causation during a quick reading. | Use a lighter and more neutral marker. Label it as policy context and state directly that the decline had already begun. |
| Readers wanted to know what the federal rule changed, but some found the policy section long. | Keep a concise explanation of the rule’s main protections and move detailed qualifications into a source note. |
| Policy-minded readers emphasized that the data represent reported events. | Use the word “reported” consistently in titles, captions, and conclusions. Add a methods note explaining that the dataset cannot measure changes in reporting behavior. |
| The carrier comparison was clear, but readers wanted more context. | Add the number of devices handled to the tooltip or supporting information. Include a note that rates for smaller carriers may be more variable. |
| The frequent traveler wanted carrier information that could support booking decisions. | Add a link to a carrier data view or official source where readers can check recent performance. Keep the comparison factual rather than presenting a best-airline ranking. |
| The scatterplot was difficult for all audiences. | Test a simplified version with fewer labels and a short reading guide. Also test a table or aligned comparison of carrier volume and rate. |
| Some readers valued the scatterplot while others wanted it removed. | If the simplified chart still interrupts the story, move the full scatterplot into an optional section and keep its main conclusion in the central narrative. |
| The middle sections felt repetitive or visually flat. | Shorten repeated interpretation and add a brief transition before the carrier analysis. Use more space between the main findings. |
| The conclusion was consistently understood. | Keep “Better performance is possible” as the main conclusion and place the new call-to-action section immediately after it. |
| Checking rates felt useful, while reporting felt vague or burdensome. | Create a two-part call to action. One part will help passengers find carrier information and official reporting resources. The other will call for airlines and regulators to make carrier rates visible during booking. |
| Participants were skeptical about the effect of individual complaints. | Explain that reporting contributes to the public record and regulatory oversight without promising that one complaint will produce an immediate result. |
| The primary audience was not always clear at the end. | Address travelers who use mobility devices and people helping them plan travel first. Present the policy recommendation as the secondary action. |
| The draft still needs accessibility and technical cleanup. | Update the Shorthand metadata, remove placeholder captions, check for duplicated text, add alt text to the charts, and test the final story on desktop and mobile screens. |

The Part III revisions will focus first on the scatterplot, the policy marker, the carrier context, and the call to action. These issues affected comprehension or usefulness across several participant backgrounds. Feedback about individual style preferences will receive lower priority unless it also improves clarity, accessibility, or the needs of the primary audience.

# References

Bureau of Transportation Statistics. (n.d.). *Air Carrier Mishandled Baggage (Form 234.6)* [Data set]. U.S. Department of Transportation. Retrieved November 16, 2026, from [https://transtats.bts.gov/DL_SelectFields.aspx?QO_fu146_anzr=Zv5un0qyrq+Onttntr&gnoyr_VQ=GGD](https://transtats.bts.gov/DL_SelectFields.aspx?QO_fu146_anzr=Zv5un0qyrq+Onttntr&gnoyr_VQ=GGD)

Bureau of Transportation Statistics. (2018, October 31). *Technical Reporting Directive #30: Mishandled baggage and wheelchairs and scooters*. U.S. Department of Transportation. [https://www.bts.gov/topics/airlines-and-airports/number-30-%E2%80%93-technical-directive-mishandled-baggage-effective-jan-1-2019](https://www.bts.gov/topics/airlines-and-airports/number-30-%E2%80%93-technical-directive-mishandled-baggage-effective-jan-1-2019)

U.S. Department of Transportation. (2024, December 17). *Ensuring safe accommodations for air travelers with disabilities using wheelchairs* (Final rule, 89 Fed. Reg. 102398). [https://www.transportation.gov/airconsumer/final-rule-ensuring-safe-accommodations-air-travelers-PDF](https://www.transportation.gov/airconsumer/final-rule-ensuring-safe-accommodations-air-travelers-PDF)

U.S. Department of Transportation. (n.d.). *Assistive device: Stowage, damage, and delay*. [https://www.transportation.gov/resources/individuals/aviation-consumer-protection/assistive-device-guides/assistive-device-stowage](https://www.transportation.gov/resources/individuals/aviation-consumer-protection/assistive-device-guides/assistive-device-stowage)

U.S. Department of Transportation. (n.d.). *Air travel complaints*. [https://www.transportation.gov/airconsumer/complaint-process](https://www.transportation.gov/airconsumer/complaint-process)

Camilo, V. (n.d.). *Black and gray wheelchair on blue floor* [Photograph]. Unsplash. [https://unsplash.com/photos/black-and-gray-wheelchair-on-blue-floor-7NoYTT9OmiI](https://unsplash.com/photos/black-and-gray-wheelchair-on-blue-floor-7NoYTT9OmiI)

# AI Acknowledgements

For Part II, I used OpenAI’s ChatGPT to explore ways to organize the Shorthand story, clarify the policy section, and narrow the intended audience. These conversations served as planning support. I reviewed the source material, conducted the data analysis, created the visualizations and Shorthand draft, conducted the interviews, and made the final writing and design decisions.

