# Operational Dashboards Added

This document summarizes the new dashboards added to the CDRIntel dashboard and what each one helps the customer understand.

## 1. Missed Call Recovery

Shows customer calls that came in but were not answered.

What was added:
- Missed inbound call count
- Unique missed callers
- Repeat missed callers
- Estimated callbacks found
- Missed calls by hour
- Missed calls by branch
- Recovery queue with caller number, attempts, last missed time, branch, staff, and callback status

Why it matters:
- Helps the team identify customers who may need follow-up.
- Shows which branches or times create the most missed-call risk.

## 2. Branch Health Scorecard

Ranks branches using a simple health score.

What was added:
- Branch health score from 0 to 100
- Healthy, Watch, and Critical status labels
- Best branch and weakest branch summary
- Branch ranking chart
- Detailed branch table with connect rates, missed inbound calls, no-response outbound calls, peak miss rate, and score

Why it matters:
- Gives leadership a quick view of which branches are performing well and which need attention.

## 3. Agent Coaching

Highlights agents who may need coaching or manager review.

What was added:
- Agents needing attention
- Agents with high missed inbound calls
- Agents with low outbound connect performance
- Talk-time outlier count
- Coaching priority chart
- Volume vs inbound connect chart
- Coaching queue with reason for review

Why it matters:
- Helps managers move from raw call data to clear coaching actions.

## 4. Peak Hour / Coverage

Shows when call pressure is highest and where coverage may be weak.

What was added:
- Busiest hour
- Worst missed-call hour
- Peak missed-call rate
- Active staff peak
- Hourly call volume chart
- Hourly missed inbound chart
- Day/hour heatmap
- Branch peak-pressure ranking
- Hourly coverage detail table

Why it matters:
- Helps decide staffing, scheduling, and branch support during busy times.

## 5. Data Quality

Shows whether the uploaded CSV and branch mapping are clean enough for reliable analytics.

What was added:
- Unmapped CDR user count
- Duplicate record count
- Mapping coverage percentage
- Loaded date range
- Unmapped user list
- Duplicate record list
- Mapping gap list
- Quality issue register with suggested fixes

Why it matters:
- Helps admins fix data problems before managers rely on the dashboard numbers.

## Other Small Changes

- Added the five dashboards to the left navigation.
- Added role access:
  - Super Admin and Executive can see all new dashboards.
  - District Manager can see the new dashboards scoped to their district.
  - Staff only sees My Performance.
- Added shared filters for the new dashboards: date, district, branch, and staff where relevant.
- Added mobile layout improvements so the dashboard is usable on small screens.
- Fixed duplicate user-management markup that was creating duplicate IDs.
- Added missing handlers for duplicate logs, duplicate export, agent detail view, and Power BI CSV export.

