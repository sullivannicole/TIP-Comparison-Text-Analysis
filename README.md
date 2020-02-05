# TIP Text Analysis

## Overview
The Transportation Improvement Program (TIP) is a ["United States federally mandated requirement for all metropolitan planning organizations (MPOs)"](https://en.wikipedia.org/wiki/Transportation_improvement_program) and helps serve as an index of all the transportation projects that will draw on federal funding within at least the coming four years.  Each year, the [Metropolitan Council](www.metrocouncil.org), the MPO for the Twin-Cities region receives submissions for the TIP from stakeholder agencies from around the region (MnDOT, counties and other local jurisdictions), in both draft and final forms.  Because most projects are multi-year, description changes from year to year often elude the notice of Council planners and it can be cumbersome for submitting agencies to provide track changes for every project throughout the process.  Therefore, this project seeks to automate that textual analysis using natural language processing in Python and, after finding differences from draft to final, categorize differences as either significant (ie needing planner review) or insignificant (spelling/punctuation/capitalization changes, syntactical changes, or other additions/deletions that do not alter the overall project scope or project objective).

## Contributors
* Nicole Sullivan (nicole.sullivan@metc.state.mn.us)
* Joe Barbeau (joseph.barbeau@metc.state.mn.us)
* Jonathan Ehrlich (jonathan.ehrlich@metc.state.mn.us)