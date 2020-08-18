# Documate (Documentation Automate)

This project is intended to create a workflow system where one form of documentation source may be converted into another form
by using various extensible plugins.

It mainly stems from my angst that the same work often needs to be redone in a different format manually. I just want to eliminate, or at least minimize the manual labor part.

## Design

The concept is quite simple. Three blocks overall: Input block, Output block and an intermediate Interconnect block that works on a common denominator language/structure. I prefer JSON there (I considered JSON and XML, JSON is simpler to manipulate in python).
