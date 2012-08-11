bitrix-cli
==========

Usage: 
	bx command [parameters]

Available commands:

c[reate]
	page name [alias] [path] [components..]       # Create a bitrix php page
	tpl name [alias] [description] [components..] # Create a template using components
	ibl name iblock_type [code]                   # Create a iblock
	cmp name [alias] [description]	              # Create a component
	cmpin template_name name                      # Create a component's template copy for the site template
	mod name [alias] [description]	              # Create a module

r[emove]
	page name [path]
	tpl name
	ibl id [name] [code]
	cmp name
	cmpin template_name name
	mod name

cl[ear]
	iblock id [name] [code]

i[mport]
	products
		magento hostname apiuser apikey category_id iblock_id
		xls filename iblock_id
