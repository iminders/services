install:
	pip install wandb
	# export PATH=~/.local/bin:$PATH
up:
	# https://docs.wandb.com/self-hosted/local
	# docker run --rm -d -v $(DATA_HOME)/wandb:/vol -p 8080:8080 --name wandb wandb/local
	wandb local

down:
	docker stop wandb
