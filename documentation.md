---
layout: layout
section: remote
permalink: /documentation/
---

# Documentation

It's important to us to keep SRCCON events small enough to feel friendly and conversational, but we also care about getting the ideas and conversations that take place into the wider world. The most important way this happens is when attendees return to their newsrooms and put new skills and approaches to work, but we also document as extensively as possible. This page collects resources you can refer back to as you bring SRCCON:POWER home with you:

* [Transcripts](#transcripts)
* [Session notes & resources](#session-notes--resources)
* [Session write-ups on Source](#session-write-ups)

## Transcripts

Our captioner provided live transcription of all our talks at SRCCON:POWER. Those transcripts are marked on [our full schedule](/schedule), or you can use the lists below. If you notice something that needs to be fixed, we'd love your [pull requests](https://github.com/opennews/srccon-power) or [emails](mailto:srccon@opennews.org).

<div>
    <h3>Thursday</h3>
    <table>{% assign thursday = site.data.schedule | where:"day","Thursday" %}
{% for session in thursday %}
        {% if session.transcription != "" %}<tr><td>{{ session.time }}</td><td><a href="/transcripts/SRCCONPOWER2018-{{ session.id }}">{{ session.title }}</a></td></tr>{% endif %}
{% endfor %}
    </table>
</div>

<div>
    <h3>Friday</h3>
    <table>{% assign friday = site.data.schedule | where:"day","Friday" %}
{% for session in friday %}
        {% if session.transcription != "" %}<tr><td>{{ session.time }}</td><td><a href="/transcripts/SRCCONPOWER2018-{{ session.id }}">{{ session.title }}</a></td></tr>{% endif %}
{% endfor %}
    </table>
</div>

## Session Notes & Resources

All sessions at SRCCON:POWER have a collaborative etherpad that facilitators and attendees can use to share links and capture notes on discussions as they take place. Each entry on [our schedule](/schedule) has a link to that session's etherpad. We also collect slide decks, worksheets, and other documentation right here—if you're a facilitator and you have session resources to share, [let us know](mailto:srccon@opennews.org)!

* ["Funders: Can’t live with ’em. Can’t live without ’em!" session notes](https://etherpad.opennews.org/p/SRCCON2018-funders)
* ["Historical legacies of resistance in journalism" session notes](https://etherpad.opennews.org/p/SRCCON2018-legacies-resistance)
* ["Influence versus authority: wielding power at all levels of an organization" slides](https://docs.google.com/presentation/d/1buvRyWCRgCJXTnQ9iYgQy_tHEQF8QrXsJyGqF5sLhC8/edit#slide=id.p)
* ["Is this what democracy looks like? Meeting democratic challenges with collective solutions" session writeup: "5 ways to make your workplace more democratic"](https://medium.com/@simongalp/5-ways-to-make-your-workplace-more-democratic-730aa1fdc87f)
* ["Is this what democracy looks like? Meeting democratic challenges with collective solutions" session notes](https://etherpad.opennews.org/p/SRCCON2018-meeting-democratic-challenges)
* ["Is this what democracy looks like? Meeting democratic challenges with collective solutions" slides](https://docs.google.com/presentation/d/1HKuojK5a3hYM34xYLknvymBSGlbxK2tfnSViT0NXo4w/edit#slide=id.g49e02677f0_2_0)
* ["Is this what democracy looks like? Meeting democratic challenges with collective solutions" reading list](http://bit.ly/srcconbooks)
* ["Minding the (Accessibility) Gap" session notes](https://etherpad.opennews.org/p/SRCCON2018-accessibility-gap)
* ["Minding the (Accessibility) Gap" slides](https://slides.com/kevinhuber/deck-5/live#/)
* ["Much more than eyeballs: Exploring & empowering community members’ power" slides](https://docs.google.com/presentation/d/1V21GN3LsAJNgVNizdZT8uMfeYDMCgxd_R1SGb-oQTiQ/edit?ts=5c19ae6e#slide=id.g3d31cf1e1d_2_275)
* ["Overview of Pre-trial Risk Assessment Tools: A Social Justice Perspective" session notes](https://etherpad.opennews.org/p/SRCCON2018-algorithms-social-justice)
* ["Power to the People—of Color" session notes](https://etherpad.opennews.org/p/SRCCON2018-power-people-of-color)
* ["Power to the People—of Color" slides](https://docs.google.com/presentation/d/1waXYN7b1vE4ylnwia6sU4ICwaNzghs9ho5JDkbW9ZbU/edit#slide=id.g35f391192_00)
* ["Survival Kit for Journalists of Color & Anti-Racism Self-Work for White Journalists" session notes](https://etherpad.opennews.org/p/SRCCON2018-survival-kit-journalists-of-color)
* ["Survival Kit for Journalists of Color & Anti-Racism Self-Work for White Journalists" project overview](https://www.poynter.org/newsletters/2018/a-survival-kit-for-journalists-of-color/)
* ["That’s not my job … yet" session notes](https://etherpad.opennews.org/p/SRCCON2018-not-my-job-yet)
* ["Turning news consumers into constituents for journalism" session notes](https://etherpad.opennews.org/p/SRCCON2018-news-consumers-constituents)
* ["Turning news consumers into constituents for journalism" slides](https://docs.google.com/presentation/d/1HcrjWUeRZcfA8yE5PUhzU7jdceFqC5K3q1J8OFks-lM/edit#slide=id.g3a5f7cb001_1_6)
* ["What to do when you lose (energy)" slides](https://docs.google.com/presentation/d/1Gg8erwNvYbNKBsIToZfFSRc4d0A57kfJyF9hIr6br-Q/edit#slide=id.g49f2b5991e_0_13)
* ["Why not add Puerto Rico to the standard U.S. map? Rethinking the messages in our templates and defaults" session notes](https://etherpad.opennews.org/p/SRCCON2018-rethinking-messages)
* ["Why not add Puerto Rico to the standard U.S. map? Rethinking the messages in our templates and defaults" slides](https://docs.google.com/presentation/d/1zOF6gKcdpNNu6dU1Et9Ko62eIDaUV5ebc5g0AV75kmc/edit#slide=id.g4a52e7ee7b_0_2)

## Session Write-Ups

In the leadup to SRCCON:POWER, we featured a selection of Q&As with speakers about the topics and research they brought to this year's event. You can [find the series on Source](https://source.opennews.org/articles/tags/srcconpower-q-a/).

After SRCCON events, we also publish a series of [session summaries on Source](https://source.opennews.org/articles/tags/srcconpower/) that dig into the things people learned during conversations and workshops. If you publish your own writeups or blog posts, we'd love to [hear about them](mailto:source@opennews.org) so we can help you share them with everyone!
