---
layout: essay
type: essay
title: "Final Project Extra"
# All dates must be YYYY-MM-DD format!
date: 2025-11-04
published: true
labels:
  - Software Engineering
  - Nextjs
---

## Overview

### The problem

UH Mānoa students often want to get involved in community service, ʻāina-based workdays, and other volunteer events, but information is scattered across flyers, emails, Instagram, and word of mouth. It is hard to see everything in one place, find events that fit a student’s schedule and interests, and keep track of volunteer hours for scholarships, resumes, or personal records.

### The solution

We propose a web application that centralizes local community service and volunteer opportunities for UH Mānoa students.  

Students will be able to:

- Create an account and set a profile with preferred causes (ʻāina restoration, beach cleanups, keiki/kupuna support, animal care, etc.), availability, and general location/transportation.
- Browse and filter upcoming opportunities by cause, date, location, and time commitment.
- View detailed pages for each event and sign up directly through the site.
- Log participation and keep a personal history of volunteer hours and reflections.

The “special sauce” is that the app uses each user’s profile and history to personalize the experience. After logging in, users see recommended events, a **“Match My Interests”** filter that surfaces aligned opportunities, an **“I’m Feeling Helpful”** button that suggests a random event within their constraints, and a dashboard of their total hours and recent activity.

Local organizations and UH clubs can post opportunities and connect with volunteers who care about their cause.

## Names of the proposers

This project proposal was collaboratively written by:

- *[Add your name(s) here]*

## Mockup page ideas

We plan to implement the following main pages:

1. **Landing page**  
   Explains the purpose of the app (connecting UH students with local service opportunities) and provides links to log in, register, or learn more.

2. **User home page (dashboard)**  
   Shows recommended opportunities based on the user’s profile, a “This Week’s Highlights” section, and a quick summary of upcoming events they have signed up for and total hours completed.

3. **Profile page**  
   Lets users set preferred causes, available days/times, general location/transportation, and optional skills or interests.

4. **Opportunities list / Filter & Search page**  
   Lists all opportunities by default with filters for cause, date/time, location, time commitment, and accessibility. Includes:
   - **“Match My Interests”** toggle (uses profile preferences).
   - **“I’m Feeling Helpful”** button for a random suitable event.

5. **Individual opportunity page**  
   Shows event details: title, organizer, date/time, location, type of work, what to bring, volunteers needed, and a “Sign Up” action for logged-in users.

6. **Post opportunity / Organization page**  
   Lets approved organizations or UH clubs post new events with all relevant details.

7. **Admin home page**  
   Allows admins to review and approve new events, edit or update existing ones, remove canceled or past events, and manage roles.

8. **Volunteer history page**  
   Shows a user’s past events, hours logged, and short reflections, plus simple totals over time.

## Use case ideas

- A new user visits the landing page, registers, fills out their profile with preferred causes and availability, logs in, and is taken to the dashboard. They open the opportunities list, filter by Saturday morning and ʻāina work, and sign up for a restoration workday.

- A returning user logs in, sees recommended events on their dashboard, toggles **“Match My Interests”**, and clicks **“I’m Feeling Helpful”** to get a random suggestion that fits their schedule. They sign up from that page.

- A UH club organizer logs in as an organization user, goes to the **Post Opportunity** page, and creates a new event with date, time, location, and description. The event is submitted for admin review.

- An admin logs in, reviews new submissions on the admin home page, approves one event, edits the location for another, and removes an old event that has already passed.

- After attending a beach cleanup, a user logs in, visits their **Volunteer history**, confirms their participation, records three hours, and writes a short reflection. Their total hours update automatically.

## Beyond the basics

Beyond basic posting and browsing, this project aims to:

- **Support local organizations and UH clubs** by making it easier to reach interested volunteers without constantly reposting across social media.
- **Encourage reflection and growth** through personal logs of hours and experiences, which students can later use for scholarships, internships, or leadership applications.
- **Highlight ʻāina-based and community-rooted work** that is central to life in Hawaiʻi and often under-advertised.
- **Provide simple, useful data** such as total hours served and patterns of involvement, which could eventually be extended into badges, milestones, or basic analytics for organizations.

The app will be implemented using **Next.js, React, Bootstrap 5**, and hosted on **GitHub**, meeting the technical requirements while focusing on a real need in the UH Mānoa and local community.
