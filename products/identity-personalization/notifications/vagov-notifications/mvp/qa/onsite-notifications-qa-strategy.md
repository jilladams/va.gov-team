# Onsite Notifications QA Strategy
See [#34543](https://github.com/department-of-veterans-affairs/va.gov-team/issues/34543) for reference

## Points of Contact
Testing Onsite Notifications will involve coordination across three groups (that we know of so far): Auth Exp - My VA team, VA Notify team, and folks from the Debt Management Center. Critical points of contacts and roles are listed below.

| Name | Team | Role |
|------|------|------|
| Samara Strauss| Auth Exp | PO |
| Anastasia Jakabcin (AJ)| Auth Exp - My VA | PM|
|Erica Sauve | Auth Exp - My VA | APM|
|Tze-chiu Lei | Shared Support PTEMS | QA |
| Beverly Nelson | VA Notify | PO |
| Melanie Jones | VA Notify | PM |
| Jake Uhteg | VA Notify | QA |
| Jeff Chant | DMC | PjM |
| Jill Anderson | DMC | PO/Stakeholder | 

## Initial planning/strategy questions:

| Question | Answer |
|------|-------|
|1. When will My VA team's work be done?| Targeting end of current sprint (by 5/31). Taylor is wrapping his FE work ([#36034](https://github.com/department-of-veterans-affairs/va.gov-team/issues/36034), [#40710](https://github.com/department-of-veterans-affairs/va.gov-team/issues/40710), [#41482](https://github.com/department-of-veterans-affairs/va.gov-team/issues/41482)), Tom has one ticket ([#41268](https://github.com/department-of-veterans-affairs/va.gov-team/issues/41268)) to complete that will enable VA Notifty to be able to complete connectivity testing with our API.|
|2. When will VA Notify's work be done?| Targeting by end of their current sprint which ends 5/27. They need Tom to complete [#41268](https://github.com/department-of-veterans-affairs/va.gov-team/issues/41268) (See above). |
|3. Does VA Notify need to be part of this? If so, who on their team should participate?| Yes, sounds like they should. According to Melanie they'd like to have their QA person involved (see POC table above). |
|4. Does Tze need to be part of this? If so, what does he need to do? Or can he just take a look at things once the notification has already been sent?| _Initial answer is yes. Meeting scheduled for 5/25 to discuss with him._ |
|5. What use cases do we need to test (single notification, multiple notifications, etc)? We'll want this so we can make sure the backend team sends us exactly what they need.| _TBD - hoping to answer at 5/25 meeting_ |

## Timeline

### 5/16 - 5/20
1. Tom (My VA) completes work to update tokens for vets-API (tentative)

### 5/23 - 5/27
1. VA Notify completes work and connectivity testing with My VA's API. 
2. Taylor (My VA) complets FE work 

### 5/30 - 6/3
1. My VA, VA Notify and DMC folks meet to coordinate test plan which should be scheduled to take place week 6/8 - 6/21
2. My VA and VA Notify teams address any issues with found in connectivity testing

### 6/6 - 6/10
1. QA occurs

### 6/13 - 6/17 
1. QA occurs (cont.)
2. Address any issues found in QA

### 6/20 - 6/24
1. Retest



