.PHONY: install
install:
	@docker build -t git_crypt .
	@echo
	@echo
	@echo "**********************************************"
	@echo Copy the git-crypt script to your bin directory
	@echo "**********************************************"

.PHONY: shell
shell:
	@docker run --rm -it git_crypt bash

.PHONY: uninstall
uninstall:
	@docker rmi git_crypt
