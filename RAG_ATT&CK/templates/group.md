# {{group_name}} - {{group_id}}

**Created**: {{metadata['created']}}

**Modified**: {{metadata['modified']}}

**Contributors**: {% for contributor in metadata['contributors'] %}{{contributor}}{% if not loop.last %},{% endif %}{% endfor %}

## Aliases

{% for alias in metadata['aliases'] %}{{alias}}{% if not loop.last %},{% endif %}{% endfor %}

## Description

{{metadata['description']}}

## Techniques Used

|Matrix|Domain|Platform|Technique ID|Technique Name|Use|
| :---| :---| :---| :---| :---| :---|
{% for t in metadata['techniques'] %}|{{t['matrix']}}|{% for domain in t['domain'] %}{{domain}}{% if not loop.last %},{% endif %}{% endfor %}|{% for platform in t['platform'] %}{{platform}}{% if not loop.last %},{% endif %}{% endfor %}|{{t['technique_id']}}|{{t['technique_name']}}|{{t['use']}}|
{% endfor %}