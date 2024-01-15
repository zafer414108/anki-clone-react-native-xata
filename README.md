# React Native Anki Clone with API and Xata Database

This is a React Native Anki learning card clone with Expo Router and Express server using a [Xata database](https://xata.io/).

To run the project, check out the [Anki App](./ankiApp) and [Express API](./api) directories.

# Data Structure:

The sets and cards data are structured as arrays of objects, making it easy to manage and iterate over.
# Set IDs:

Each set has a unique ID (id property), and this ID is referenced in the cards data using the set property.
# Database Integration:

Your code likely uses these data sets when initializing the database with the /init route.
# Set Properties:

Each set object has properties such as title, description, private, cards, and id, which seem appropriate for defining sets.
# Card Properties:

Each card object has properties like question, answer, and set. These properties seem appropriate for defining cards associated with a set.
# Considerations:

Ensure that your database schema aligns with the structure of these data sets.
When handling images in sets, you're using a structure that includes base64Content, mediaType, and enablePublicUrl. Make sure your storage solution supports this format.


## Screenshots
![1-ezgif com-resize](https://github.com/zafer414108/anki-clone-react-native-xata/assets/147662873/14ba5135-a317-4d7f-9c50-49834bf8f63c)
![2-ezgif com-resize](https://github.com/zafer414108/anki-clone-react-native-xata/assets/147662873/d0b10583-2eda-4aa0-ba26-c141afe38364)
![3-ezgif com-resize](https://github.com/zafer414108/anki-clone-react-native-xata/assets/147662873/3a2c1f07-808f-414b-ac62-1038854f857c)

# Screen gif
![ezgif com-cut](https://github.com/zafer414108/anki-clone-react-native-xata/assets/147662873/5252e97d-2cbf-481c-bc6c-8e5a9506acf4)
