## SOC ANALYST MATURITY MODEL

Description: Rubric/maturity model for cyber security Security Operations Center (SOC) analysts. This is intended to be a guide to assess analysts individually, but also the team as a whole. No person should be expected to be great at everything, but where one individual is lacking, another should be excelling. This, in turn, will help create a well-rounded SOC.

| Category | 0 | 1 | 2 | 3 | 4 | 5 |
| --- | --- | --- | --- | --- | --- | --- |
| **Analysis** | not observed | copy/pastes logs into analysis notes | participates in log preservation (screenshots, log export, etc.) | asks for help in a timely manner | interprets logs in analysis rather than copy/paste | looks for *intent* when performing analysis |
| **Confidence** | not observed | analyst is largely unsure if they have come to the correct conclusion | actively seeks out new alert signatures or challenging cases to imrpove their skills | analyst is mostly sure of conclusions drawn, but regularly asks for a second opinion | takes a step back to look at the bigger picture, is confident in analysis and actions taken | is decisive and provides rationale for their actions, acts as a technical lead for peers |
| **Escalations** | not observed | checks with peers before escalating | escalated cases have thorough analysis that exhausts relevant logs | analyst understands attackers intent (why the rule fired and what is risky about it) | analysis shows clear direction (analyst understands what they've looked at and what logs/actions need to come next) | escalation provides an accurate recommendation with clear rationale |
| **Follow-Up** | not observed | analyst follows their escalated cases to see what next tier determines | reviews old malicious cases during downtime | reviews team current malicious cases that have been escalated | asks for feedback on escalated malicious cases | creates query for team to monitor malicious cases (past and present) |
| **Innovation** | not observed | submits tuning suggestions | submits rule recommendations | suggests new ideas to improve team efficiency | helps design and implement dashboards or tools | acts as primary analyst for design and implementation of new ideas |
| **Inter-team networking** | does not work with other teams | occasionally works with other teams on cases | regularly works with other teams on cases | works with other teams to imrpove team processes | works with other teams to develop/improve departmental processes | works with other teams to develop/improve company processes |
| **\*Intuition** | not monitored | < 0.5 | 0.5 - 0.79 | 0.8 - 0.89 | 0.9 - 096 | >= 0.97 |
| **Knowledge-sharing** | not observed | assists peers on cases | creates short presentations or write-ups to share with team | trains/coaches new team members | performs demos of work, tools, or other relevant topic | creates knowledge item that is shared to the department or organization (i.e. awareness training, all hands presentation) |
| **Ownership** | not observed | participates in process review/update | co-owns a team process or tool | owns and maintains a team process or tool | owns and maintains 2-4 team processes or tools | manages team document management system with periodic review |
| **Situational awareness - environment** | not observed | has a general grasp of team tools | understands team tools and how to use them properly | understands general company environment (tooling, naming conventions, user identification, etc.) | thoroughly understands company invronment (network topology, network infrastructure, config policies, etc.) | acts as a team Subject Matter Expert (SME) for company environment | 
| **Triage** | not observed | performs triage on assigned cases in under 15 minutes, asks peers for help in a timely manner | performs triage on assigned cases in <= 5 minutes | when multiple unassigned cases are in queue, triages cases and selects highest priority case first | with multiple unassigned cases, communicates priority based on traige to the team | delegates unassigned cases to team members based on triaged priority and skill of analysts | 
| **Verbal Skills** | not observed | participates in team meetings | performs short demos in a small team setting | gives presentations at a team level | gives presentations at a departmental level | participates in leadership calls |
| **Written Skills** | not observed | thought process is understood when reading analysis notes | analysis notes are well-organized and queries/steps are able to be replicated | analysis and emails are well-written with minimal typos | writes team processes and procedures | provides intelligent feedback on new team processes written by others |
| **\*Special Interest** | not observed | - | - | - | - | - |
<br>
<br>


**\*Intuition**<br>
- intuition is the ability to understand something immediately and without the need for conscious reasoning<br>
- measuring:<br>
  - in ticketing system, create a timer and integrate a feature that will ask if the case is a benign positive or true positive after 2-5 minutes of assignment to analyst<br>
  - divide number of correct 2-5 minute determinations by total number of cases that analyst worked to get an intuition (or pre-analysis accuracy) rating<br>
  - IMPORTANT: the analysts's response will have no bearing on the actual case, this will just be compared with the final determination after analysis is completed<br>
- scale is loosely based on common US academic grading scale as it has been tested over a long time period<br>
<br>
<br>


**\*Special Interest**<br>
- specific area of interest to analyst (automation, cloud analysis, forensics, IR, malware analysis, project management, etc.)<br>
- path should be developed by analyst and their manager/mentor<br>
<br>
<br>


**Suggested 1:1 Format**<br>
- Case review (1-3 cases) with feedback/constructive criticism<br>
  - per case: one thing analyst did well, one - two things to improve <br>
- What is your 1-year career goal?<br>
- Develop three SMART goals:<br>
  - Analyst sets a goal to improve their skills for current position<br>
  - Analyst sets a goal to improve their skills for 1-year goal position<br>
  - Manager/Mentor sets a goal for analyst based on overall SOC MM score<br>
<br>
<br>
