# Chatbot Framework

This Chatbot Framework package provides a basic framework for building chatbots in JavaScript applications. It includes a `Chatbot` class with methods for sending and receiving messages.

## Installation

You can install the Chatbot Framework package via npm:

```bash
npm install chatbot-framework
```

## Usage

Import the `Chatbot` class into your JavaScript code:

```javascript
const Chatbot = require('chatbot-framework');
```

### Creating a Chatbot Instance

To create a new chatbot instance, instantiate the `Chatbot` class with a name:

```javascript
const myChatbot = new Chatbot('MyChatbot');
```

### Sending Messages

To send a message from the chatbot, use the `sendMessage` method:

```javascript
myChatbot.sendMessage('Hello, world!');
// Output: MyChatbot sent message: Hello, world!
```

### Receiving Messages

To receive a message by the chatbot, use the `receiveMessage` method:

```javascript
myChatbot.receiveMessage('How are you?');
// Output: MyChatbot received message: How are you?
```

## License

This Chatbot Framework package is licensed under the [MIT License](LICENSE).
