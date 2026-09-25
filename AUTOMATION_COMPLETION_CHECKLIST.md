# Automation Completion Checklist

An automation firing successfully does not necessarily mean the business outcome completed.

## Before calling a workflow complete

Check:

- Did the trigger fire?
- Did the intended action run?
- Did the destination system receive the correct data?
- Was the result independently read back?
- Did the customer-facing state change?
- Did any partial failure create a duplicate, stale record, or silent error?
- Is there evidence linking the intended operation to the final state?

## Examples

**Email outreach:** “send attempted” is not the same as delivered, replied, or converted.

**Publishing:** “scheduled” is not the same as publicly live.

**Website update:** “save succeeded” is not the same as the public page showing the correction.

**Commerce:** “checkout opened” is not the same as successful settlement and fulfillment.

**Data sync:** “job completed” is not the same as the destination containing the right record.

> **AUTOMATION IS NOT COMPLETION. VERIFICATION IS COMPLETION.**

Creator Desk AI builds verification-first services and machine utilities. [Start here](./START_HERE.md).
