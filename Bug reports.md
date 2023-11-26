**Bug reports**

**1.**

+-----------------------------------------------------------------------+
| **Summary/Title:** Profile tab - Some sections are cut off at the end |
| of the page.                                                          |
+=======================================================================+
| **Description:** In the profile tab, in the sections "Benefits" and   |
| "Skills and badges", the last squares are cut. The frame of the       |
| squares in the last row is not visible.                               |
+-----------------------------------------------------------------------+
| **Steps to reproduce:**                                               |
|                                                                       |
| 1.  Go to the mobile application "MatchIT".                           |
|                                                                       |
| 2.  Go to the profile tab, open sections "Benefits" and "Skills and   |
|     > badges".                                                        |
|                                                                       |
| 3.  Scroll to the bottom of the page.                                 |
+-----------------------------------------------------------------------+
| **Actual result:** In the profile tab in the sections "Benefits" and  |
| "Skills and badges" squares in the last row are cut off.              |
+-----------------------------------------------------------------------+
| **Expected result:** All squares should be fully visible.             |
+-----------------------------------------------------------------------+
| **Environment:** The version of application is 0.3.1.                 |
|                                                                       |
| Android - version: 12                                                 |
|                                                                       |
| Phone model: Xiaomi Redmi Note 9 pro.                                 |
+-----------------------------------------------------------------------+
| **Priority:** Low                                                     |
|                                                                       |
| **Severity:** Low                                                     |
+-----------------------------------------------------------------------+
| **Attachment:**                                                       |
|                                                                       |
| ![](./image2.jpg){width="1.805126859142607in"                   |
| height="4.02                                                          |
| 6042213473316in"}![](./image1.jpg){width="1.8054932195975504in" |
| height="4.026042213473316in"}                                         |
+-----------------------------------------------------------------------+

**2.**

+-----------------------------------------------------------------------+
| **Summary/Title:** Profile - Technologies - User can check more       |
| technologies than the limit allows.                                   |
+=======================================================================+
| **Description:** In the profile tab, in the \"Technologies\" section, |
| the user can check a maximum of 20 technologies, however, the counter |
| does not work properly. In the attached video, the user can check 21  |
| technologies, but the limit is 20.                                    |
+-----------------------------------------------------------------------+
| **Steps to reproduce:**                                               |
|                                                                       |
| 1.  Go to the mobile application "MatchIT".                           |
|                                                                       |
| 2.  Go to the profile tab, open the section "Technologies".           |
|                                                                       |
| 3.  Check 20 technologies (the counter says 20).                      |
|                                                                       |
| 4.  Check one more technology (the counter says 20, but the           |
|     > technology is checked).                                         |
+-----------------------------------------------------------------------+
| **Actual result:** The user managed to check 21 technologies, and the |
| counter shows number 20.                                              |
+-----------------------------------------------------------------------+
| **Expected result:** The limit for checking technologies is 20, and   |
| user should not be able to check more technologies than that.         |
+-----------------------------------------------------------------------+
| **Environment:** The version of application is 0.3.1.                 |
|                                                                       |
| Android - version: 12                                                 |
|                                                                       |
| Phone model: Xiaomi Redmi Note 9 pro.                                 |
+-----------------------------------------------------------------------+
| **Priority:** Medium                                                  |
|                                                                       |
| **Severity:** Medium                                                  |
+-----------------------------------------------------------------------+
| **Attachment:**\                                                      |
| [[https://drive.google.com/file/d/1znrC7kUvc3lwFFe                    |
| zHwELRaSg_7qJwlIE/view?usp=drive_link]{.underline}](https://drive.goo |
| gle.com/file/d/1znrC7kUvc3lwFFezHwELRaSg_7qJwlIE/view?usp=drive_link) |
+-----------------------------------------------------------------------+

**3.**

