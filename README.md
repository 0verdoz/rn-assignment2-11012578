# rn-assignment2-11012578

# React Native Project

`JSON`
This is a simple React Native project that demonstrates how to change the background color, update the default text, and style text with different font weights.

## Tasks Implemented

### Task 1: Change Background Color

The background color of the main container was changed from `white` to `lightblue`.

### Task 2: Change Default Text

The default text was updated to `My name is Michel Kpodo`.

### Task 3: Style Text

The name `Michel Kpodo` was styled to be `bolder` than the rest of the text.

## Project Setup

To set up this project on your local machine, follow these steps:

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- [Expo CLI](https://reactnative.dev/docs/environment-setup) installed
- [Android Studio](https://developer.android.com/studio) and/or [Xcode](https://developer.apple.com/xcode/) installed for emulation

### Installation

1. **Clone the repository:**
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

2. **Install dependencies:**
   npm install

### Running the App

To run the app on an Android or iOS emulator, use the following commands:

- **For Android:**
  npm start

## File Changes

### Task 1: Change Background Color

```JSON
File: `App.js`

jsx
import React from 'react';
import { StyleSheet, View } from 'react-native';

const App = () => {
return (
<View style={styles.container}>
{/_ Other components _/}
</View>
);
};

const styles = StyleSheet.create({
container: {
flex: 1,
backgroundColor: 'lightblue',
alignItems: 'center',
justifyContent: 'center',
},
});

export default App;

### Task 2: Change Default Text

File: `App.js`

jsx
import React from 'react';
import { StyleSheet, View, Text } from 'react-native';

const App = () => {
return (
<View style={styles.container}>
<Text style={styles.text}>
My name is <Text style={styles.boldText}>Michel Kpodo</Text>
</Text> {/_ Change text to "My name is Michel Kpodo" _/}
</View>
);
};

const styles = StyleSheet.create({
container: {
flex: 1,
backgroundColor: 'lightblue',
alignItems: 'center',
justifyContent: 'center',
},
text: {
fontSize: 24,
},
boldText: {
fontSize: 24,
fontWeight: 'bold',
},
});

export default App;

### Task 3: Style Text

File: `App.js`

jsx
import React from 'react';
import { StyleSheet, View, Text } from 'react-native';

const App = () => {
return (
<View style={styles.container}>
<Text style={styles.text}>
My name is <Text style={styles.boldText}>Michel Kpodo</Text>
</Text>
</View>
);
};

const styles = StyleSheet.create({
container: {
flex: 1,
backgroundColor: 'lightblue',
alignItems: 'center',
justifyContent: 'center',
},
text: {
fontSize: 24,
},
boldText: {
fontSize: 24,
fontWeight: 'bold',
}
});

```

export default App;

## Committing Changes

### Task 1: Change Background Color

1. **Stage Changes:**
   git add .
2. **Commit Changes:**
   sh
   git commit -m "Task 1: Change background color to lightblue"
3. **Push Changes to Remote Repository:**
   sh
   git push origin main

### Task 2: Change Default Text

1. **Stage Changes:**
   sh
   git add .
2. **Commit Changes:**
   sh
   git commit -m "Task 2: Change default text to 'My name is Michel Kpodo'"
3. **Push Changes to Remote Repository:**
   sh
   git push origin main

### Task 3: Style Text

1. **Stage Changes:**
   sh
   git add .
2. **Commit Changes:**
   sh
   git commit -m "Task 3: Change font to make 'Michel Kpodo' bolder"
3. **Push Changes to Remote Repository:**
   sh
   git push origin main

## Conclusion

This project demonstrates basic React Native styling techniques and the process of committing code changes for different tasks. Each task focuses on a specific aspect of the app's UI, showcasing how to effectively manage and implement incremental changes in a React Native project.

This README file provides an overview of the tasks completed, detailed setup instructions, and a step-by-step guide on how to implement and commit the changes in the project.

```

```
