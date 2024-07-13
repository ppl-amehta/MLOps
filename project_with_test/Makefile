# Makefile
install:
	pip install --upgrade pip && pip install -r requirements/requirements.txt
format:
	black *.py
lint:
	pylint *.py
train:	
	python3 titanic_model/train_pipeline.py
test:
	python3 -m pytest tests/test_*.py
all: install lint test format