+-----------------------------------------------------------------------+
| **Summary/Title:** Candidate profile and MatChat - The data shown in  |
| percentages do not match.                                             |
+=======================================================================+
| **Description:** On the candidate profile, the percentages displayed  |
| for \"Technologies\" and \"Benefits\" do not match the percentages    |
| displayed in the *MatChat.*                                           |
+-----------------------------------------------------------------------+
| **Steps to reproduce:**                                               |
|                                                                       |
| 1.  Go to [[Match IT \| Početna strana - Match                        |
|     > IT]{.underline}](https://company.matchit.rs/job-offers).        |
|                                                                       |
| 2.  Click *Matches* for the job "Entry level Android developer".      |
|                                                                       |
| 3.  For the user \"Marija Takić\", click on \"Candidate Profile\".    |
|     > (See how the candidate matches in percentage with the given job |
|     > ad.)                                                            |
|                                                                       |
| 4.  Click on MatChat and compare the matching of candidates in        |
|     > percentages.                                                    |
+-----------------------------------------------------------------------+
| **Actual result:** The candidate\'s profile (user Marija Takic) says: |
| Technologies 100%, Benefits 100%. When the *MatChat* is opened, there |
| is different data in the message: Technologies 50%, Benefits 28%.     |
+-----------------------------------------------------------------------+
| **Expected result:** Data in percentages should be the same both on   |
| the candidate\'s profile and in the message on the *MatChat*.         |
+-----------------------------------------------------------------------+
| **Environment:** Windows 10 Pro, browser: Google Chrome               |
+-----------------------------------------------------------------------+
| **Priority:** High                                                    |
|                                                                       |
| **Severity:** High                                                    |
+-----------------------------------------------------------------------+
| **Attachment:**                                                       |
|                                                                       |
| ![](./image4.png){width="5.09667760279965in"                    |
| height="2.7726848206474193in"}                                        |
|                                                                       |
| ![](./image3.png){width="5.0984251968503935in"                  |
| height="2.9721052055993002in"}                                        |
+-----------------------------------------------------------------------+

**4.**

+-----------------------------------------------------------------------+
| **Summary/Title:** Job offer (Home page) does not match with the      |
| user\'s qualifications.                                               |
+=======================================================================+
| **Description:** On the homepage where jobs that user is compatible   |
| with appear, the job offer that appears says \"Technology 60%\"       |
| matched, but when the user goes to his profile, in the technology     |
| section, totally other technologies are checked, so he has 0% matches |
| with that job.                                                        |
+-----------------------------------------------------------------------+
| **Steps to reproduce:**                                               |
|                                                                       |
| 1.  Go to the mobile application "MatchIT".                           |
|                                                                       |
| 2.  Go to the homepage and see the job offer.                         |
|                                                                       |
| 3.  Go to the profile tab and open the "Technologies" section.        |
|                                                                       |
| 4.  Compare the technologies checked by the user and those found in   |
|     > the job offer.                                                  |
+-----------------------------------------------------------------------+
| **Actual result:** The data shown in percentages do not match. It is  |
| about the user \"Marija Takić\", and the job offer that does not      |
| match is \"DevOps Engineer\".                                         |
+-----------------------------------------------------------------------+
| **Expected result:** Only jobs that user is compatible with should    |
| appear on the home page.                                              |
+-----------------------------------------------------------------------+
| **Environment:** The version of application is 0.3.1.                 |
|                                                                       |
| Android - version: 12                                                 |
|                                                                       |
| Telephone model: Xiaomi Redmi Note 9 pro.                             |
+-----------------------------------------------------------------------+
| **Priority:** Critical                                                |
|                                                                       |
| **Severity:** High                                                    |
+-----------------------------------------------------------------------+
| **Attachment:**\                                                      |
| [[https://drive.google.com/file/d/1TNVc-AV_wvaU7Ol                    |
| Sst9HbEBY9CJSJIXI/view?usp=drive_link]{.underline}](https://drive.goo |
| gle.com/file/d/1TNVc-AV_wvaU7OlSst9HbEBY9CJSJIXI/view?usp=drive_link) |
+-----------------------------------------------------------------------+

**5.**

+-----------------------------------------------------------------------+
| **Summary/Title:** Profile - Technologies - The counter does not      |
| always show the correct number of checked technologies.               |
+=======================================================================+
| **Description:** In the profile tab, in the \"Technologies\" section, |
| the user can check a maximum of 20 technologies, however, the counter |
| does not work properly. Sometimes the counter shows a number less     |
| than the technology checked. In the attached video, when the user     |
| tries to check 21th technology, the counter stays the same (20), then |
| when the user unchecks that technology, the number on the counter     |
| decreases by one (19).                                                |
+-----------------------------------------------------------------------+
| **Steps to reproduce:**                                               |
|                                                                       |
| 1.  Go to the mobile application "MatchIT".                           |
|                                                                       |
| 2.  Go to the profile tab, open the section "Technologies".           |
|                                                                       |
| 3.  Check 20 technologies (the counter says 20).                      |
|                                                                       |
| 4.  Check one more technology (the counter says 20).                  |
|                                                                       |
| 5.  Uncheck the last checked technology (the counter says 19).        |
+-----------------------------------------------------------------------+
| **Actual result:** Counter number decreases by one.                   |
+-----------------------------------------------------------------------+
| **Expected result:** The counter should show the correct number of    |
| checked technologies.                                                 |
+-----------------------------------------------------------------------+
| **Environment:** The version of application is 0.3.1.                 |
|                                                                       |
| Android - version: 12                                                 |
|                                                                       |
| Phone model: Xiaomi Redmi Note 9 pro.                                 |
+-----------------------------------------------------------------------+
| **Priority:** Medium                                                  |
|                                                                       |
| **Severity:** Medium                                                  |
+-----------------------------------------------------------------------+
| **Attachment:**                                                       |
|                                                                       |
| [[https://drive.google.com/file/d/1-O_75NPDstV33Kp                    |
| -wzcqv0PVfIdELVX2/view?usp=drive_link]{.underline}](https://drive.goo |
| gle.com/file/d/1-O_75NPDstV33Kp-wzcqv0PVfIdELVX2/view?usp=drive_link) |
+-----------------------------------------------------------------------+
