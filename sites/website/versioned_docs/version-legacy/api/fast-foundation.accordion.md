---
id: fast-foundation.accordion
title: Accordion class
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[@microsoft/fast-foundation](./fast-foundation.md) &gt; [Accordion](./fast-foundation.accordion.md)

## Accordion class

An Accordion Custom HTML Element Implements [ARIA Accordion](https://www.w3.org/TR/wai-aria-practices-1.1/#accordion)<!-- -->.

<b>Signature:</b>

```typescript
export declare class Accordion extends FoundationElement 
```

## Remarks

Designed to be used with [accordionTemplate](./fast-foundation.accordiontemplate.md) and [AccordionItem](./fast-foundation.accordionitem.md)<!-- -->.


change - Fires a custom 'change' event when the active item changes


item - The slot for the accordion items

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [expandmode](./fast-foundation.accordion.expandmode.md) |  | [AccordionExpandMode](./fast-foundation.accordionexpandmode.md) | Controls the expand mode of the Accordion, either allowing single or multiple item expansion. |