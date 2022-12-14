# Meeting Minutes 9-27

## Date / Time

9-27-2022 at 11:30am

## Attendees

- Dr. Bateman
- Isaiah Lathem
- Ian Skelskey
- Zachary Jacobson

## Topics Covered

- Dr. Bateman explained the purpose of the app: to assist with the Capture-Mark-Recapture method of estimating wildlife populations. This data can then be used to perform ecological modeling and help researchers determine how biodiversity is impacted by human actions.
- Dr. Bateman specified several features that needed improvement in the current version of the app, including but not limited to:
  - Input validation taking action on each input event instead of on form submit
  - When each session is complete, the time of session is set to the time it is uploaded to the cloud, not the actual time it was completed
  - Quality of life improvements
    - SVL should be 1 decimal place
      - rounded to nearest 0.5g so only .0 and .5 should be permitted
    - VTL should be an integer
    - OTL should be <= VTL
    - Ability to edit/add to previous sessions in the same day (only same day)
    - Make it more clear that a session is over
    - Recapture column in web UI should be T/F instead of True/False
  - Need to be able to edit column names and rename species names in the web UI because they change periodically throughout the years
  - Need a merge button in the web UI for merging sessions together
- Dr. Bateman also specified the current usage of the app, as well as key terms that they use in the application domain
  - Array: a set of traps for one type of species at one location
    - There can be multiple arrays per project/location
  - Project: a location where the team collects data, contains multiple arrays 
  - Session: unique to 1 location, 1 site, and 1 array
  - Toe Clip Code: how the team records wildlife
    - Format is `/([A-D][1-5])+/` where `[A-D]` = FootId and `[1-5]` = ToeId
    - unique per species-location combination
  - Species Code: abbreviation based on scientific name
    - unique per animal class (amphibian, lizard, snake, ...)
  - SVL (snout-to-vent length): body length of a lizard, excluding the tail
  - VTL (vent-to-tail length): length of the tail only
  - OTL (original tail length): length of the original tail only, excluding any portion that has been lost and regenerated
  - Sex should be M/F/U(nknown), never blank
- Possible functionalities to include are various forms of data aggregation and graph building in the web UI to eliminate doing it by hand

## Action Item List

| **Action Item**                                              | **Owner(s)**             | **Due Date**                    |
| ------------------------------------------------------------ | ------------------------ | ------------------------------- |
| Inquire about the purpose of the Recapture checkbox if Toe Clip Code is available to identify recaptured animals automatically | Development team | Next sponsor meeting |
| Retrieve current working app from previous development team  | Development team | Before the end of the semester  |
| Find out if the current version of the app can be swapped with a newer backend implementation | Development team         | Before the end of the semester  |
| Develop an initial prototype of the updated application for feedback |  Development team | By the start of next semester |
| Incorporate the improvements given by Dr. Bateman into the next iteration of the application | Development team         | Before the end of next semester |

## Date / Time Next Meeting

TBD
