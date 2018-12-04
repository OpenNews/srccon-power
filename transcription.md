---
layout: layout
section: remote
permalink: /transcription/
---

# Transcription

SRCCON:POWER is an intentionally small event, but we also care about getting the ideas and conversations that take place there into the wider world. The most important way this happens is when attendees return home and put their new skills and approaches to work, but we also document extensively.

Our captioner will provide live transcription of all our talks at SRCCON:WORK, and links to the archives will remain below. We'll also transcribe several sessions for publication later on.

<div>
    <h3>Thursday</h3>
    <table>{% assign thursday = site.data.schedule | where:"day","Thursday" %}
{% for session in thursday %}
        {% if session.transcription != "" %}<tr><td>{{ session.time }}</td><td><a href="http://aloft.nu/stanley/SRCCONPOWER2018-{{ session.id }}">{{ session.title }}</a></td></tr>{% endif %}
{% endfor %}
    </table>
</div>

<div>
    <h3>Friday</h3>
    <table>{% assign friday = site.data.schedule | where:"day","Friday" %}
{% for session in friday %}
        {% if session.transcription != "" %}<tr><td>{{ session.time }}</td><td><a href="http://aloft.nu/stanley/SRCCONPOWER2018-{{ session.id }}">{{ session.title }}</a></td></tr>{% endif %}
{% endfor %}
    </table>
</div>

## Write-Ups

In the leadup to SRCCON:POWER, we’re featuring [Q&As with our conference speakers](https://source.opennews.org/). After the event wraps, we'll be publishing session writeups, resource lists, and more [on Source](https://source.opennews.org)—[hop on the Source newsletter](https://opennews.us5.list-manage.com/subscribe?u=71c95e9a43708843d2fdc1f09&id=996e9290cc) if you'd like a digest of those links, plus highlights from the community, as they come out.
