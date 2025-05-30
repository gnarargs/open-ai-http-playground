# OpenAI HTTP Playground

HTTP examples for various OpenAI APIs.

## Responses API

[OpenAI Responses API](https://platform.openai.com/docs/guides/structured-outputs?api-mode=responses)

See [responses.http](responses-api.http).

#### Examples

- Create a response
- Get a response
- Passing `previous_response_id` instead of passing entire context
- Using built-in web search tool

## Structured Outputs
[OpenAI Structured Outputs](https://platform.openai.com/docs/guides/structured-outputs?api-mode=responses)

See [structured_outputs.http](structured_outputs.http).

#### Examples

- Respond with structured JSON instead of text 

#### Notes

- Structured Outputs use [JSON Schema](https://json-schema.org/overview/what-is-jsonschema) to define desired output structure
- Currently, all fields must be marked as required and `additionalPropeties` must be false


## Tools/Function Calling
[OpenAI Function Calling](https://platform.openai.com/docs/guides/function-calling?api-mode=responses)

See [tools.http](tools.http).

#### Examples

- Send request with no tool call, see that LLM can't respond
- Send same request with tool call, see that LLM responds with tool call
- Send followup request that includes the output from calling the requested tool
- Multiple tool calls in a single response

## Todo

- Add configuration to web search tool
- Add example code interpreter tool http://platform.openai.com/docs/guides/tools-code-interpreter
- Add example for computer use tool https://platform.openai.com/docs/guides/tools-computer-use