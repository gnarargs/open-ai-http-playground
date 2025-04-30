# OpenAI HTTP Playground

HTTP examples for various OpenAI APIs.

## Responses API

[OpenAI Responses API](https://platform.openai.com/docs/guides/structured-outputs?api-mode=responses)

See [responses.http](responses.http).

TODO:
- Add example that uses `instructions` to pass role in one request but does not follow through on next request when using previous reponses id.

## Tools/Function Calling
[OpenAI Function Calling](https://platform.openai.com/docs/guides/function-calling?api-mode=responses)

See [tools.http](tools.http).

## Structured Outputs
[OpenAI Structured Outputs](https://platform.openai.com/docs/guides/structured-outputs?api-mode=responses)

See [structured_outputs.http](structured_outputs.http).

Notes:
- Using JSON Schema, all fields must be required and `additionalPropeties` must be false
