#############
Release Notes
#############

V4.0.5

Following release includes:

* move users to internal free plan after trial period
* remove "Open in new tab" link from tableau view embed for Analytixlive
* remove public-ip library and replace with meteor server side method to obtain user public ip necessary for trusted authentication
* enable {{ds}} timestamp jinja macros for workflow
* fix /pm command for users imported via ATS
* fix for user role changed by admin/owner account right after ATS for imported Slack users, after login such user role was changed back to interactor
* fix Slack unfurl for users without ATS and slacktoken, and get firsta available added by admin, owner or other user with the right permission scope
* fix for workflows not paused after edit action
