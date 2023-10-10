# ADR 4: Permissions
Our approach to permissions is influenced by the need for precise location tracking, timely order updates, and an effective push notification system.
##
## Decision
We will request permissions for location services, notifications, and any other necessary device feature upon the app's first launch, with clear explanations for each.

## Rationale
In the era of data privacy concerns, being transparent about app permissions is not just a courtesy but a necessity. The request for location services stems directly from the primary feature of providing localized restaurant suggestions and accurate delivery times. Real-time order updates and push notifications ensure users are always in the fold, enhancing their experience. By explaining each permission clearly, we intend to build trust with our users, reassuring them that their data is used solely to improve their experience and not for any other purpose.
## Status
Accepted
## Consequences
- Increased user trust
- Accurate services based on user permissions.
- Possible user hesitancy if not convinced about the necessity of permissions.