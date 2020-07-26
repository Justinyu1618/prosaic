---
title: Adsensible
description: 2nd place at HackRPI 2019
cover: /assets/images/portfolio/adsensible1.webp
key: adsensible
---

This was a project I worked on for HackRPI 2019. 

## Motivation

Companies today are collecting an unprecedented amount of data about their users - sometimes, a scary amount. We think that users should have a say in how their data is used. Since many companies have ambiguous opt-out systems that might even reset themselves without notification, we decided to take a novel approach to preserving user privacy.
Tools Used

Built using Javascript and JQuery with Flask server backend for calling API endpoints

## Description

Adsensible will automatically perform google searches in the background that are orthogonal in meaning to your actual google searches, thus obfuscating your real data with random noise. For example, for a random search, Adsensible may choose another word like "baker" to base noise searches off of. Then, it will generate realistic search queries using the noise topic performs the search. It also sends POST request to the tracking endpoints in the link so Google believes the link was clicked. This process is repeated 50 - 100 times, while remaining light on computational resources. 

![adsensible](/assets/images/portfolio/adsensible1.webp){:class="project-img"}