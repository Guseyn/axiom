# axiom
No Code End To End Test Solution For Web Applications

# How It Works

- User presses button record
- User engages with the web app: invokes event listeners, sends requests, redirects to different pages, etc.
- The tool records every event from the user and takes snapshots as `document.body.innerHTML` after each event, then puts it in the map: `[ { event, html } ]`
- User presses button stop
- File(s) with the records is being save according to the configuration
- User run cli command to run tests again

Every recorded state of the HTML is considered as the correct behaviour

# Benefits

- Higher test coverage with little to no effort
- No code needed at all, i.e. no need to support additional code base
- Easier to detect bugs
- We are testing the real thing

# TODO:

- [ ] We will start with custom script, maybe we will consider browser extension, but we will see
- [ ] Function that detect all events in the document
- [ ] Function that records all the events
- [ ] Function that allows to donload recordings
- [ ] Function that can emulate all the events
- [ ] Buttons record, pause and stop
- [ ] Handle page redirects
- [ ] Handle AJAX Requests
- [ ] Create logo
- [ ] Create Video
- [ ] Write an article
- [ ] Promote it
