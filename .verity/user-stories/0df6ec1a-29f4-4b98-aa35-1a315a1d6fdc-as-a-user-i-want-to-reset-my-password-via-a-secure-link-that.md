# As a user, I want to reset my password via a secure link that expires in 24 hours

<!-- verity-story-sync {"storyId":"0df6ec1a-29f4-4b98-aa35-1a315a1d6fdc","version":1,"origin":"verity"} -->

- Story ID: `0df6ec1a-29f4-4b98-aa35-1a315a1d6fdc`
- Status: `proposed`
- Priority: `high`
- Path: `.verity/user-stories/0df6ec1a-29f4-4b98-aa35-1a315a1d6fdc-as-a-user-i-want-to-reset-my-password-via-a-secure-link-that.md`

## Description

End users who have forgotten their password or wish to change it need the ability to securely reset their password. By providing a password reset link that expires after 24 hours, we ensure both user convenience and account security. This feature is critical to prevent unauthorized access and to comply with security best practices. The reset link should be sent to the user's registered email and become invalid after 24 hours if unused.

## Acceptance Criteria

- [ ] Given a user requests a password reset, When the system sends the reset link, Then the link should be valid for 24 hours from the time of creation.
- [ ] Given a user receives a password reset link, When the user clicks the link within 24 hours, Then the user should be able to set a new password.
- [ ] Given a password reset link has expired (after 24 hours), When the user attempts to use the link, Then the system should display an error message indicating the link is no longer valid.

## Tags

`tg_02gga2dg` `tg_ppbn6qls` `tg_e763r6wu`
