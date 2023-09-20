
#  Caesar cipher {Python Game}
This Python code is an implementation of the Caesar cipher, a type of substitution cipher in which each letter in the plaintext is 'shifted' a certain number of places down the alphabet. Here's a breakdown of its functionality:

1. The `alphabet` list contains all the letters of the alphabet in order.

2. The user is asked to input either 'encode' to encrypt a message or 'decode' to decrypt a message. If the user enters anything other than these two options, they are repeatedly prompted until they do.

3. The user is then asked to input the message they want to encrypt or decrypt.

4. Next, the user is asked to input an integer which will be used as the shift number for the Caesar cipher. If the user enters anything other than an integer, they are repeatedly prompted until they do.

5. If the shift number entered by the user is a multiple of 26 (the length of the alphabet), it is incremented by 1 to avoid having a shift that leaves the text unchanged.

6. The `Caesar` function takes in three parameters: `start_text` (the text to be encrypted or decrypted), `shift_amount` (the number of positions to shift each letter), and `cipher_direction` ('encode' or 'decode'). It then iterates over each character in `start_text`. If the character is a letter, it finds its position in `alphabet`, calculates its new position by adding or subtracting `shift_amount` (depending on whether we're encoding or decoding), and appends the corresponding letter from `alphabet` to `end_text`. If the character is not a letter, it is appended to `end_text` as is.

7. After encoding or decoding, the function prints out the resulting text.

8. Finally, the user is asked if they want to run the program again. If they enter 'no', the program terminates; otherwise, it starts over from step 2.
#  Acknowledgements
I would like to thank Dr. Angela Yu.
## Authors

- [@Sookchand](https://github.com/Sookchand)


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## Tech Stack
The specific “tech stack” for this game includes:

Python: The core language used to implement the game logic.
## Documentation
Here are some resources that you might find helpful:

**Python Documentation and Tutorials:**
- [Real Python's Guide to Documenting Python Code](^1^)
- [Python's Official Website](^2^)
- [W3Schools Python Tutorial](^8^)
- [Python 3.11.5 Documentation](^9^)
- [TutorialsPoint Python Tutorial](^10^)

**Google Colab Documentation and Tutorials:**
- [Google Colab's Official Introduction](^4^)
- [Google Colab's Basic Features Overview](^5^)
- [TutorialsPoint Google Colab Tutorial](^12^)

## Lessons Learned
The lesson that can be learnt from this solution is:

- How to use Python to implement a simple encryption and decryption algorithm based on the Caesar cipher.
- How to use lists, strings, loops, conditional statements, and functions in Python.
- How to use the `input` function to get user input and validate it using `try` and `except` blocks.
- How to use the `lower` method to convert strings to lowercase and the `index` method to find the position of a character in a list.
- How to use the modulo operator (`%`) to wrap around the alphabet when shifting letters.
# Hi, I'm Sookchand! 👋

Strive to improve with each passing moment, surpassing the person I was in the previous minute, the previous hour, and even the person you were yesterday.
## 🚀 About Me
I have experience as a data scientist and machine learning engineer. I have worked on projects involving the development of predictive models, the optimization of machine learning algorithms, and the deployment of machine learning models. I have also worked on projects involving the analysis of large datasets, the development of data-driven insights, and the creation of data visualizations.
## 🛠 Skills
I possess a wide range of skills including:

- **Data Analysis**: Proficient in Data Exploration and Visualization, Model Evaluation and Analysis, and Regression Analysis.
- **Machine Learning**: Experienced in Neural Network and Deep Learning, Supervised Learning (including Classification, Regression, and Time Series), Decision Trees and Random Forests, Ensemble Learning, and Hyperparameter Tuning.
- **Libraries and Frameworks**: Skilled in using TensorFlow 2.0, NumPy, Scikit Learn, Keras, Pandas, React.js, Node.js, Express.js with Node.js.
- **Big Data Technologies**: Familiar with Hadoop, Apache Spark, Kafka, and Apache Flink.
- **Image Processing**: Capable of performing Image Recognition and Classification, and Transfer Learning.
- **Programming Languages**: Proficient in Python and R. Also have experience with HTML, CSS, JavaScript ES6, DOM, JQuery.
- **Database Management**: Knowledgeable in SQL and MongoDB along with Mongoose.
- **Web Development**: Experienced in HTML, CSS, Bootstrap 4, JavaScript ES6, DOM, JQuery.
- **Version Control Systems**: Comfortable with Git, GitHub.
- **Data Visualization Tools**: Proficient in Tableau and Power BI.
- **Authentication and Security**: Familiar with various authentication and security protocols.
- **Other Skills**: Comfortable working with GPU on Google Collab. Familiar with Unix Command-Line.

This diverse skill set allows me to tackle a variety of data science and web development projects.