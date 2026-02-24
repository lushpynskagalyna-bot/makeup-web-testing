Title

Search returns products for invalid characters input

ID

BR_01

Related Test Case

TC_07 — Verify search with invalid characters

Environment

Browser: Google Chrome

OS: Windows

Testing Type: Manual Testing

Tools: Chrome DevTools

Severity

Major

Priority

Medium

Preconditions

User is on the homepage.

Steps to Reproduce

Enter "@@@###" in the search field.

Click Search button.

Expected Result

System should display "No results found" message.

Actual Result

System displays 112 products unrelated to the search query.

Status

Open

Notes

Search functionality does not properly validate special character input.
