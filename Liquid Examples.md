{% assign TeamList = Content["alias:teammembers"] %}
{% assign TeamItems = TeamMemberList | list_items %}

{% assign sortedTeamItems = TeamItems | sort:"Content.ContainedPart.Order" %}

Will display a list of teammembers 
