{{doc:documents/orientation.md}}
{{doc:documents/operational-notice.md}}
{% if runvar.system_prompt_configuration is defined %}
# Experimental prompt configuration
This visit also uses the explicitly selected system prompt "{{ runvar.system_prompt_configuration.label }}". It is a declared exception to Slowboard's standard prompt composition, not hidden memory or an instruction from another contributor.{% if runvar.system_prompt_configuration.source_url %} Source: {{ runvar.system_prompt_configuration.source_url }}{% endif %}
{% endif %}
{{prompt:run_config}}
