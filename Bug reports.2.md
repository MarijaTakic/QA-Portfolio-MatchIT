**<hr>﻿Bug reports<hr>**

**1.**

**Summary:** Profile tab - Some sections are cut off at the end of the page.

**Description:** In the profile tab, in the sections “Benefiti” and “Veštine i bedževi”, the last squares are cut. The frame of the squares in the last row is not visible.

**Steps to reproduce:**

1. Go to the mobile application “MatchIT”.
1. Go to the profile tab, open sections “Benefiti” and “Veštine i bedževi”.
1. Scroll to the bottom of the page.

**Actual result:** In the profile tab in the sections “Benefiti” and “Veštine i bedževi”** squares in the last row are cut off.

**Expected result:** All squares should be fully visible.

**Environment:** The version of application is 0.3.1. 

Android - version: 12 

Phone model: Xiaomi Redmi Note 9 pro.

**Priority:** Low

**Severity:** Low

**Attachment:** 
![WhatsApp Image 2023-11-27 at 17 37 45 (1)](https://github.com/MarijaTakic/QA-portfolio-/assets/149474370/2a45a97d-c5ec-4f10-afb7-866453af0560)
![WhatsApp Image 2023-11-27 at 17 37 45](https://github.com/MarijaTakic/QA-portfolio-/assets/149474370/41e6969e-dd8c-4716-b0da-f2ccaafe11ea)

<hr>





**2.**

**Summary:** Profile - Technologies - User can check more technologies than the limit allows.

**Description:** In the profile tab, in the "Tehnologije" section, the user can check a maximum of 20 technologies, however, the counter does not work properly. In the attached video, the user can check 21 technologies, but the limit is 20.

**Steps to reproduce:**

1. Go to the mobile application “MatchIT”.
1. Go to the profile tab, open the section “Tehnologije”.
1. Check 20 technologies (the counter says 20).
1. Check one more technology (the counter says 20, but the technology is checked).

**Actual result:** The user managed to check 21 technologies, and the counter shows number 20.

**Expected result:** The limit for checking technologies is 20, and user should not be able to check more technologies than that.

**Environment:** The version of application is 0.3.1. 

Android - version: 12 

Phone model: Xiaomi Redmi Note 9 pro.

**Priority:** Medium

**Severity:** Medium

**Attachment:** 
https://github.com/MarijaTakic/QA-portfolio-/blob/main/Video%20for%20bug%20report%20number%202.mp4
<hr>



















**3.**

**Summary:** Candidate profile and MatChat  -**  The data shown in percentages do not match.

**Description:** On the candidate profile, the percentages displayed for "Tehnologije" and "Benefiti" do not match the percentages displayed in the *MatChat.*

**Steps to reproduce:**

1. Go to [Match IT | Početna strana - Match IT](https://company.matchit.rs/job-offers).
1. Click *Matches* for the job “Entry level Android developer”.
1. For the user "Marija Takić", click on "Profil kandidata". (See how the candidate matches in percentage with the given job ad.)
1. Click on MatChat and compare the matching of candidates in percentages.

**Actual result:** The candidate's profile (user Marija Takic) says: Technologies 100%, Benefits 100%. When the *MatChat* is opened, there is different data in the message: Technologies 50%, Benefits 28%.

**Expected result:** Data in percentages should be the same both on the candidate's profile and in the message on the *MatChat*.

**Environment:** Windows 10 Pro, browser: Google Chrome

**Priority:** High

**Severity:** High

**Attachment:**
![8](https://github.com/MarijaTakic/QA-portfolio-/assets/149474370/3b2759dc-fa90-46ef-96bd-d57f1c881939)
![9](https://github.com/MarijaTakic/QA-portfolio-/assets/149474370/10ce53c4-0045-42b7-bc9a-4a1b6d30b2d2)

<hr>

**4.**

**Summary:** Job offer (Home page) does not match with the user's qualifications.

**Description:** On the homepage where jobs that user is compatible with appear, the job offer that appears says "Tehnologije 60%" matched, but when the user goes to his profile, in the technology section, totally other technologies are checked, so he has 0% matches with that job.

**Steps to reproduce:**

1. Go to the mobile application “MatchIT”.
1. Go to the homepage and see the job offer.
1. Go to the profile tab and open the “Tehnologije” section.
1. Compare the technologies checked by the user and those found in the job offer.

**Actual result:**  The data shown in percentages do not match. It is about the user "Marija Takić", and the job offer that does not match is "DevOps Engineer".

**Expected result:** Only jobs that user is compatible with should appear on the home page.

**Environment:** The version of application is 0.3.1. 

Android - version: 12 

Telephone model: Xiaomi Redmi Note 9 pro.

**Priority:** Critical

**Severity:** High

**Attachment:** 
https://github.com/MarijaTakic/QA-portfolio-/blob/main/Video%20for%20bug%20report%20number%204.mp4
<hr>



















**5.**

**Summary:**  Profile - Technologies - The counter does not always show the correct number of checked technologies.

**Description:** In the profile tab, in the "Tehnologije" section, the user can check a maximum of 20 technologies, however, the counter does not work properly. Sometimes the counter shows a number less than the technology checked. In the attached video, when the user tries to check 21th technology, the counter stays the same (20), then when the user unchecks that technology, the number on the counter decreases by one (19).

**Steps to reproduce:**

1. Go to the mobile application “MatchIT”.
1. Go to the profile tab, open the section “Tehnologije”.
1. Check 20 technologies (the counter says 20).
1. Check one more technology (the counter says 20).
1. Uncheck the last checked technology (the counter says 19). 

**Actual result:** Counter number decreases by one.

**Expected result:** The counter should show the correct number of checked technologies.

**Environment:** The version of application is 0.3.1. 

Android - version: 12 

Phone model: Xiaomi Redmi Note 9 pro.

**Priority:** Medium

**Severity:** Medium

**Attachment:** 
https://github.com/MarijaTakic/QA-portfolio-/blob/main/Video%20for%20bug%20report%20number%205.mp4
<hr>
