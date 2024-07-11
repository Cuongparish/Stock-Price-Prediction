# Stock Price Prediction

## Owner information

- University: University of Science - VNUHCM

| Student Name     | Student ID | Email                         |
| ---------------- | ---------- | ----------------------------- |
| Trịnh Quốc Cường | 20120447   | 20120447@student.hcmus.edu.vn |

## App Demo

- coming soon

## Usage
- Install all package
```
pip install -r requirements.txt
```

- Run the app
```
python main.py
```

- Open: http://127.0.0.1:8050/

## Notes
- The data folder keeps old datasets which are prepared for training process. So if you want to refresh them, then run:

```
python fetch_data_service.py
```

- The models folder keep old lstm models, run the following script in order to refresh:

```
python training_service.py
```
