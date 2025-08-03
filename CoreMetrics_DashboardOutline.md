# Core metrics for City of Chicago government tracking vendor contracts
### 1.Total contract value of each Department.
**The sum of contract amounts grouped by department**
- Helps monitor and manage how taxpayer money is being spent across departments. Identifies departments with the largest spend and ensures funding aligns with city priorities.

### 2. Average Contract Value by Vendor
**Average of money amount per vendor**
- Flags unusually high or low contract values. Helps assess vendor efficiency and detect possible overbilling or underpricing that could suggest performance or compliance issues.

### 3.Percentage of Contracts Awarded to Local or Minority-Owned Businesses
**Count and value of contracts awarded to businesses flagged as local, minority-owned, women-owned, or disadvantaged**
- Promotes diversity and equity in public spending. Tracks progress toward inclusion goals, which are often mandated by local policy.

### 4.Percentage of Contracts type by Vendor
**Count and value of contracts provided by Vendors**
- This metric helps identify if procurement is overly reliant on a few vendors and detect if is have any risks, or limit of market competition, or ethics red flags (e.g., favoritism).

### 5.Vendor Retention Rate
**Percentage of vendors that appear across multiple years (or quarters, depending on granularity of start_date)**
- Long-term vendor relationships can be good — but only if based on performance and fair procurement. High retention in certain categories may prompt a review for fairness or market competitiveness.

# Filters should be showed on dashboards:
- **Departments**: Allows users to focus on spending within specific city departments
- **Vendors**: Enables tracking of individual vendor histories, recurring contracts, or spending concentration.
- **Contract Start/End Date**: Date range selector or year filter.

# Intended Audience:
- The audience could be manager of Sales Deparment, Audit team, Accounting and CEO.

# Reporting outline - Charts should be used:
1. **Score card:** For visualize number of total
2. **Pie chart:** For visualize percentage of contracts by vendor / departments
3. **Line chart**: Showing number of contracts over time (ex: by approved date)
4. **Pivot table**: Details of Vendor/Departments/... if select any filters.
5. **Combo chart**: Line with bar chart to show correlations
6. **Head Map**: To show continuity over time.