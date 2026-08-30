# USSD Student Information System

## Problem
University students without smartphones or reliable internet 
cannot access their student portal during high-traffic periods 
— exam results, fee statements, timetable updates become 
inaccessible exactly when demand is highest.

## Solution
A USSD-based alternative access channel allowing any student 
with a basic phone to query results, fee balances, and 
institutional updates via a structured menu system — 
no internet required.

## What this taught me
- How USSD session flows work (stateful, session-based, 
  short-lived)
- How to design for failure: timeout handling, 
  invalid input states, session expiry
- High-traffic access patterns and why portal systems fail

## Tech
Python · USSD flow logic · Session state management

## Status
Prototype — built to demonstrate the concept and flow design
