# Marine MVP -  Initiative Brief
- Created using Gemini, brief context & access to historical docs in a Google drive

## **Outcome Summary**

* The Marine MVP aims to provide mariners—including commercial fishermen, the Coast Guard (USCG), cruise lines, cargo ships, and recreational mariners—with an authoritative, accessible, and high-confidence digital platform for critical weather data (wind, waves, visibility) to ensure safety and efficient navigation.

**Related/Associated product(s)**

* [Weather.gov 2.0 Product Outline](https://vlab.noaa.gov/gitlab-licensed/NWS/Systems/DIS/Weather.gov-2.0/weathergov-django/-/wikis/Weather.gov-2.0-Product-Outline)
* [Epic #1](https://vlab.noaa.gov/gitlab-licensed/groups/NWS/Systems/DIS/Weather.gov-2.0/-/epics/1)
* Research
* Figma designs
* [Existing Marine page on Weather.gov](https://www.weather.gov/marine/)
* [Existing Coastal page on Weather.gov](https://www.weather.gov/marine/usamz)
* \[other resources?\]

## **Problem**

* **The Problem**: Current marine products are often presented in large, hard-to-interpret text or low-resolution charts.
* **Affected Parties**: Commercial fishermen, Coast Guard (USCG), cruise lines, cargo ships, and recreational mariners.
* **Evidence**: Stakeholder interviews show that users are going to commercial sites that offer prettier, more interactive visualizations, despite NWS expertise.
* **Root Cause**: Reliance on legacy transmission methods (radio, FTP email) and a lack of integrated, mobile-friendly graphical interfaces for offshore/high seas data.

## **Desired User Outcomes**

* **Direct Access**: Users can skip 3rd-party aggregators and get "ground truth" expertise directly from NWS.
* **Localized Context**: Mariners can click a specific point (lat/long) in the open ocean to get precise wind and wave forecasts rather than interpreting a zone the size of a state.
* **Improved Safety**: clearer communication of hazards like "sneaker waves," freezing spray, and dense fog.

## **Desired Business Outcomes**

* **Operational Efficiency**: Automate legacy text products and transition to a gridded, polygon-based warning system.
* **Standardization**: Replace fragmented WFO-specific marine pages with a unified Weather.gov 2.0 experience.

\---

## Measuring Success

### Key Performance Indicators (KPIs)

:bulb: Measure success against Ease of use, Service Completion, Trust/Satisfaction, Health.

:bulb: Identify balancing metrics to ensure you're not bringing about undesired outcomes.

| Metric | Baseline | Target | 1-wk post launch | 1-mo post launch |
|--------|----------|--------|------------------|------------------|
| User Trust | High reliance on Windy/private models | Increased use of NWS Point forecasts |  |  |
| Accessibility/Content | Overwhelming/scientific | AIM score of 9.5/10 |  |  |
| Data Integrity | Manual chart drawing | Automated digital grid delivery |  |  |

---

## Discovery

### Assumptions/Risks

* **Value Risk**: Mariners may continue using familiar private apps if the NWS interface isn't as user-friendly or performant.
* **Usability Risk**: Older mariners may struggle to transition from legacy text/radio products to digital maps.
* **Technical Feasibility**: Challenges in resolving "inside waters" and narrow passages with current computer models.

### Supporting research

* Initial research TBD

### Source Data

* TBD

### What are you building?

### The scope of the MVP

* Must
  * User can access point data for all marine-related weather variables available in api.weather.gov.
  * User can access all coastal marine zone forecasts available in api.weather.gov
  * User can access all marine hazard information available in api.weather.gov
  * User can access all nearby buoy observation data available in api.weather.gov
  * User can navigate to the marine point or zone that they are most interested in
* Should
  * User can view all marine-related weather variables in a map format
  * User can access other marine-related observation data (e.g. bar observations)
  * User can access tidal information
  * User can access any specialized marine forecasts (bar forecasts, etc)
* Could
  * User can access offshore marine forecasts
  * User can access water temperature information
* Won't
  * Include coastal information like rip currents, coastal hazards (beach hazard statements), surf forecasts

#### Key Decisions made

* …

#### Go-to-market comms, outreach, etc

* ...

---

## Launch Planning

### Timeline 

Describe any major milestones for this initiative including organizational, legislative, etc. constraints.\*

* Release Plan - TBD

#### Initiative Launch Dates

* Target Launch Date
  * By the end of 2026
* Actual Launch Date
  * tbd

---

   

## Screenshots

### Before

<details>
<summary>

* Existing [Weather.gov Marine page](https://www.weather.gov/marine/) (as of April 2026)

</summary>

![image.png](uploads/3c69120d2d8f44f9ecad90673644e9fa/image.png){width="489" height="600"}

</details>

### After

* TBD

---

<details>
<summary>

#### Team & Stakeholders

</summary>

 Team information

* Team Name: Weather.gov 2.0
* Gitlab Label(s): `marine_coastal`
* Product POCs: Shad Keene, Corey Pieper

Offices/departments who are critical to make this initiative successful

* Office/Department:
* Contact(s): 

</details>

