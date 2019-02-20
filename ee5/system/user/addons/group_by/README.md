'Group By' for ExpressionEngine
=====================

This simple [ExpressionEngine](https://ellislab.com/expressionengine) extension adds SQL style 'group by' (aggregate) support to the {channel:entries} tag pair. Pass a 'groupby' parameter in your channel entries loops. Supports standard entry fields, custom fields by id and field_name; 'field_id_1', 'custom_field_name')

<pre>
{exp:channel:entries channel="advertising" groupby="custom_field_name"}
{title}
{/exp:channel:entries}
</pre>

In the example above this is being used to output banner ads which are related (with custom_field_name) to a sponsor and ensure that only 1 ad from each sponsor is shown.