# Saunatech Style Guide

Status: draft  
Owner: Saunatech  
Language: en  
Last reviewed: 2026-05-17

## Executive Summary

Saunatech's product UI uses a restrained, modern, wellness-oriented identity with light editorial surfaces and deep blue-green accents. The system should feel practical, premium-leaning, operationally credible, and calm.

Use dark fjord blues, cool slate neutrals, warm ember/copper highlights, rounded cards, and generous whitespace.

## Visual Signals

- Use Manrope for headings, body, labels, and UI text when available.
- Build the palette around fjord, fjordDeep, snow, mist, glacier, and slate neutrals.
- Prefer rounded cards and panels with low visual noise: 1px borders, soft fills, and limited shadows.
- Use dark footer or hero sections where helpful.
- Use small uppercase labels and status pills for metadata and operational details.

## Brand Colors

| Role | Token | Hex | Typical usage |
| --- | --- | --- | --- |
| Primary | fjord | `#184A5E` | Primary buttons, links, icons, hero accents, map actions |
| Primary dark | fjordDeep | `#0C2A3A` | Footer background, dark hero sections, legal card headers |
| Primary light | fjordLight | `#2A6A84` | Hover/focus borders, secondary emphasis |
| Accent warm | ember | `#B74E2A` | CTA emphasis, filter badge, commercial highlights |
| Accent warm 2 | copper | `#A46C43` | Secondary warm accent, use sparingly |
| Background | snow | `#F7FAFC` | Main light page backgrounds, cards, dialog surfaces |
| Background muted | mist | `#E9EEF1` | Section backgrounds, filters, header cards |
| Border | glacier | `#D7E6EC` | Standard 1px card/input borders |
| Text primary | slate900 | `#0F1A22` | Main headings and body emphasis |
| Text secondary | slate600 | `#5A6B76` | Supporting copy, labels, metadata |
| Success | success | `#2F7D4E` | Success states and positive deltas |
| Warning | warning | `#B07C19` | Pending review and warnings |
| Error | error | `#A23A2D` | Validation errors and destructive states |
| Info | info | `#2F6F9B` | Informational emphasis |

## Typography

Preferred font stack:

```css
font-family: Manrope, Aptos, "Avenir Next", Calibri, Arial, Helvetica, sans-serif;
```

| Semantic style | Size | Weight | Line height | Typical use |
| --- | ---: | ---: | ---: | --- |
| Heading XL | 40px | 700 | 46px | Hero and major page titles |
| Heading MD | 24px | 600 | 30px | Section headers, card headers |
| Body LG | 18px | 400 | 29px | Marketing subtitles, long supporting copy |
| Body MD | 16px | 400 | 26px | Default application text |
| Body SM | 14px | 500 | 21px | Metadata, secondary copy, inputs |
| Label / Eyebrow | 12px | 700 | 14px | Uppercase labels, badges, status text |

## Layout And Spacing

Use a spacing scale based on:

```text
4, 8, 12, 16, 20, 24, 32, 40px
```

Cards use 10-18px radii, 1px glacier borders, subtle fills, and generous whitespace.

## Components

- Primary buttons use fjord background and snow text.
- Ember is reserved for stronger commercial emphasis.
- Secondary buttons use snow or white fill, glacier border, and slate text.
- Cards use snow or white fill, glacier border, rounded corners, and low visual noise.
- Labels are uppercase, small, and bold.
- Focus states should use fjordLight or a clearly visible accessible outline.

## Site-Specific Notes

- `www.saunatech.no` is the company, support, compliance, and brand asset site.
- `booksauna.app` is canonical for BookSauna product pages and product legal documents.
- Avoid duplicating product legal text on `www.saunatech.no`; link to canonical BookSauna URLs instead.
