# announcement-board

We are piloting a new announcement board on [Wordpress](https://sigs.esciencecenter.nl/).
We'll use this repository just to discuss [issues](https://github.com/nlesc-sigs/announcement-board/issues).

## Structure

We want to keep the announcement board simple and manageable.
Thus, we propose the following minimalistic structure:

```sh
home/       # Main entry point (see below)
├─ about/   # General information about this site
├─ SIGs/    # Static pages containing info about each SIG
   ├─ Analytics/
   ├─ UX/
   ├─ .../
```

Each new announcement is posted to `home` in the form of a blog post (see [example](https://sigs.esciencecenter.nl/structure-preserving-discretisations/)).

We'll use post tags to comfortably link each announcement with the correspondent SIG (see for instance the [posts corresponding to the Analytics SIG](https://sigs.esciencecenter.nl/tag/analytics-sig/)).
This way, we don't have to maintain any agenda.

Additionally, users can follow the announcement board via [the general RSS feed](https://sigs.esciencecenter.nl/feed/), or even subscribe to the feed corresponding to a SIG (see for instance the [Analytics feed](https://sigs.esciencecenter.nl/tag/Analytics-SIG/feed/)).
More on RSS feeds [here](https://wordpress.com/support/feeds/).

More information on the [about](https://sigs.esciencecenter.nl/about) page.

## Future developments

- Add a calendar plug-in.
- Adapt the layout to our institutional style.
- Rename to `board`, `agenda` or `announcements.esciencecenter.nl`.
