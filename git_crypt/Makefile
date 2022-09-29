.PHONY: install
install:
	@docker build -t git_crypt .
	@echo
	@echo
	@echo "*******************************************************************************************"
	@echo Add this to your bash/zshrc file: alias git-crypt=\"docker run --rm -it -v \$$\PWD:/repo git_crypt git-crypt\"
	@echo "*******************************************************************************************"

.PHONY: shell
shell:
	@docker run --rm -it git_crypt bash

.PHONY: uninstall
uninstall:
	@docker rmi git_crypt
