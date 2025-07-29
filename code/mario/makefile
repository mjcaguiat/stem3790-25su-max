all: env

env:
	python3 -m venv rl-env
	#chmod 755 -R rl-env/
	sleep 5
	source "rl-env/bin/activate"
	pip install --upgrade pip
	pip install -r requirements.txt
	pip install ipykernel
	python -m ipykernel install --user --name=rl-env --display-name "Python (RL Env)"

