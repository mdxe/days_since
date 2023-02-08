## Days Since Date - Online Calculator App

Minimal website that shows how many days have passed since a selected date. It is a static website so the host/server reads saved date from URL parameter. To save a new date, simply create a new local bookmark along with name and/or tags (description and tags are client-side only). The goal for this little project wast to be able to host it on Github Pages (barebone/baremetal/no framework website).  It works as-is, but I somewhat failed as it still requires JavaScript for the form submission.

## Usage

It is a static website using only HTML, JS and CSS.. so it has no requirements, besides a web server:

1. Copy all files to any web host and navigate to index.html

2. Bookmark generated url or click "Add to Home Screen" to save your date

## Demo
- https://mdxe.github.io/days_since/  (hosted for free on Github Pages)

## Todo
- [ ] TO FIX HIGH PRIORITY: when calendar pops up on Chrome/Android, OK button doesnt show
- [ ] TO FIX: Automatically propose mobile users "add to home screen" on first visit (or when new date is selected)
- [ ] TO DO: Display visual effect when new date is set on page load
- [ ] TO FIX: Javascript should not be required for form submission