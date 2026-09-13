
## Recent files
${query[[from p = index.tag "page" 
where p.created:startsWith("2026") 
order by p.created desc limit 15
select templates.pageItem(p)
]]}
