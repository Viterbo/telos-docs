---
title: Manage Sections
sidebar_position: 4
hide_table_of_contents: true
---

# Manage Sections

## Reorder Document Sections

Every section has a unique id number that indicates its order in the document. Document sections can be reordered with the `reorder` action.

### ACTION `reorder`

| Parameter Name | Type | Example | Description |
| :--- | :--- | :--- | :--- |
| document\_name | name | doc1 | Name of the document to reorder. |
| new\_order | map&lt;name, uint64\_t&gt; | { sectiona: 3, sectionb: 2, sectionc: 1 } | The new section order |

```text
cleos push action amend.decide reorder '{ ... }' -p author
```

## Delete a Section

To delete a section, the section content must first be amended to an empty string. Once empty, the author can call the `delsection` action on the contract.

### ACTION `delsection`

| Parameter Name | Type | Example | Description |
| :--- | :--- | :--- | :--- |
| document\_name | name | doc1 | The name of the document with the section to delete. |
| section\_name | name | sectionc | The name of the section to delete. |

```text
cleos push action amend.decide delsection '{ ... }' -p author
```
