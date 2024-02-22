# Selection of Backend Language for the Retail Mobile App

## Context

The team is working on a mobile app for a retail company. We need to choose a backend language for the server-side components that will allow them to use analytics tools or services.

## Decision

The team has decided to use Python as the backend language. We chose Python due to its compatibility with A.I. and Machine Learning. These tools will be used to enhance user experience by providing analytics.

## Rationale

Python's versatility and integration capabilities with A.I. and Machine Learning libraries such as Scikit-learn, TensorFlow and PyTorch make it an appropriate choice for the project. The team's goal is to use analytics tools to improve app performance and user experience.

## Consequences

Machine Learning is not ideal to execute on a device. Hence, API requests and responses are required to continuously exchange between the client-side javascript and server-side backend Python code. This may create performance and adaptation issues.
