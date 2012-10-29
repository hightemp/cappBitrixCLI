bitrix-cli
==========

	Usage: 
		bx command [parameters]

	Available commands:

		c, [create]
			page NAME [ALIAS PATH COMPONENTS..]           # Create a bitrix php page
			tpl TEMPLATE [ALIAS DESCRIPTION COMPONENTS..] # Create a template using components
			ibl IBLOCK IBLOCK_TYPE [CODE]                 # Create a iblock
			cmp COMPONENT [ALIAS DESCRIPTION]	          # Create a component
			tplcmp TEMPLATE COMPONENT                     # Create a component's template copy for the site template
			mdl MODULE [ALIAS DESCRIPTION]	              # Create a module
			menu NAME IBLOCK

		r, [remove]
			page NAME [PATH]
			tpl TEMPLATE
			ibl ID [NAME CODE]
			cmp COMPONENT
			cmpin TEMPLATE COMPONENT
			mdl MODULE

		g, [generate]
			codes IBLOCK_ID [NAME CODE]
			tplcmp TEMPLATE

		cl, [clear]
			iblock ID [NAME CODE]

		l, [list]
			cmp
			mdl
			tpl
			tplcmp TEMPLATE

		m, [module]
			install MODULES
			unintall MODULES

		i, [import]
			products
				magento HOSTNAME APIUSER APIKEY CATEGORY_ID IBLOCK_ID
				xls FILENAME IBLOCK_ID

		t, [tools]
			pqt                              # Products quantity trace
			tm                               # Test mail
			oct LOGIN PASSWORD               # Optimize and check all tables
			bmysql LOGIN PASSWORD HOST ITERS # Make a benchmark for mysql

		mysql
			drop table TABLE
			drop database DATABASE
			truncate table TABLE
			truncate database DATABASE

		w, [watcher]
			start TEMPLATE
			stop TEMPLATE

		backup [EMAIL FTP_URL]
