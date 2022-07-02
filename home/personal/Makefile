### Makefile for Dotfile Management ###

# [Variables]


# [Recipes]
help:
	@declare -A help=(\
		["(h)elp"]="Display this help message" \
	); \
	@for opt in "${!help[@]}"; do \
		echo "$$(opt) : $${help[$$(opt)]}"; \
	done
