# Verification Methodology

## Overview
This database was created using strict verification standards to ensure accuracy and reliability for Gaza students seeking scholarships.

## Verification Process

### 1. Source Identification
**Tier 1 (Required):**
- Official university websites
- Government scholarship portals
- Official foundation websites
- Direct application portals

**Tier 2 (Supporting):**
- British Council official pages
- DAAD official announcements
- UN agency official resources
- Embassy official resources

**Tier 3 (Discovery Only):**
- Scholarship aggregators (for discovery, not verification)
- News articles (for date context)
- Academic networks

### 2. Link Verification
Each application URL was tested for:
- ✅ Valid HTTP status (200, 301, 302)
- ✅ Page actually exists (no 404 errors)
- ✅ Direct application path (not search results)
- ✅ Working application form/button
- ✅ Current relevance (not archived page)

### 3. Date Verification
- ✅ Deadlines cross-checked with multiple official sources
- ✅ Year explicitly confirmed (not assumed from 2025 to 2026)
- ✅ Time zones handled correctly
- ✅ All deadlines are FUTURE-DATED as of Sept 12, 2026

### 4. Eligibility Verification
- ✅ Gaza explicitly mentioned OR
- ✅ Palestine with clear Gaza inclusion OR
- ✅ International with no geographic restrictions
- ✅ Each criterion verified against official eligibility page

### 5. Funding Verification
- ✅ Funding amounts from official sources only
- ✅ What is covered clearly documented
- ✅ Partial vs. full funding accurately labeled
- ✅ No assumptions about coverage

### 6. Evacuation/Travel Status
Four categories used:
- **EVACUATION_CONFIRMED:** Official source explicitly mentions evacuation from Gaza
- **TRAVEL_FUNDED:** Scholarship covers travel but evacuation not explicitly confirmed
- **VISA_SUPPORT:** Only visa support documented
- **NO_EVACUATION_EVIDENCE:** No evacuation/travel support mentioned

## Data Quality Rules

### ❌ REJECTED:
- Scholarships with past deadlines
- Broken or 404 links
- Unverified "open" status
- Aggregator-only listings
- 2025 data presented as 2026
- Hallucinated information
- Unclear Gaza eligibility

### ✅ ACCEPTED:
- Future-dated deadlines
- Working official URLs
- Direct source verification
- Clear Gaza/Palestine mention
- Primary source evidence
- Explicit opening announcements

## Conflict Resolution

When sources disagreed (e.g., different deadline dates):
1. Checked original official source
2. Verified date across 2+ official sources
3. If unresolved: Flagged as "CONFLICT - MANUAL REVIEW REQUIRED"
4. Contacted organization for clarification

## Evidence Collection

For each scholarship, a short quote from the official source was captured:
- Proving deadline: "Applications close October 6, 2026"
- Proving Gaza eligibility: "Open to Palestinian students from Gaza"
- Proving funding: "Full tuition, living stipend, travel costs covered"
- Source: Always cited

## Verification Scoring

**100 Points:**
- ✅ Official page verified
- ✅ Application currently open
- ✅ Deadline verified
- ✅ Eligibility verified
- ✅ Official URL works

**90 Points:**
- All above except one secondary element unconfirmed

**70-89 Points:**
- Good information but significant missing element
- Not included in OPEN_VERIFIED sheet

**Below 70 Points:**
- Insufficient verification
- Placed in POTENTIAL_OPPORTUNITIES

## Cross-Verification

Where possible, each scholarship was verified against:
1. University official scholarship page
2. Application portal page
3. Eligibility requirements page
4. Third-party announcement (if available)
5. Social media/press release (if recent)

## Limitations & Disclaimers

### What We Could NOT Verify:
- Whether Gaza students can physically travel to study (security/political situation)
- Whether visas will be granted (government decision)
- Whether students can return to Gaza (government policy)
- Actual scholarship award rates
- Informal/unofficial arrangements

### What We DID Verify:
- Scholarships are officially open for application
- Application procedures are active
- Eligibility requirements as stated
- Funding details as claimed
- Deadlines have not passed
- Links are functional

## Last Updated

**Database:** September 12, 2026
**Verification Date:** September 12, 2026
**Next Scheduled Update:** October 1, 2026

## How to Report Errors

If you find an error:
1. Check the official source directly
2. Document the discrepancy
3. Open an Issue on GitHub with:
   - Scholarship name
   - What is incorrect
   - Link to official source proving error
   - Screenshot if possible

## Methodology Philosophy

"10 verified scholarships are better than 100 unverified ones."

This database prioritizes:
1. **Accuracy** over quantity
2. **Verification** over assumption
3. **Primary sources** over aggregators
4. **Transparency** over hidden criteria
5. **Helpfulness** over completeness

---

**Maintained by:** GitHub Community  
**For:** Palestinian students from Gaza