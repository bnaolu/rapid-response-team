---
layout: default
title: USWDS Screener Prototype
subnav: USWDS Screener Prototype
permalink: /case-studies/uswds-screener-prototype/
---

# USWDS Screener Prototype

## Overview

One issue we see commonly across government websites is the need for people to fill out a simple screener form before they continue with a larger task to ensure they understand what’s being asked of them and why. When these screeners are long, onerous, and confusing, they lead to wasted time and bad data.

## Tools used

- USWDS
- Figma
- GitHub
- Jekyll

## Problem

Before filing a complaint relating to HIPPA violations with the HHS Office for Civil Rights, you are first taken through an [assistant](https://ocrportal.hhs.gov/ocr/smartscreen/main.jsf) and come across some challenges:

- A lot of text that doesn't scale well.
- Individual questions that are hard to read in mobile view.
- Questions that are awkwardly worded.

## Solution

When creating and refining these screeners, it can be helpful to prototype and test them in a working state so you can see how people interpret the questions and related responses in a realistic environment. Our goal was to build a template that incorporates best practices for accessibility, plain language, and usability to make it quick and easy to test different versions.

## Results

The screener template contains the following features:

- **Custom questions**: Set up any number of questions with their own answer text, related resources, and pathing based on responses. (Radio buttons only for now.)
- **Simple logic flow**: For each answer, direct people to the next question, an exit page, or jump ahead to the success page.
- **Linked resources**: Each question and exit page can include resource content stored in its own plain-text pages.
- **Step indicator**: Show people where they are in the process, even if you're not building the whole thing.
- **No code**: Most customization can be done by creating and editing plain-text files. No need to mess with code for the included features.
- **U.S. Web Design System**: Built on [USWDS](https://designsystem.digital.gov/) for the best in accessible, responsive, usable web experiences for government-focused sites.

## Reflection

Once this cycle project came to an "end", we shared this template with HHS representatives and a concern came up around the relationship of rapid prototyping and the reality of dealing with business and development constraints: **"when prototyping something, without knowing if you can deliver it in a certain time, it might lead to empty promises if you don't have the right tech and tools"**.

To answer this concern, it really isn't about the right tech or tools. It's about the technique. What we're trying to do is look at this in **a way to improve collaboration between design and implementation**. Working through iterations are few and far between, it's all one big iteration and then MAYBE you go back and do iterations on it. By prototyping fast and early, it can help test things before it goes into development. 

So when it's possible and when it makes sense, it's important to remember that you can start applying these techniques now with the tech and tools available to you. 
