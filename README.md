# Running-app-pre-MVC-spaghetti-style
A small project built intentionally in the “old way” to understand why MVC was created.

## 📌 Overview

This is a simple web application for managing running events.
Users can:

View all running events

Add a new event

Delete an event

The entire app is built in one file, with HTML, CSS, database queries, and logic all mixed together — just like developers often did before MVC became a common pattern.

This project is not meant to be clean or modern.
It is deliberately messy so I can experience, firsthand, the problems that early developers faced.

## 🎯 Purpose of the Project

The main goal is to feel the pain that led to the creation of MVC (Model–View–Controller).
Instead of reading about why MVC matters, I wanted to experience it by building a small app without any architecture or separation of concerns.

This helps me understand:

Why apps became hard to maintain

Why developers needed structure

How MVC solved real problems

What changed when MVC arrived

## What I’m Learning

By building this pre-MVC app, I am learning:

✔ How code looks when everything is mixed together

HTML, SQL, CSS, and logic inside one big file.

✔ Why separation of concerns matters

Changing the UI breaks the logic.
Changing the logic breaks the UI.

✔ How quickly technical debt appears

Even a simple feature makes the file longer, harder to read, and harder to debug.

✔ How scaling becomes painful

Adding “edit event”, “filter events”, or “user accounts” becomes messy very fast.

✔ Why MVC was invented

## Pain Points I Encountered

These are the exact problems that developers faced before MVC existed:

❌ Everything is tangled

HTML + PHP/JS + SQL + CSS live in the same file.

❌ Hard to read and navigate

The file grows fast, and finding code becomes difficult.

❌ Repeated code everywhere

Database queries, templates, and validation get duplicated.

❌ UI changes break logic

Since everything is mixed, small changes cause unexpected bugs.

❌ Impossible to scale

Adding new features quickly turns into spaghetti code.

❌ Debugging is frustrating

Logic is scattered, variable states are unclear, and errors are harder to trace.

## Next Step

I will rebuild the same Running Events App using proper MVC architecture.
This will let me clearly compare:

Pre-MVC chaos
vs

MVC structure and clarity
