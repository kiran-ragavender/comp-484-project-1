# COMP 484 – Project 1: Personal Website

A 4-page website about my calisthenics and weight-training journey, built with HTML and CSS.

**Live site:** https://kiran-ragavender.github.io/comp-484-project-1/

## Pages
- **Home** (`index.html`) – what calisthenics is and why I started
- **Exercises** (`exercises.html`) – my push / pull / legs split, how I progress, and a glossary
- **Routines** (`routines.html`) – my 4-day training cycle, with a downloadable plan
- **My Journey** (`journey.html`) – a timeline of my milestones and next goals

All pages share one external stylesheet: `styles.css`.

## MDN Exploration
| Type | Item | Where it is used |
|---|---|---|
| Element | `<dfn>` | `index.html` and the glossary in `exercises.html` |
| Element | `<sub>` | `exercises.html` (VO<sub>2</sub> max) |
| Element | `<tfoot>` | `routines.html` (summary row of the training table) |
| Attribute | `srcset` | `index.html` (logo image) |
| Attribute | `download` | `routines.html` ("Download the plan" button) |
| Attribute | `datetime` | `journey.html` (dates on the log entries) |

Each one is explained in a comment next to where it is used in the code.
