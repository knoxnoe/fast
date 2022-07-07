---
id: fast-foundation.columndefinition.headercellfocustargetcallback
title: ColumnDefinition.headerCellFocusTargetCallback property
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[@microsoft/fast-foundation](./fast-foundation.md) &gt; [ColumnDefinition](./fast-foundation.columndefinition.md) &gt; [headerCellFocusTargetCallback](./fast-foundation.columndefinition.headercellfocustargetcallback.md)

## ColumnDefinition.headerCellFocusTargetCallback property

Callback function that returns the element to focus in a custom cell. When headerCellInternalFocusQueue is false this function is called when the cell is first focused to immediately move focus to a cell element, for example a cell that is a checkbox could move focus directly to the checkbox. When headerCellInternalFocusQueue is true this function is called when the user hits Enter or F2

<b>Signature:</b>

```typescript
headerCellFocusTargetCallback?: (cell: DataGridCell) => HTMLElement;
```