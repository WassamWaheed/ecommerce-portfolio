# Representative Marketplace Case Studies

These examples demonstrate the type of marketplace work and problem-solving approach used in real eCommerce operations. They use anonymized/demo scenarios and do not disclose client-confidential information.

## 1. Amazon Variation Repair

### Situation
A product family had inconsistent child attributes and a broken parent/child relationship.

### Audit
- Reviewed parentage and parent SKU fields
- Compared variation-theme values
- Checked color/size naming consistency
- Validated product identifiers and category-specific attributes

### Resolution Approach
Correct the source data first, rebuild the relationship fields consistently, submit a controlled update, then verify the live detail pages.

### Verification
- Parent remains non-buyable
- Children appear under the intended variation
- Variation values display consistently
- No new processing errors remain

---

## 2. Amazon Flat-File Error Resolution

### Situation
A bulk catalog upload produced multiple processing errors.

### Audit
- Isolated affected SKUs
- Grouped errors by code/root cause
- Checked required attributes and allowed values
- Compared submitted data with the selected product type

### Resolution Approach
Correct the master source file, test a small SKU subset, review the processing report, and only then scale the corrected upload.

---

## 3. Walmart Attribute Mapping

### Situation
A product feed contained source fields that did not align cleanly with Walmart attributes.

### Audit
- Identified required vs optional attributes
- Mapped source fields to marketplace fields
- Flagged category-dependent values for review
- Checked variant consistency

### Resolution Approach
Build a reusable mapping sheet, validate a test batch, fix source-data gaps, and verify live content after publication.

---

## 4. Multi-Channel Catalog Cleanup

### Situation
The same SKUs had inconsistent titles and attributes across sales channels.

### Audit
- Compared the master catalog with channel-specific values
- Flagged duplicates and missing data
- Standardized SKU formatting
- Separated source-of-truth data from channel overrides

### Resolution Approach
Maintain one master catalog, document channel-specific exceptions, and use QA checks before bulk updates.

> Outcomes should only be published when they are verified and non-confidential.
