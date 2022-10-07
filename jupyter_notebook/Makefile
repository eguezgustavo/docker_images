.PHONY: install
install:
	@docker build -t jupyter .
	@echo
	@echo
	@echo "**********************************************"
	@echo Copy the git-crypt script to your bin directory
	@echo "**********************************************"
	
.PHONY: uninstall
uninstall:
	@docker rmi jupyter
	@echo "**********************************************"
	@echo Remove the jupyter script to your bin directory
	@echo "**********************************************"
