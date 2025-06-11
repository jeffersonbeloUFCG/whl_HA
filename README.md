system_packages:
  - py3-numpy
  - python3
  - libgomp
  - py3-scikit-learn
  - py3-pandas
python_packages:
  - tuya-connector-python
  - kafka-python
  - joblib==1.3.1
init_commands:
  - >-
    pip install --no-cache-dir
    https://github.com/jeffersonbeloUFCG/whl_HA/raw/main/xgboost-2.0.3-py3-none-any.whl
