# Gerrit Access

There are two types of Gerrit access described here, with different powers & responsibilities. Only ask for access if you're an active member of the community. New contributors should participate in the Gerrit code review process for some time before requesting access.

## Approver Access ("approvers")

Approver access gives you power to +2 CLs and submit them. Only +2 things that you're very confident in, and generally only in a directory (or package) that you normally "own", unless it's trivial and obviously correct.

To request this access, reference https://go-review.googlesource.com/#/admin/groups/1005 in your email. See below.

## Trybot Access ("may-start-trybots")

Trybot access lets you kick off a trybot run, testing a CL in Gerrit against the most common builders. The Trybots run in a somewhat-secure and somewhat-isolated environment, but they're not perfectly security hardened. You must skim the CL for anything malicious before starting Trybots.

To request this access, reference https://go-review.googlesource.com/#/admin/groups/1030 in your email. See below

# Requesting Access

To get request either of the access types above, email bradfitz (at golang) and state which access you want (its name and group URL), and state your Gerrit email address.