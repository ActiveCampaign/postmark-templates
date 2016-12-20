{{body}}

{{#attachment_details}}

{{#each . }}

{{attachment_name}} ( {{ attachment_url }} ) ({{attachment_size}} {{attachment_type}})

{{/each}}

{{/attachment_details}}

By {{commenter_name}} at {{timestamp}}

View the comment ( {{ action_url }} ) or Manage notifications ( {{ notifications_url }} )
