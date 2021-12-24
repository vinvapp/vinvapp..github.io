.Phony: submit

submit:
	@echo "Everything will be pushed" ; \
	echo "Input the commit message and press [enter]" ; \
	read message ; \
	git add . ; \
	git commit -m "$${message}" ; \
	git push origin ; \
	git log -1		