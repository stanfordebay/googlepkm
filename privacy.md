# Privacy Policy

Last updated: 2026-10-26

## What this application does
googlePKM is a personal calendar-automation application used by a single
person. It connects to Google Calendar to read existing events and create
events that the user explicitly requests.

## Google Calendar permissions
googlePKM requests one Google Calendar permission scope:

- `https://www.googleapis.com/auth/calendar.events` — read and write calendar
  events.

It does not request access to Gmail, Google Drive, or any other Google data.

## How calendar information is used
- Events are read to show the user's own schedule in a personal daily brief.
- New events are created only when the user explicitly asks for them (for
  example, by marking an item with a calendar-intent tag).

Calendar data is processed automatically for the user's own scheduling. It is
not used for advertising, profiling, or any purpose other than the user's
scheduling.

## Where credentials are stored
The Google OAuth refresh token is stored in the application owner's private
cloud secret store (Supabase secrets), not in this website and not in any
source repository. This website contains no credentials, tokens, or user data.

## Whether information is shared
No. Calendar information is not sold, shared, or disclosed to any third party.
It remains under the control of the single user who authorised it.

## How to revoke access
You can revoke googlePKM's access at any time from your Google Account →
Security → Third-party apps & services → remove googlePKM. After revocation,
the stored refresh token becomes invalid and the application can no longer
access your calendar.

## Contact
This is a personal application. For questions, contact the application owner
(the Google account that authorised it).
