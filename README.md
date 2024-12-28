# Tailwind CSS Flexbox Width Issue

This repository demonstrates an uncommon issue with Tailwind CSS's fractional width classes (`w-1/2`, `w-1/3`, etc.) within flexbox containers when the parent container doesn't have an explicitly defined width. 

The `bug.html` file showcases the problem: two divs with `w-1/2` inside a flex container don't occupy equal widths because the parent lacks a defined width.

The solution, presented in `solution.html`, involves adding a width to the parent flex container, fixing the issue.