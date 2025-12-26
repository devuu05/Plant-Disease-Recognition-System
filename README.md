# Plant-Disease-Recognition-System
Plant Disease Recognition System


## Usage

1. **Specify the Model File Location**
   - Open the `app.py` file in a text editor.
   - Locate line 8, which contains the following code:
     ```python
     tf.keras.models.load_model("")
     ```
   - Update the empty string with the relative path to the model file. For example:
     ```python
     tf.keras.models.load_model("models/your_model_file.keras")
     ```
     Replace `your_model_file.keras` with the actual name of the model file you downloaded.

2. **Run the Server**
   - Open a terminal and navigate to the root directory of this project.
   - Run the following command to start the server:
     ```bash
     python app.py
     ```

3. **Access the Application**
   - Once the server is running, follow the instructions displayed in the terminal to access the application in your web browser.
