.PHONY: init
init: init-secret

.PHONY: init-secret
init-secret: 
	mkdir -p .secret/__envrc.d
	cp -rf $(HOME)/.danny/var/secret/postgres/__envrc.d .secret/
