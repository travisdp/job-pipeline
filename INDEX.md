# Inria Job Postings Analysis - Formal Methods Candidate

## Overview
Analysis of 111 new Inria job postings scored against a formal methods specialist profile specializing in TLA+, Event-B, formal methods, verification, and critical/safety-critical systems.

## Results Summary
- **Total postings analyzed:** 111
- **Perfect matches (Score 5):** 3 postings
- **Adjacent/strong relevance (Score 3+):** 36 postings  
- **Low FM relevance (Score 2):** 75 postings

## Deliverables

### 1. **scored_jobs.json**
Complete JSON array with all 111 postings. Each entry contains:
- `url` - Link to Inria job posting
- `title` - Job title extracted from posting
- `score` - Relevance score (0-5)
- `matching_skills` - Comma-separated list of matching skills
- `gaps` - Any gaps (primarily location-based)
- `verdict` - One-sentence assessment

**Use case:** Machine-readable format for filtering, sorting, and bulk processing.

### 2. **scored_jobs.csv**
Same data in spreadsheet format, sorted by score descending.

**Use case:** Import into Excel, Google Sheets, or other spreadsheet tools for easy browsing.

### 3. **scoring_summary.json**
Enhanced summary with:
- Metadata and scoring rubric
- Score distribution
- Perfect matches (Score 5)
- Strong adjacent matches (Score 3+)
- All recommendations grouped by tier

**Use case:** Quick reference and programmatic access to recommendations.

### 4. **SCORING_REPORT.txt**
Human-readable analysis with:
- Executive summary
- Detailed breakdown by score tier
- Location analysis
- Most common matching skills
- Actionable recommendations organized by tier

**Use case:** Read-only reference, sharing with others, printing.

### 5. **INDEX.md**
This file - navigation guide for all deliverables.

## Key Findings

### Tier 1: Perfect Matches (Score 5 - 3 positions)
These are core formal methods roles requiring direct FM expertise:

1. **2026-10150** - PhD Position F/M Interoperability for Synthetic Mathematics in a Proof Assistant
   - Skills: proof assistant, verification, security
   - Location: Paris/IDF ✓

2. **2026-10021** - Post-Doctorant F/H Bridging the gap between combinatorial proof theory and subatomic proof theory
   - Skills: formal verification, verification, security
   - Location: Paris/IDF ✓

3. **2026-10135** - PhD Position F/M Post-Quantum Protocol Transition for Internet-of-Things Systems
   - Skills: formal verification, formal specification, verification, security
   - Location: Paris/IDF ✓

**Action:** Apply immediately to all three.

### Tier 2: Adjacent/Strong Matches (Score 3+ - 33 positions)
Positions with formal methods relevance through:
- Cryptography and protocol analysis
- Programming language semantics
- Distributed systems and safety-critical work
- Static analysis and verification tools
- Model checking

**Location Note:** Only 12 of 33 are in Paris/IDF region; 21 require relocation.

**Action:** Review secondary opportunities, prioritizing Paris-based roles if relocation is a constraint.

### Tier 3: Low Relevance (Score 2 - 75 positions)
General technical positions (ML, physics, systems, infrastructure) with minimal formal methods content.

**Action:** Only pursue if higher-tier opportunities exhausted.

## Scoring Methodology

### Score 5: Core Formal Methods Roles
- Direct work with TLA+, Event-B, proof assistants, or formal verification
- Multiple core FM keywords in posting

### Score 4: Strong FM-Related
- (None found in this batch)

### Score 3: Adjacent Technical Areas
- Cryptography, programming language design, formal verification, distributed systems
- Clear connection to FM interests

### Score 2: Some Technical Relevance
- General technical positions with tangential relevance
- Missing FM-specific keywords

### Score 1-0: Minimal/No Relevance
- (None found - all postings had at least some technical content)

## Using These Files

### For Quick Review
Start with **SCORING_REPORT.txt** for an overview and high-level recommendations.

### For Detailed Exploration
Use **scored_jobs.csv** in a spreadsheet tool to filter and sort by:
- Score (descending)
- Location (gaps column)
- Specific matching skills

### For Programmatic Access
Import **scored_jobs.json** or **scoring_summary.json** into your scripts or tools for:
- Filtering and custom sorting
- Bulk processing
- Integration with job tracking systems

## Key Statistics

| Metric | Count | % |
|--------|-------|---|
| Perfect matches (Score 5) | 3 | 2.7% |
| Strong relevance (Score 3+) | 36 | 32.4% |
| Low relevance (Score 2) | 75 | 67.6% |
| Paris/IDF location | 36 | 32.4% |
| Other locations | 75 | 67.6% |

### Most Common Matching Skills (Score 3+ jobs):
1. Security (36 postings)
2. Verification (15 postings)
3. Distributed systems (12 postings)
4. Programming language (5 postings)
5. Cryptography (3 postings)

## Next Steps

1. **Read SCORING_REPORT.txt** for overview
2. **Open scored_jobs.csv** in spreadsheet
3. **Filter for Score 5 positions** → Apply immediately
4. **Review Score 3+ positions** → Prioritize Paris-based ones
5. **Use matching_skills field** to tailor application materials

---

**Analysis Date:** 2026-06-16  
**Total Postings:** 111  
**Candidate Profile:** Formal methods specialist (TLA+, Event-B, verification)
