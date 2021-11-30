## ${domain.title} Domain Inventory

Also see [Original Narrative][narrative]

<#list domain.items as topic>
${topic.formatSubjectLink()}
<#list topic.linkedFacts as fact>
* ${topic.formatFact(fact, "topics/")}
</#list>

</#list>

[narrative]: original-narrative.md
