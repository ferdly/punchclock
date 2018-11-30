+Continue with Locations, Curriculum Courses
+Added $$catch_clear_cache_task UI so that the annual tasks can be completed easier (and that these can be run... what?... once a month?
+$$catch_clear_cache_task(s)
+Cleaned up the Launch (Course Curr Exceptions)
Cleaned up REST_GET
Cleaned Up FORCE_REFRESH
~reset_weeks_array = PPASSIVE
~reset_locationss_array = PPASSIVE
+Revisit CurrCrs Update Check, then on to 2019!
Really worked through the problems with the Refresh Script.
Use of $$catch_direct_refresh_entityid_par 
to match the $$session_exception_curriculum_course_json
Either UNSET (and Start Over) or Adjust $$session_exception_curriculum_course_json upon success
~
Major overhaul of GET_ThreeKeys
~
Build REST POST COURSE Response UI.
The Responses lead me to a number of Bugs 
(improper fieldname, improper destination 'JSON key', yada, yada)
Now it is Working! (For 2018, that is...)
~
REST Codes JSON before final testing so that Feedback is useful.
~
Successful (other than 500) POST Execution of new Course
Added Logic for DESTROY:
$$catch_destroy_exception_par for REST_RESULT 
(and other blocks, but this was the engendering block)
Nice Bootstrap4 ~'BB_asResponsePanel'
Responses can go HERE:
courses.built[0]responsestring
courses.built[0]responsekind
~
Punching Back in. Confirm Required, use PostMan for Testing...
============BEING PREPENDING TO TOP FOR CHANGES============
Punchcard for Steam Discovery Academy
Write Documentation Layouts for 'Admin New Summer' and 'Admin Close Summer', could be containers, could be links to Gdrive, but for first blush it is just going to be layouts with text blocks
Initial Two Documentation Layouts
Also, began Course Creation
Write a CriticalKeys View for the Course API
Contextual Filter by Week Nid, Include Raw Join Data for Conflict Checking
Workging through Admin OnRamp for Course Curriculum
1. Exception JSON
Check Exception JSON (Logic, REST, Session, and Layout all work)
Forgot to PUNCHIN approx 9:20 as per texts
Applied Bootstrap 4 Logical Color Classes to BN_ and BB_ for _Primary _Sescondary and _Danger_
Now I am going to work on the Multiple Build Courses based on Student Enroll Buttons JSON
Lots of Progress making as many as 6 courses at a time
More (as it occurred) work on BTL_Bootstrap theme
Going to work on Validation
Okay, built Validation Data Management, but Validation STEP per se is just around the corner
NEXT: Validation Step and Testing
Validation Step and Testing
Real Data Form
Already punched in
Forgot to PUNCHIN 3 hours ago
Lots of Good work on the Course Creation Form and the Logic and Building the Option Value JSON for the Form and better
Checkbox and RadioButton BB
Forgot to Punch In
Ready to BUILD Courses!
Form and Form UI are perfect.
Cooking with Gas for Curriculum/Course REST_POST
Lots of good work Connecting to procHOOK_REST_Interface
Documentation of Course Manage Fields on GDrive
Can't seem to stop -- make hay while the bug has you caught
Most of the Course Attribute Source Dataset is completed
This and that early in the morning
Lots of This and That - 'Ago' date contextual filter. Reanimated steamsbx
Begin Testing POST_COURSE
Good Progress. Got a little bogged down in PAUSEONERROR_PAUSE, but worth it
procSWITCH_CourseCurriculum
RESET_GET
Cleaned up to gather the necessary JSON Constants (Clear_Cache)
Now PunchOut
Made "Offset" an Error for SPAN() for now.
new vDate_Punctuate() function
Set SPAN as Week
Set DAYLIGHT as 11/15 Year
SourceDataset Build Working!
Used separate ETL Process for COMM Data
-- NOTE: It worked, Probably BAD that I ELT halfway upon Post and halfway upon Build
-- -- but IIABDFI
YaY! 
Extract-Transform- TESTING LOAD
Other than 500 successful ETL REST-POST Course
classREST Enhanced 'DESTROY'
