# MindMate.ai
![MindMate ai](https://github.com/AdityaSharma2003/MindMate.ai/assets/98648638/d3acb882-fa20-4649-aaeb-8234779bf332)

MindMate.ai is a full stack software as a service (SaaS) AI platform. The platform allows users to create and interact with chatbots that impersonate various celebrities and historical figures.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Introduction

MindMate.ai offers a user-friendly interface built with NextJs, ReactJs, TypeScript, and the ShadCn library. With authentication integrated using CLerk, users can easily sign up and log in, and engage in conversation with chatbots programmed to impersonate iconic figures. 

The pro plan allows user to also create their own personalised custom AI character

## Walkthrough Video

[Click here to watch the walkthrough video](https://drive.google.com/file/d/1xaWgEyKjTEXeEjjH0pDv2IBGsf79QB-u/view?usp=sharing)


## Features

- **User Authentication**: Secure signup and login functionality powered by Clerk.
- **Conversation with the AI character**: Used llama2-13b LLM model offering great expericience to users impersonating the charater.
- **Storing the character**: Utilizing Cloudinary for image, Pinecone for vector embeddings and MongoDB for the conversations to save the state of the chatbot.
- **Seamless Payments**: Integration with Stripe ensures smooth and secure transactions.
- **Restaurant Dashboard** Restaurant Owners can Make changes to their restaurant and real-time update Order status that will reflect into the customer's dashboarc

## Technologies Used

- Frontend: Next, React, TypeScript, ShadCn, TailwindCSS
- Backend: Node.js, MongoDB, Pinecone
- Authentication: Clerk
- Payments: Stripe
- Image Management: Cloudinary

## Getting Started

To get started with RapidEats, follow these steps:

1. Clone this repository.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Set up your environment variables.
5. Run the project servers using `npm run dev`.

## Contributing

We welcome contributions from the community to improve RapidEats. To contribute, please follow these steps:

1. Fork this repository.
2. Create a new branch for your feature (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
