## Here is my prompt used to create the Marine MVP Initiative Brief

**Prompt:** OK so let's try it out. Based on my agent description, help me write a feature brief, using the @hdjustice/hdjustice/files/main/Templates/Initiative%20Brief%20template.md.  This is for adding Marine information on the new weather redesigned website. The outcome summary is The Marine MVP aims to provide mariners—including commercial fishermen, the Coast Guard (USCG), cruise lines, cargo ships, and recreational mariners—with an authoritative, accessible, and high-confidence digital platform for critical weather data (wind, waves, visibility) to ensure safety and efficient navigation. Existing marine page on weather.gov is found at URL https://www.weather.gov/marine/.  Some additional information about the problem is Current marine products are often presented in large, hard-to-interpret text or low-resolution charts.  This affects Commercial fishermen, Coast Guard (USCG), cruise lines, cargo ships, and recreational mariners. Stakeholder interviews show that users are going to commercial sites that offer prettier, more interactive visualizations, despite NWS expertise.
The problem cause seems to be reliance on legacy transmission methods (radio, FTP email) and a lack of integrated, mobile-friendly graphical interfaces for offshore/high seas data.
Copilot finished thinking

---

**Copilot said:** Done! I've created your **Marine MVP Initiative
Done! I've created your Marine MVP Initiative Brief and saved it to your repository.

Here's what I applied from your agent description:

✅ Accessibility as foundation — Section 508 compliance and WCAG 2.1 AA woven throughout; assistive tech users called out explicitly

✅ Inclusive design for diverse users — Three distinct user personas (commercial, USCG, recreational) with different needs and expertise levels; recognized that one-size-fits-all doesn't serve anyone well

✅ Questions you might not have considered:

How do we serve commercial mariners (domain experts) without oversimplifying?
What accessibility barriers do interactive maps/charts inherently create?
Are we removing or just adding to legacy systems (radio, email)?
Liability implications if USCG relies on NWS data for rescue operations?
✅ Strategic thinking at higher level — Focused on why users abandon NWS (not just features), and what would it take to rebuild trust

Location: /Briefs/Marine MVP Initiative Brief.md

The brief is ready for your product team to use for discovery, stakeholder alignment, and design direction. Would you like me to adjust any sections, add more questions, or create a companion research plan document?

---

**Prompt:** 
Update the "What you're building" section to consider this MVP scope from the product owners: The scope of the MVP

Must

User can access point data for all marine-related weather variables available in api.weather.gov.
User can access all coastal marine zone forecasts available in api.weather.gov
User can access all marine hazard information available in api.weather.gov
User can access all nearby buoy observation data available in api.weather.gov
User can navigate to the marine point or zone that they are most interested in

Should

User can view all marine-related weather variables in a map format
User can access other marine-related observation data (e.g. bar observations)
User can access tidal information
User can access any specialized marine forecasts (bar forecasts, etc)

Could

User can access offshore marine forecasts
User can access water temperature information

Won't

Include coastal information like rip currents, coastal hazards (beach hazard statements), surf forecasts

--- 

**Copilot said**: Done! Your Marine MVP Initiative Brief has
Done! Your Marine MVP Initiative Brief has been updated with the product owners' scope.

What I changed in "What're you building?":

✅ Replaced generic descriptions with specific, product-owner-defined features using MoSCoW prioritization:

MUST Have (5 items): Point data, coastal marine zone forecasts, hazard info, buoy observations, navigation
SHOULD Have (4 items): Map visualization, additional observations, tidal info, specialized forecasts
COULD Have (2 items): Offshore forecasts, water temperature
WON'T Have: Coastal/rip current/surf forecasts (with clear reasoning)
✅ Applied your PM philosophy:

For each feature, I included "Why this matters" tied to user needs, not just the what
Highlighted how MUST features serve commercial/USCG safety needs while SHOULD features polish the recreational experience
Called out accessibility implications early (e.g., "ensure maps are accessible alongside text alternatives")
Flagged realistic constraints (API rate limits, mobile screen real estate)
✅ Added strategic guidance:

New section explaining why this scope works (existing data only, addresses pain points, balances user types, realistic timeline)
Stronger risk mitigation (how scope directly reduces value/usability/feasibility risks)
Phase 2 roadmap clarity (offshore and water temp are deliberate future items, not oversights)
✅ New questions for design phase:

Navigation hierarchy for diverse users
Data density vs. clarity balance
Accessibility for maps (a real design challenge you should tackle early)
Trust-building visual cues
Mobile constraints
Offshore data timing
The brief is now aligned with product owner reality while still pushing higher-level thinking around accessibility and inclusive design. Ready to move into design phase?
