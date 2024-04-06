# Currency Converter Bot

Currency Converter Bot is a chatbot built using Dialogflow that allows users to convert between different currencies. The bot provides real-time exchange rates and supports various currencies worldwide.

## Features

- **Currency Conversion**: Users can specify an amount and select the source and target currencies for conversion.
- **Real-Time Exchange Rates**: The bot fetches real-time exchange rates from an external API to provide accurate conversion results.
- **Multi-Currency Support**: The bot supports a wide range of currencies, allowing users to convert between different currency pairs.
- **Interactive Conversations**: Users can interact with the bot in natural language to perform currency conversions seamlessly.

## Usage

To use the Currency Converter Bot, follow these steps:

1. **Accessing the Bot**: The bot can be accessed through various platforms, including web chat, messaging apps, or voice assistants.
2. **Initiating Conversion**: Start a conversation with the bot and specify the amount to convert and the source currency.
3. **Selecting Target Currency**: Choose the target currency to which you want to convert the specified amount.
4. **Viewing Conversion Result**: The bot will provide the converted amount based on real-time exchange rates.

## Example Conversion
![image](https://github.com/prithviraj-ai/Currency-converter-bot/assets/127374751/e3c7801a-ae85-4f52-95d9-56f6a5632013)

## Technologies Used

- **Dialogflow**: Dialogflow is used for natural language understanding and conversation management.
- **External API**: An external API (such as Open Exchange Rates or CurrencyLayer) is used to fetch real-time exchange rates.
- **Python**: Python is used for backend development to handle currency conversion logic and API integration.
- **Flask/Django**: Flask or Django frameworks can be used to build the backend server for handling webhook requests from Dialogflow.

## Setup and Deployment

1. **Dialogflow Setup**: Set up a Dialogflow agent and configure intents and entities related to currency conversion.
2. **API Integration**: Integrate an external API to fetch real-time exchange rates. Obtain API keys and configure the integration in your backend.
3. **Backend Development**: Develop the backend server using Python and Flask/Django to handle webhook requests from Dialogflow and perform currency conversions.
4. **Deployment**: Deploy the backend server to a hosting provider such as Heroku, Google Cloud Platform, or AWS.
5. **Testing**: Test the bot thoroughly to ensure accurate currency conversions and seamless user experience.

## Contributing

Contributions to the Currency Converter Bot project are welcome! If you have any suggestions, feature requests, or bug reports, please open an issue or submit a pull request on GitHub.

## License

This project is licensed under the [MIT License](LICENSE).
