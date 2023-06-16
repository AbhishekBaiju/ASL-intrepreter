# ASL-intrepreter


This project aims to recognize sign language gestures using computer vision and machine learning techniques.

## Requirements

- Python (version X.X.X)
- Webcam or video input device

## Installation

1. Clone the repository:
   ```git clone https://github.com/AbhishekBaiju/ASL-intrepreter.git```

3. Navigate to the project directory:
   ```cd ASL-intrepreter```


3. Set up a virtual environment (optional):

- Create a virtual environment:
  ```
  python -m venv myenv
  ```

- Activate the virtual environment:
  - On Windows:
    ```
    myenv\Scripts\activate
    ```
  - On macOS and Linux:
    ```
    source myenv/bin/activate
    ```

4. Install the required dependencies:
   ```pip install -r requirements.txt```


## Usage

### Data Collection

1. Run the data collection script to collect ASL gesture data:
   ```python data_collection.py```
 
- The script will load the collected data, train the model, and save it as `keras_model.h5` in the `Model` directory.

### ASL Interpretation

1. Run the ASL interpretation script to test the model in real-time:
   ```python test_code.py```

- Ensure that your webcam or video input device is connected and functioning properly.
- The script will utilize the webcam to interpret ASL gestures in real-time and provide visual feedback.

## License

[MIT License](LICENSE)
