**Bug reports**<hr>

**1.**

**Summary: Profile tab - Some sections are cut off at the end of the page.**

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

![WhatsApp Image 2023-11-27 at 17 37 45](https://github.com/MarijaTakic/QA-Portfolio-MatchIT/assets/149474370/bd9949bb-dea2-4e36-927a-31bb51f5a849)
![WhatsApp Image 2023-11-27 at 17 37 45 (1)](https://github.com/MarijaTakic/QA-Portfolio-MatchIT/assets/149474370/3bd20826-e106-4869-b6de-a663ad859767)



<hr>





**2.**

**Summary: Profile - Technologies - User can check more technologies than the limit allows.**

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
<https://drive.google.com/file/d/1znrC7kUvc3lwFFezHwELRaSg_7qJwlIE/view?usp=drive_link> 

<hr>


















**3.**

**Summary: Candidate profile and MatChat  - The data shown in percentages do not match.**

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

![9](https://github.com/MarijaTakic/QA-Portfolio-MatchIT/assets/149474370/545db271-c25e-4323-bdf3-ade43aafb8e9)
![8](https://github.com/MarijaTakic/QA-Portfolio-MatchIT/assets/149474370/cc25afe5-09b2-40c9-b11e-4723dfcf4c12)



<hr>


**4.**

**Summary: Job offer (Home page) does not match with the user's qualifications.**

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
<https://drive.google.com/file/d/1TNVc-AV_wvaU7OlSst9HbEBY9CJSJIXI/view?usp=drive_link> 
<hr>


















**5.**

**Summary:  Profile - Technologies - The counter does not always show the correct number of checked technologies.**

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

<https://drive.google.com/file/d/1-O_75NPDstV33Kp-wzcqv0PVfIdELVX2/view?usp=drive_link> 

<hr>
















**Google DevTools**


**Bug 1:**

**Summary: “Kreiranje oglasa” page -  Some text in placeholders is cut off.**

**Description:** On the "Kreiranje oglasa" page some text  in placeholder is cut off. These are the words "Država" and "Grad" (Lokacija) and "Izaberite" (Industrija).

**Precondition:**

1. User is logged in and the web application [Match IT | Početna strana - Match IT](https://company.matchit.rs/job-offers) is opened.

**Steps to reproduce:**

1. Click the “+Dodaj oglas” button.

**Actual result:** The words above are cropped and not fully visible on resolution 320 x 658 (for example Galaxy S9+).

**Expected result:** All words should be visible on any phone/laptop.

**Environment:** Chrome browser (Google DevTools) on resolution 320 x 658 (for example Galaxy S9+).

**Priority:** Medium

**Severity:** Low

**Attachment:**

![devtools 1](https://github.com/MarijaTakic/QA-Portfolio-MatchIT/assets/149474370/728ba2cf-d91b-4ecf-b742-b3b8e429dbdb)

<hr>







**Bug 2:**

**Summary: “Kreiranje oglasa” page - Some parts of the text and some buttons do not fit in the sections.**

**Description:** On the "Kreiranje oglasa" page some parts of the text and some buttons do not fit in the sections. The text and buttons jump out of the sections and are not readable at all.	

**Precondition:**

1. User is logged in and the web application [Match IT | Početna strana - Match IT](https://company.matchit.rs/job-offers) is opened.

**Steps to reproduce:**

1. Click the “+Dodaj oglas” button.

**Actual result:** Buttons in the "Benefiti" section and words in the "Načini rada" jump out of their sections.

**Expected result:** All words and buttons should be visible in their section on any phone/laptop.

**Environment:** Chrome browser (Google DevTools) on resolution 320 x 658 (for example  Galaxy S9+).

**Priority:** Medium

**Severity:** Low

**Attachment:**

![devtools 2](https://github.com/MarijaTakic/QA-Portfolio-MatchIT/assets/149474370/b89268de-ba49-4505-8be4-9e1c705c4b8c)
<hr>

**Bug 3:**

**Summary:  "Oglasi" page - Page is cut off, it is not fully visible.**

**Description:** On the "Oglasi" page, not all parts of the page are visible.

**Precondition:**

1. User is logged in and the web application [Match IT | Početna strana - Match IT](https://company.matchit.rs/job-offers) is opened.

**Steps to reproduce:**

1. Go to the “Oglasi” page.

**Actual result:** The "Oglasi" page is not entirely visible.

**Expected result:** The entire page should be fully visible.

**Environment:** Chrome browser (Google DevTools) on resolution 375 x 667; resolution 360 x 740; resolution 390 x 844 (for example iPhone SE, Samsung Galaxy S8+, iPhone 12 Pro).

**Priority:** High

**Severity:** High

**Attachment:**

![devtools 5](https://github.com/MarijaTakic/QA-Portfolio-MatchIT/assets/149474370/c16edfb9-59f8-4596-86aa-b157a211f07b)
![devtools 4](https://github.com/MarijaTakic/QA-Portfolio-MatchIT/assets/149474370/051eceef-b8af-4adb-8ee3-a5950b3489ab)
![devtools 3](https://github.com/MarijaTakic/QA-Portfolio-MatchIT/assets/149474370/2b36d45c-50b7-4f15-a01d-2c2b40771036)

<hr>

