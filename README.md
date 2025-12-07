#   запускает виртуальную среду 
 python -m venv .venv


# запускает обучение 
 python -m src.baseline.prepare_data 
 python -m src.baseline.train
 python -m src.baseline.predict
 python -m src.baseline.validate
 