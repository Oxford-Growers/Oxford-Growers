---
layout: default
title: Core Group - Oxford Growers Network
---
The core group are responsible for making initial contact with people who want to get involved in Oxford Growers Network.

You can contact us through {% include contact_email.md %}

<div id="group-members">
    {% for group_member in site.data.core_group.core_group %}
        {% include group_member.html
            group_member_name = group_member.name
            group_member_picture = group_member.picture
            group_member_pronouns = group_member.pronouns
        %}
    {% endfor %}
</div>
