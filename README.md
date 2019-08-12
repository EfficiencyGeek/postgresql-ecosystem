# postgresql-ecosystem
<!-- https://stackoverflow.com/questions/3492153/markdown-open-a-new-window-link/5803384 -->
Overview of the capabilities and tooling directly tied to <a href="https://postgresql.org/" target="_blank">PostgreSQL</a>

Diagram hosted by draw.io (<a href="https://www.draw.io/?mode=github#HEfficiencyGeek%2Fpostgresql-ecosystem%2Fmaster%2Fpostgresql-ecosystem.drawio" target="_drawio">Edit</a>)

<iframe frameborder="0" style="width:100%;height:-197px;" src="https://www.draw.io/?lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=postgresql-ecosystem.drawio#R3VptU%2BI6FP41fMShLX3ho4K4O1evXhlHd7%2FshDa00dDUNBW4v35PaAqtoci9gHR1HCEnTZo85%2FU5Y8vqT%2BdXHCXRDQswbZmdYN6yBi3TNLqm2ZK%2FnWChJK5h5JKQk0DJ1oIR%2BRcrYUdJMxLgtPKgYIwKklSFPotj7IuKDHHOZtXHJoxW35qgEGuCkY%2BoLn0kgYiU1HB664lvmISRerVnuvnEGPkvIWdZrN7XMq3J8iefnqJiL3XRNEIBm5VE1mXL6nPGRP5tOu9jKsEtYMvXDWtmV%2BfmOBa7LHj9wR5eZ1k4SH95tO39%2Bvnz75e2YXeVAt8QzRQk1ygOM7h2qg4uFgVYy%2BtiuaHRsi5mERF4lCBfzs7APkAWiSlV0%2FoB1ZnfMBd4XhKpA19hNsWCL%2BARNdvtdfMlyrra3QLNWUlXhSwqqamrZEiZR7jaew0RfFEobUZsfmuTR9dtm06nR75T1%2Bk615sRGzIO745BOEACwccjoJFgvieCK5NZDgRnL7jPKOPLrSzH9%2FB4AjMTQmlJHiDsTXyQhxSl6eGU4ZidM7uB6rA0dVzOBY5TwuLTW7BrNxO0rgaastyRAFuGTxXqmwefZTUAPluHDyeULabyqqcGrVfcvIDMcRsAmaPnGYYCkFwgimIf85Y80RD%2B3kH%2Bl8MvHTptuwE6cTWdyMoIjQklAl4A%2B3buwa6JjwRE05MbtmG4noZjE8KBp%2BF4w2ICkZTE4elRs2zrpKjN%2Fmo%2FGQ9PLL4dYN%2B%2FunUenecSahuh6cDdGRcRC1mM6DVjiQLkGQuxUDQCZYJV4cJzIp5K33%2FIreDy%2BWgwVzsvB4tiEMN9nsqD0io5XC9bjtbrgnNJQGAYsxjnkiGRMCzna1WXsoz7eLtFKfYhEA%2Bx2A6jcmIcVIiObg4cU3DjtyrvOYY39DRvuMcppMXO%2Bd33VZBf8sl%2FrvfzjrrwXR%2FwK3mhHOV9NiX%2BR5rbK%2BI3IQsXSaekm6sHqZQ%2BJXDZL8ZXtLDn9o6ngocU89vxs%2BxRmB3IoZjmS%2FsMogYZQ6gq6CAl8Us%2BFwkh2xznS5cYzmazs4SlIuQ4faVnjEPuGIJdTrN4mY7he3mrYb7bRxovg6SMpEmM%2FpjlPAxLWvlvjqKT%2FDvOJjiVtBLJDUZZkkCGOn16N%2FTs3oRIo9PyPmWZLPgByDcS7N0dOQB2Zk%2BvJ5uAnc7OVUtjTCU3H8m8CUwdxQHiEtH7wcXN6IvH7q7XAMXohb6GuqzDRmqo6sL9y9oPSs3%2FW8LWamqHEtVW%2BimXqHWPKu5%2FuBJVLb1jRPZbCqvx9KJr1X4vdsmPqxa%2BM4jVSfayEb039A28dIZkW%2B3E8W5DVQqn%2F%2FSSaARgTB0IckW7%2FNz3McUcQWHzcYmU5qvPoDICiRq1A7RbOeRsLYdAQJIUf4oyPPNdKWRuinCGq6vCO04pVEMwC85w7BinqHvBz3ej7geg4HW82v6coOVq3Vr7UCGrzv%2FuFMkQm5xt5WsFFRGKiVT9aytqh6Eb72qNyQQ7%2FkZ2H7i9cedAxN3VW4yOcVqKUgd1r8F%2BqeoR4wQttTq4nJ3rlQLZo7fU6hw0QmnG0fZUmD9zRtjOrrk99f0JrtmrOqb7ub2D7eEUJRGh%2BOPypXhSRdWksnhHTbp%2FvCb1IHtE3r1BlyBa%2F%2BtNnknX%2F%2BBkXf4G"></iframe>

	1. Why
		a. What are the capabilities enabled with PostgreSQL?
		b. To increase the viability of PostgreSQL to those who are relatively new to it.
	2. What
		a. A diagram of the main entities providing capabilities, grouped into common areas.
		b. Languages
		c. Foreign Data Wrappers
		d. Extensions
		e. Data Store Model
			i. JSON
			ii. Columnar
			iii. Name Value
			iv. Graph
			v. Time Series at Rest
			vi. Streaming Time Series
		f. Deployment
			i. AWS
			ii. Docker
			iii. Android
		g. Load Balancer, Pooler
		h. Scalability / Replication
		i. Monitoring
		j. Rest / GraphQL Wrappers
		k. Clients
			i. PG Admin4
			ii. PGWeb
			iii. Azure Data Studio - SQL Notebook
		
		
	3. How
		a. Open Source - use github?
		b. Allow for PRs, collaboration
		c. With Links to other sites.
		d. Feedback to alex@efficiencygeek.com
